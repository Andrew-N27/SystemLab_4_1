# SystemLab_4_1

Задание 1
Создайте приложение, использующее механизм мьютексов. Создайте в коде приложения несколько потоков.
Первый поток отображает числа от 0 до 20 в порядке
возрастания. Второй поток ожидает, когда завершится
первый, после чего отображает числа от 0 до 10 в обратном
порядке. Вывод данных необходимо выполнять в консоль.



Задание 2
Создайте приложение, использующее механизм мьютексов.
Создайте в коде приложения несколько потоков. Каждый из
потоков получает массив с данными. Первый поток должен
модифицировать элементы массивы, увеличив каждый на
некоторое случайное число (элемент массива + случайное
число). Второй поток ожидает, когда пройдет модификация
всего массива, после чего находит максимальное значение
в этом массиве и отображает его на экран. Вывод данных
(массив и максимум) необходимо выполнять в консоль.



Задание 3
Модифицируйте второе задание. Необходимо отображать максимальное значение и модифицированный
массив вне потоковой функции. Например, отображение
можно выполнять в Main.



Задание 4
Создайте консольное приложение, которое может запускаться только в одной копии. При попытке запустить
вторую копию необходимо отображать информационное
сообщение и закрывать приложение.



Задание 5
Создайте приложение, использующее механизм семафоров. Создайте в коде приложения десять потоков.
Каждый из потоков выводит набор случайных чисел
после чего завершает свою работу. Перед отображением
нужно показать идентификатор потока. Одновременно
могут исполняться только три потока, остальные потоки
выстраиваются в очередь. Как только какой-то поток
завершает своё исполнение, новый запускается.



Задание 6
Реализуйте первое задание внутри приложения с оконным интерфейсом. Выбор элементов управления остаётся
за вами.



Задание 7
Реализуйте второе задание внутри приложения с оконным интерфейсом. Выбор элементов управления остаётся
за вами. 
