// Домашнее задание 1
// Задача 2

/*Console.WriteLine("Введи число 1: ");
int number1 = int.Parse(Console.ReadLine());

Console.WriteLine("Введи число 2: ");
int number2 = int.Parse(Console.ReadLine());

if (number1 > number2)
{
Console.WriteLine($"бОльшее число {number1}");
}
else

Console.WriteLine($"бОльшее число {number2}");*/

// Задача 4

/*Console.WriteLine("Введи число 1: ");
int A = int.Parse(Console.ReadLine());

Console.WriteLine("Введи число 2: ");
int B = int.Parse(Console.ReadLine());

Console.WriteLine("Введи число 3: ");
int C = int.Parse(Console.ReadLine());

if (A>B) 
{
if (A>C) 
{
Console.WriteLine($"бОльшее число {A}");
}
}

else 
if (B>C)
{
 Console.WriteLine($"бОльшее число {B}");   
}

else
Console.WriteLine($"бОльшее число {C}");*/

//Задача 6

/*Console.WriteLine("Введи число: ");
int A = int.Parse(Console.ReadLine());

if (A % 2 != 0) 
{
Console.WriteLine($"Число {A} четное");
}

else
{
    Console.WriteLine($"Число {A} нечетное");
}*/

// Задача 8

Console.WriteLine("Введи число: ");
int N = int.Parse(Console.ReadLine());

int A = 1;
 Console.WriteLine($"");
 Console.Write($"Чeтные числа:");
while (A <= N)
{
if (A % 2 == 0) 
{
    Console.Write($" {A}");
    
}
A += 1;
}
Console.WriteLine($"");