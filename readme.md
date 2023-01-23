### Итоговая проверочная работа.
> **1. Задача.**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
> **2. Описание алгоритма решения.**

1. Задаем массив из строк на старте выполнения. 
2. Далее создаем еще один массив из строк такой же длины(длина строк второго массива будет равна длине строк первого массива). 
3.  Запускаем цикл по параметрам: цикл будет продолжаться до тех пор, пока счетчик i(он же индекс строки массива - необходим для того, чтобы проходить массив от начала до конца) будет меньше длины массива. Изначально i = 0. При каждом проходе i будет увеличиваться на 1.
4.  Проверяем условие: если длина строки массива будет меньше либо равна 3, то строка второго массива равно строке первого(изначального) массива. Далее срабатывает счетчик j(он же индекс строки массива). При каждом проходе j будет увеличиваться на 1.
5.  После этого снова цикл по параметрам. 
6.  Если же после цикла по параметрам попадаем в условие (пункт 4) и условие не будет соответствовать действительности, то возвращаемся в цикл по параметрам.
7. Когда пробежимся по всему массиву, то в итоге выведем новый массив только со строками, которые будут равны строкам первого массива, где длина строки массива меньше либо равна 3.

> **3. Изображение блок-схемы.**

Блок-схема содержится в файле **Final.jpg**  в папке **block_diagram**.

> **4. Написание программы, отвечающей описанному алгоритму.**

Программа находится в папке **task**.