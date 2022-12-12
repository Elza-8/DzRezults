Решение задачи в текстовом формате
Функция, которая состоит в наличии массива элементов, состоящих из не более 3х записей и записывающей их в новый массив:

строка [] ArrayUpToThree (строка [] массив1)

{

int sizeArray2 = 0;

for (int i = 0; i < array1.Length; i++)
    if (array1[i].Length <= 3) sizeArray2++;

string[] array2 = new string[sizeArray2];

for (int i = 0, j = 0; i < array1.Length; i++)
    if (array1[i].Length <= 3)
    {
        array2[j] = array1[i];
        j++;
    }
return array2;
}

Функция, которая выводит массив:

void ShowArray (массив строк [])

{

for (int i = 0; i < array.Length; i++)
{
    Console.Write(array[i] + " ");
}
Console.WriteLine();
