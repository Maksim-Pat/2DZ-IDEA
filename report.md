# Отчёт о тестировании 
Название приложения: Money Transfer

# Краткое описание
02.04.2021 - 02.04.2021 было проведено smoke test приложения Money Transfer.
На тестирование затрачено: 2 (два) часа.

В результате тестирования выявлены следующие дефекты:
* [Отрицательная сумма после перевода #1](https://github.com/Maksim-Pat/2DZ-IDEA/issues/1)


# Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «1.2. Программирование на Java: переменные, операторы, работа с отладчиком»](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
* IDEA
В качестве тестовых данных использовались данные:
Код
 public class Main {
    public static void main(String[] args) {
        int balanse = 2_000_000_000;
        int count = 500_000_000;
        int total = balanse + count;
        System.out.println(total);
    }
}

Тестирование производилось в следующем окружении:

* Windows 7
* IntelliJ IDEA Community Edition 2020.3.3