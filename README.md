# *Задача*
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## **Текстовое описание решения**

Сначала объявляем два массива,одинаковой длины.
Потом метод, в котором цикл такой же длины что и массив, внутри цикла проверку условия (<= 3), если да элемент первого массива заносится в count элемент второго массива.
Переменная Count что бы из первого массива поочереди переносить во второй.После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.