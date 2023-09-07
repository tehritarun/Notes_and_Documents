# C# Basics

## String

```csharp
string phrase;
phrase = "Something";
phrase.Length;
phrase.ToUpper();
phrase.Contains("thing");
phrase[0];
phrase.IndexOf("thing");
phrase.Substring(5);
```
The output for above code will be as below:
```cmd
9
SOMETHING
True
S
4
hing
```
## Integers
```csharp
int num=6;
num++;
num--;
Convert.ToInt32("45");
Math.Abs(-40);
Math.Pow(3,2);
Math.Sqrt(16);
Math.Round(47.6);
```
The output for above code will be as below:
```
7
6
45
40
9
4
48
```
## Arrays
```csharp
int[] numbers={3,6,8};
Console.WriteLine(numbers[2]);
numbers[1]=90;
Console.WriteLine(numbers);
```