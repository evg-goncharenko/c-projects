## Собеседование в Яндекс

*Read this in other languages: [English](README.md), [Русский](README.ru.md).*

<b> [Задача A. Кинотеатр](./1_task.cpp): </b><br>

Поиск подходящего места в кинотеатре.<br>
Найти свободное место с наибольшим расстоянием до ближайших занятых мест.<br>

<br><b>Формат ввода:</b><br>
Первая строка входного файла содержит одно число `n`, `n ≤ 10000`.
Каждая из следующих `n` строк содержит ровно одно число — 0 или 1 (свободно или занято место).

<br><b>Формат вывода:</b><br>
Выходной файл должен содержать единственное число — максимальную длинну до ближайшего занятого места.

<br><b>Ввод:</b><br>
```none
7
1
0
1
0
0
0
1
```

<br><b>Вывод:</b><br>
```none
2
```

<br> <b> [Задача B. Последовательно идущие единицы](./2_task.cpp): </b><br>

Требуется найти в бинарном векторе самую длинную последовательность единиц и вывести её длину,
при условии обязательного удаления одного элемента.<br>

<br><b>Формат ввода:</b><br>
Первая строка входного файла содержит одно число `n`, `n ≤ 10000`.
Каждая из следующих `n` строк содержит ровно одно число — 1 или 0.

<br><b>Формат вывода:</b><br>
Выходной файл должен содержать единственное число — длину самой длинной последовательности
единиц во входном массиве.

<br><b>Ввод:</b><br>
```none
8
0
1
0
1
1
0
1
1
```

<br><b>Вывод:</b><br>
```none
4
```

<br> <b> [Задача C. Прямая симметрии](./3_task.cpp): </b><br>

Дан произвольный набор целочисленных точек. Можно ли провести вертикальную прямую, которая будет
являться прямой симметрии? <br>

<br><b>Формат ввода:</b><br>
Первая строка входного файла содержит единственное число `n`, `n ≤ 1000000`.
На следующих `n` строк расположены пары чисел — координаты точек, по одной на строку.

<br><b>Формат вывода:</b><br>
Выходной файл должен содержать `Yes`, если такую прямую можно провести, и `No` в противном случае.

<br><b>Ввод:</b><br>
```none
3
-5 7
5 7
0 2
```

<br><b>Вывод:</b><br>
```none
Yes
```

<br> <b> [Задача D. Удаление повторов](./4_task.cpp): </b><br>

Дан шаблон функции:<br>
```cpp
void remove(std::vector<int>&v, int val);
```
Необходимо удалить из вектора `v` все элементы, равные `val`. 

<br> <b> [Задача E. Стек](./5_task.cpp): </b><br>

Необходимо реализовать класс `Stack`, с методами: `push()`, `pop()`, `max()` работающие за O(1).<br>
Метод `max()` возвращает текущий максимум в стеке.
