# C-Tricky-Cheat-sheet-for-interview.

# 🔥 C# Interview Tricky Coding Cheatsheet (Top 20)

This repository contains commonly asked **tricky C# interview questions** with outputs and explanations to help you crack .NET interviews.

---

# 1. String Immutability

```csharp
string s = "A";
s.ToLower();
Console.WriteLine(s);

string s = "Hello";
s.Replace("H", "J");
Console.WriteLine(s);

```
🚀 2. String Interning
string a = "Hello";
string b = "Hello";

Console.WriteLine(object.ReferenceEquals(a, b));
