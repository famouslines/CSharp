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
5. binary literal
```
int b1 = 0b1010; 
Console.WriteLine(b1); // 10
int b2 = 0B0001_1010; 
Console.WriteLine(b2); // 26
```
6. var & dynamic
```
var i = 10; // similar to auto keyword in C++
Console.WriteLine(i);
//i = "hello"; compile error
//Console.WriteLine(i);

dynamic a = 10;
Console.WriteLine(a);
a = "hello";
Console.WriteLine(a);
```
