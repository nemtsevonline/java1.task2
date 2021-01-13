Отчёт о тестировании кода Credit Card Number Validator

Краткое описание

12.01.2020 - 13.01.2020. Было проведено функциональное тестирование (валидация номеров банковской карты.) кода Credit Card Number Validator

На тестирование затрачено: 2 часа

В результате тестирования не были выявлены дефекты.

Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

1.Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA» https://github.com/netology-code/javaqa-homeworks/tree/master/intro
2.Установка IntelliJ IDEA https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md


Тестовые данные

Валидные номера карт:

4221338900396804 - ожидаемый результат - Result is OK
4998330321786680 - ожидаемый результат - Result is OK
5382637894624358 - ожидаемый результат - Result is OK
5223388713514015 - ожидаемый результат - Result is OK
5556444847129001 - ожидаемый результат - Result is OK


Невалидные номера карт:

1111111111111111 - ожидаемый результат - Result is FAIL
1234567890123456 - ожидаемый результат - Result is FAIL
44674675758576877 - ожидаемый результат - Result is FAIL
0000000000000000 - ожидаемый результат - Result is FAIL
…………… - ожидаемый результат - Result is FAIL

Тестирование производилось в следующем окружении:

Windows 10 Home 64 bit
версия Java 11.0.9.1