# Palindrome
## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare two variable with string datatype

### Step3:
Loop over the entire string and reverse it

### Step4:
Use if condition to check whether the string and the reversed string is equal or not

### Step5:
print palindrome if it's equal else print not a palindrome.

### Step6:
stop
<br/>

## Program:
```cs

using System;
namespace palindrome
{
    class Pals
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter any string");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("{0} is Palindrome", revs);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```
## Output:
![mala](https://user-images.githubusercontent.com/75234646/188787954-fc86adc1-88c1-42b7-87b3-a6e8543fba4d.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
