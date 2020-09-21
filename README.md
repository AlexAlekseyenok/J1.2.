# Отчёт о тестировании **приложения "Credit Card Number Validator"**

## Краткое описание

20.09.2020 - 20.09.2020 было проведено функциональное позитивное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
1. [FAIL если длина номера карты более или менее 16 символов](https://github.com/AlexAlekseyenok/J1.2./issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Документация: "[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)";
* Исполняемый код приложения: [Задача №2 - Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro).

В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):

Валидные значения номеров карт:
* 4556781776280013
* 5480940234554884
* 6761051880176044
Невалидные значения номеров карт:
* 4716077776884773912
* 3539469055933213813
* 343382771908066

Тестирование производилось в следующем окружении:
* Windows 10 версия 1903, разрядность ОС: x64;
* Java 11.0.8;
* IntelliJ IDEA 2020.2.2 (Community Edition)
