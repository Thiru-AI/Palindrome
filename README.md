# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
## Step 1:
Develop a C# program using a class.

## Step 2:
Initialize two strings in which one is input string and another one is empty string.

## Step 3:
Using for loop reverse the characters from the input string and store it in the empty string.

## Step 4:
Print the string and check whether it is palindrome or not.

## Program:
~~~
Name:Thirugnanamoorthi G
Reg no:212221230117
~~~
~~~
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string: ");
            s = Console.ReadLine();
            s = s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("String is Palindrome");
            }
            else
            {
                Console.WriteLine("String is not Palindrome");
            }
        }
    }
}
~~~

## Output:
![1](https://user-images.githubusercontent.com/94980741/226581077-51869d15-2611-486a-9965-931991b22717.png)
![2](https://user-images.githubusercontent.com/94980741/226581211-5be3cf2d-d293-47d4-8808-9155dbe89702.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
