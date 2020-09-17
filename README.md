## Guide
온라인 개발툴   
https://try.dot.net   

온라인 도움말   
https://docs.microsoft.com/ko-kr/

How to use C# Interactive   
http://appetere.com/post/how-to-use-csharp-interactive   

## 문법
1. null이 허용되는 기본 data type 선언하기
```
Nullable<int> x = null; 
int? x = null; 
```
2. MultiLineString
```
string mlstr = @"
This is
   MultiLineString
";
```
3. StringInterpolation
```
string message = "String interpolation";
Console.WriteLine("Message: {0}", message); 
Console.WriteLine("Message: " + message); 
Console.WriteLine(String.Format("Message: {0}", message)); 
Console.WriteLine($"Message: {message}"); // C# 6.0 
```
4. GetType
```
int i = 1234;
Console.WriteLine(i.GetType()) // System.Int32
```
5. Convert
```
int number = 10; 
Convert.ToString(number, 2); // "1010"
Convert.ToString(number, 2).PadLeft(8, '0'); // "00001010"
Convert.ToInt32("00001010", 2) // 2진수인 string "00001010"을 정수형으로 변환하라. 
```
