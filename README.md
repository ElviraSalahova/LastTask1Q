Задача :

Написать программу, которая из имеющегося массива строк формирует массив из строк, 
длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, 
либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

Решение :

Объявляется два массива: первый и вторый, одинаковой длины. Метод,  внутри цикла проверяет условие, является ли длтна элемент массива <=3 символов.
Если да элемент первого массива заносится в count элемент второго массива.
Переменная count поочередно записывает во второй массив во второй все совпадающте значения массиса 1. 
После каждой последующей итерации увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1.
И так проверяется до конца.

Графическое решение в папке Schem .

Алгоритма в Program.cs
