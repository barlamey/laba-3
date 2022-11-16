# Здравствуйте, дорогие студенты!

Лабораторная работа #3 выполняется по вариантам. Варианты считаются так: переводите свою фамилию на английский, смотрите на ASCII-код по [этой таблице](https://www.johndcook.com/ascii.png) и берёте (остаток от деления ASCII-кода на 2) + 1. Выполнение неправильного варианта будет приравнено к нулю.
## Дедлайн 28.11

При форке репозитория Вы редактируете свой README.md файл таким образом:

```README.md```:
```Markdown
<# Варианта> + <ФИО> + <Группа>

 ТУТ ДОЛЖНО БЫТЬ ТЕЛО ОТЧЁТА
 ```

## Задание для первого варианта:

Дано натуральное число строк `0 < T <= 10000`, в каждой из которых заданы 2 вещественных числа с точностью до второго знака после запятой - это отрезки на числовой прямой. В выводе запишите отрезок, являющийся пересечением всех отрезков. В случае отсутствия выведите сообщение *"NO INTERSECTIONS"*. 
Код программы должен содержать ввод с консоли флага `--tofile` и `--fromfile`. Первый говорит нам, что ввод будет задан в заданный пользователем в командной строке файл (в случае отсутствия файла создать его), а второй говорит о считывании из файла заданного пользователем. Предусмотреть возможность исполнения обоих флагов. Учесть возможность некорректного ввода и обработать исклюючения. На дополнительный балл добавьте тесты, по возможности Google-Tests. 
```
Пример ввода:

5
1.2 3.4
-1.8 0.1
0.5 1.5
1.3 2.8 
-2 -1

Вывод для примера выше:

-2 0.1
0.5 3.4

```


## Задание для второго варианта:

Вводится последовательность предложений, оканчивающихся точкой. Предложения могут занимать более одной строки. Выведите все предложения в порядке неубывания длин ровно по одному на строку, заменяя перенос строки в исходном вводе пробельным символом. Код программы должен содержать ввод с консоли флага `--tofile` и `--fromfile`. Первый говорит нам, что ввод будет задан в заданный пользователем в командной строке файл (в случае отсутствия файла создать его), а второй говорит о считывании из файла заданного пользователем. Предусмотреть возможность исполнения обоих флагов. Учесть возможность некорректного ввода и обработать исклюючения. На дополнительный балл добавьте тесты, по возможности Google-Tests. 
```
Пример ввода:

Alice's Adventures in Wonderland is a children's novel. The title is usually shortened to Alice in Wonderland. Charles Lutwidge Dodgson wrote the book. He wrote it using the pen name Lewis Carroll. John Tenniel drew the 42 pictures in the book. The book was published by Macmillan and Co in London. It was released on 26 November 1865. It has been adapted to numerous movies. In 2010, it has been adapted to Hollywood movie.

Вывод для примера выше. 

It was released on 26 November 1865.
It has been adapted to numerous movies.
Charles Lutwidge Dodgson wrote the book.
He wrote it using the pen name Lewis Carroll.
John Tenniel drew the 42 pictures in the book.
In 2010, it has been adapted to Hollywood movie.
The book was published by Macmillan and Co in London.
The title is usually shortened to Alice in Wonderland.
Alice's Adventures in Wonderland is a children's novel.

```
