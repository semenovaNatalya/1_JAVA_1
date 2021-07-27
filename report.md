# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

25/07/2021 - 25/07/2021 было проведено санитарное тестирование, являющееся частью регрессионного тестирования приложения Credit Card Number Validator.
27/07/2021-27/07/2021 исправление ошибок

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* Невалидные номера карт платежной системы Diners Club - International (https://github.com/semenovaNatalya/1_JAVA_1/issues/10) 
* Невалидные номера карт ПС American Express (AMEX)  (https://github.com/semenovaNatalya/1_JAVA_1/issues/4)
* Невалидный 19-значный номер карты платежной системы VISA (https://github.com/semenovaNatalya/1_JAVA_1/issues/11)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* баг репорты, оформленные ввиде Issues
  https://github.com/semenovaNatalya/1_JAVA_1/issues



В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* номера банковских карт разных платежных систем с ожидаемой их валидностью


Тестирование производилось в следующем окружении:
* Windows 10 Pro, 64-разрядная 
* Java 11.0.11
* IntelliJ IDEA среда разработки