# FinalWork1
## Задача: 
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Описание решения:
### Создаем один массив строк из 4-х элементов  и второй массив с длинной первого массива. Создаем переменную количества равную нулю и метод, в котором с помощью цикла,  создаем условие (символ <= 3), ищем таким образом подходящие элементы. Если искомый элемент попадает под условие, заносим его в переменную количества и приравниваем к элементу второго массива. Далее  увеличиваем счетчик цикла на 1 и продолжаем перебирать элементы цикла. Когда счетчик будет больше длинны первого массива цикл заканчивается. Далее создаем метод печати массива и выводим искомые элементы в консоль.