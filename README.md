## Представляю Вашему вниманию алгоритм решения следующей задачи:
Написать программу, которая из имеющегося строк формирует массив из строк, длинна которых меньше либо равна 3 символа. Первоначальный массив можно задать с помощью клавиатуры, либо задать на старте выполнения алгоритма. 
* *Пример: ["hello", ":-)", "2", "world"] - > [":-)", "2"]*
### Алгоритм
1. Вводим необходимое количество элементов массива __arrayStart__ в консоли.
2. Вводиться "пустой" массив __arrayFinish__ с количеством элементов равное *arrayStart.Length*.
3. Вводиться переменная __indTask=0__, используемая в дальнейшем цикле.
4. С помощью цикла *for: i=0, i<arrayStart.Length, i++* в массив __arrayFinish__ записываются элементы массива __arrayStart__, удовлетворяющие условию *arrayStart[i].Length<=3*.
5. Выводятся элементы массивa __arrayStart__ не равные *null* в формате *["a","b"..]* с помощью метода *ShowArray* и далее в этой строке символы " - >"
6. Далее в той же строке выводятся элементы массивa __arrayFinish__ тем же методом. 
