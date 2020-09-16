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
int number = 3;
string result = "홀수";
Console.WriteLine($"{number}은(는) {result}입니다."); // C# 6.0 이후

Console.WriteLine("{0}은(는) {1}입니다.", number, result);
```

