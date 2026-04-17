# C-Tricky-Cheat-sheet-for-interview.

# 🔥 C# Interview Tricky Coding Cheatsheet (Top 20)

This repository contains commonly asked **tricky C# interview questions** with outputs and explanations to help you crack .NET interviews.

---

# 1. String Immutability

```csharp
string s = "Hello";
s.Replace("H", "J");
Console.WriteLine(s);
```
Output:
Hello

# 2. Value vs Reference type
```csharp
class Person
{
    public string Name;
}

Person p1 = new Person();
p1.Name = "A";

Person p2 = p1;
p2.Name = "B";
Console.WriteLine(p1.Name);
```
Output:
B
---
## Concept
- Objects are reference types.
---

