 Написать программу, которая из имеющегося массива строк формирует новый массив из строк,  длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры,  либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями,  лучше обойтись исключительно массивами.
 [“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
 [“1234”, “1567”, “-2”, “computer science”] → [“-2”]


Решение:
-Создаем "массив"
-Создаем второй "новый массив" с размером 0
-Перебираем все элементы "массива"
-Условие: если длина элемента "массива"(строка) <= 3, то увеличиваем размер(длина) "новый масиив" на 1 и
 присваиваем ему    значение, которое сейчас по индексу в "массиве"
-Выводим "новый массив"