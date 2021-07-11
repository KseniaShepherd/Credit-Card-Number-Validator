# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

<09/09/2021> - <09/09/2021> было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [Дефект 1](https://github.com/KseniaShepherd/CCNumber-Validator/issues/1)
* [Дефект 2](https://github.com/KseniaShepherd/CCNumber-Validator/issues/2)
* [Дефект 3](https://github.com/KseniaShepherd/CCNumber-Validator/issues/3)
* [Дефект 4](https://github.com/KseniaShepherd/CCNumber-Validator/issues/4)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Тестовый сценарий Credit Card Number Validator](https://docs.google.com/spreadsheets/d/1OFXGwz_N1cowItEkZD0nuphqCre3IPkmhtTbEdFIDGY/edit?usp=sharing)


В качестве тестовых данных использовались данные  из источника: [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):

* VISA: 

4716863430834190 - Result is OK

4556849601925563 - Result is OK

4787908164328701334- Result is OK

* MasterCard:

5241953816305625 - Result is OK

5522893793494671 - Result is OK

5573658109120650 - Result is OK

* American Express (AMEX): 

348591710072603 - Result is OK

377843073084236 - Result is OK

341719344236628 - Result is OK

* Maestro: 

0604623709177199 - Result is OK

6762725836073103 - Result is OK

6763707597982192 - Result is OK

* Visa Electron:

4844743957794263 - Result is OK

4917272197965048 - Result is OK

4026850459626560 - Result is OK

* InstaPayment: 

6399004426083158 - Result is OK

6382398999956025 - Result is OK

6387537051841519 - Result is OK

Тестирование производилось в следующем окружении:
* Mac OC Catalina Version 10.15.7 (19H1030)
* OpenJDK version "11.0.11" 2021-04-20
* IntelliJ IDEA 2018.3.6 (Ultimate Edition) 

