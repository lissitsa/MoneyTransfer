# Отчёт о тестировании Money Transfer

## Краткое описание

15.07.2021 - 15.07.2021 было проведено функциональное тестирование приложения Money Transfer

На тестирование затрачено: 2 минуты

В результате тестирования выявлены следующие дефекты:

[Не верное итоговое значение при проведении пополнения счета VIP-клиента в приложении Money Transfer](https://github.com/lissitsa/MoneyTransfer/issues/1#issue-945701277)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* тестовые данные

В качестве тестовых данных использовались следующие данные:

* balance = 2_000_000_000
* transfer = 500_000_000

Тестирование производилось в следующем окружении:
* ОС Windows 7 Домашняя расширенная SP1, 64-разрядная
* версия Java 11