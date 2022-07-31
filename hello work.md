Привет
//Задача 10: Напишите программу, которая принимает на вход трёхзначное число и на выходе показывает вторую цифру этого числа.

//456 -> 5
//782 -> 8
//918 -> 1



// Console.Write("Введите трёхзначное число: ");
// int threeDigitNumber = Convert.ToInt32(Console.ReadLine());
// string stringNumber = Convert.ToString(threeDigitNumber);
// Console.WriteLine("вторая цифра этого числа -> "+stringNumber[1]);

/*



Задача 15: Напишите программу, которая принимает на вход цифру, обозначающую день недели, и проверяет, является ли этот день выходным.

6 -> да
7 -> да
1 -> нет
*/

/*Console.Write("Цифра дня недели: " );
int dayNumber = Convert.ToInt32(Console.ReadLine());
void ProverkaDnyaNedeli (int dayNumber) 
{
  if (dayNumber == 6 || dayNumber == 7) 
  {
  Console.WriteLine("(этот день выходной) - да");
  }

  else if (dayNumber < 1 || dayNumber > 7) 
  {
    Console.WriteLine("этот день не выходной");

  }
  else Console.WriteLine("(данный день не является выходным) - нет");
}

ProverkaDnyaNedeli(dayNumber);
*/

// СЕМИНАР 3
// Задача 19
// Внимание! Решите, пожалуйста, задачку через числа (без string)

// Напишите программу, которая принимает на вход пятизначное число и проверяет, является ли оно палиндромом.

// 14212 -> нет

// 12821 -> да

// 23432 -> да

// Console.Write("Введите число :");
// int number = Convert.ToInt32(Console.ReadLine());
// int firstNum = Convert.ToInt32(Console.ReadLine());
// int secNum = Convert.ToInt32(Console.ReadLine());
// int thirdNum = Convert.ToInt32(Console.ReadLine());
// int fourtyNum = Convert.ToInt32(Console.ReadLine());
// int FifthyNum = Convert.ToInt32(Console.ReadLine());   
// if (number > 0 && number < 10);
// {
//    Console.WriteLine("Это палиндром: ");
// }
// else if (number >= 10 && number < 100);
// {
//    firstNum = number / 10;
//    secNum = number % 10;
// if (firstNum==secNum);
// {
//    Console.WriteLine("Это палиндром: ");
// }
// else
// {
//   Console.WriteLine("Это не палиндром: "); 
// }
// }
// else if (number >= 100 && number < 1000);
// {
//    firstNum = number / 100;
//    secNum = number % 100/ 10;
//    thirdNum = number % 10;
//    if = (firstNum == thirdNum);
//    {
//       Console.WriteLine("Это палиндром: ");
//    }
// }
// else
// {
//   Console.WriteLine("Это не палиндром: "); 
// }
// else if (number >= 1000 && number < 10000);
// {
//     firstNum = number / 1000;
//     secNum = number % 1000 / 100;
//     thirdNum = number % 100 / 10;
//     fourtyNum = number % 10;
//     if (firstNum == fourtyNum && secNum == thirdNum);
//     {
//        Console.WriteLine("Это  палиндром: "); 
//     }
//     else
//     {
//        Console.WriteLine("Это не палиндром: "); 
//     }
//     }
//     else if (number >= 10000 && number < 100000);
//     {
//        firstNum = number / 10000;
//     secNum = number % 10000 / 1000;
//     thirdNum = number % 1000 / 100;
//     fourtyNum = number % 100 / 10;
//     FifthyNum = number % 10;
//    if (firstNum == FifthyNum && secNum == fourtyNum);
//    {
//       Console.WriteLine("Это  палиндром: "); 
//    }
//    else
//    {
//       Console.WriteLine("Это не палиндром: "); 
//    }
//     }
    
//     Задача 21

// Напишите программу, которая принимает на вход координаты двух точек и находит расстояние между ними в 3D пространстве.

// A (3,6,8); B (2,1,-7), -> 15.84

// A (7,-5, 0); B (1,-1,9) -> 11.53



// Console.WriteLine("Введите координату х1:");
// int x1 = Convert.ToInt32(Console.ReadLine()); 
// Console.WriteLine("Введите координату y1:");
// int y1 = Convert.ToInt32(Console.ReadLine()); 
// Console.WriteLine("Введите координату z1:");
// int z1 = Convert.ToInt32(Console.ReadLine()); 
// Console.WriteLine("Введите координату х2:");
// int x2 = Convert.ToInt32(Console.ReadLine()); 
// Console.WriteLine("Введите координату y2:");
// int y2 = Convert.ToInt32(Console.ReadLine()); 
// Console.WriteLine("Введите координату z2:");
// int z2 = Convert.ToInt32(Console.ReadLine()); 
// double resultAB =Math.Sqrt(Math.Pow(x2-x1, 2) + Math.Pow(y2-y1, 2) + Math.Pow(z2 - z1, 2));
// System.Console.WriteLine(resultAB);

// Задача 23

// Напишите программу, которая принимает на вход число (N) и выдаёт таблицу кубов чисел от 1 до N.

// 3 -> 1, 8, 27
// 5 -> 1, 8, 27, 64, 125
// int number = Convert.ToInt32(Console.ReadLine());
// // (начало, условие для цикла, увеличение счетчика на 1)
// // 1
// for (int i = 1; i <= number; i++)
// {
// Console.WriteLine($"Результат: {i * i * i}"); // интерполяция
// }

// int number = Convert.ToInt32(Console.ReadLine());
// int start = 1;
// while (start <= number)
// {
// Console.WriteLine(start*start*start);
// start++;
// }