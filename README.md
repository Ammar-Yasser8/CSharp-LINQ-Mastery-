# 🔗 CSharp-LINQ-Mastery Training

<div align="center">

[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![LINQ](https://img.shields.io/badge/LINQ-68217A?style=for-the-badge&logo=microsoft&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/)

**A comprehensive LINQ assignment exploring restriction, element, aggregate, ordering, and transformation operators in C#**

[📚 Topics](#-topics-covered) • [⚡ Quick Start](#-quick-start) • [🎯 Examples](#-operator-categories) • [👨‍💻 Author](#-author)

</div>

---

## 📖 Overview

This project demonstrates **mastery of LINQ (Language Integrated Query)** in C# through practical examples. It leverages a custom data generator (`ListGenerator.cs`) to provide data for the queries.

### ✨ Key Features

- 🎯 **Multiple Operator Types**: Restriction, Element, Aggregate, Ordering
- 🔄 **Dual Syntax**: Examples in both query syntax and method syntax
- 📊 **Real-World Scenarios**: Product inventories and numerical analysis

---

## 🧠 Topics Covered

### 🔹 LINQ - Restriction Operators

<table>
<tr>
<td width="50">1️⃣</td>
<td>Find all products that are <strong>out of stock</strong></td>
</tr>
<tr>
<td>2️⃣</td>
<td>Find all products that are <strong>in stock and cost more than $3.00 per unit</strong></td>
</tr>
<tr>
<td>3️⃣</td>
<td>Return digits whose <strong>name is shorter than their value</strong></td>
</tr>
</table>

---

### 🔹 LINQ - Element Operators

<table>
<tr>
<td width="50">1️⃣</td>
<td>Get the <strong>first product</strong> that is out of stock</td>
</tr>
<tr>
<td>2️⃣</td>
<td>Return the <strong>first product whose price > $1000</strong>, or <code>null</code> if none exists</td>
</tr>
<tr>
<td>3️⃣</td>
<td>Retrieve the <strong>second number greater than 5</strong> from an integer array</td>
</tr>
</table>

---

### 🔹 LINQ - Aggregate Operators

<table>
<tr>
<td width="50">1️⃣</td>
<td>Count how many numbers are <strong>odd</strong> in an integer array</td>
</tr>
<tr>
<td>2️⃣</td>
<td>List each <strong>customer</strong> and their total number of <strong>orders</strong></td>
</tr>
<tr>
<td>3️⃣</td>
<td>List each <strong>category</strong> and count <strong>products</strong> per category</td>
</tr>
<tr>
<td>4️⃣</td>
<td>Calculate the <strong>sum</strong> of all numbers in an array</td>
</tr>
</table>

---

### 🔹 LINQ - Ordering Operators

<table>
<tr>
<td width="50">1️⃣</td>
<td>Sort products by <strong>name</strong></td>
</tr>
<tr>
<td>2️⃣</td>
<td>Perform <strong>case-insensitive sorting</strong> on string arrays</td>
</tr>
</table>

---

## ⚡ Quick Start

### Prerequisites

- **.NET SDK** (6.0 or higher)
- **Visual Studio**, **Visual Studio Code**, or **JetBrains Rider**

### Installation

```bash
# Clone the repository
git clone https://github.com/Ammar-Yasser8/LINQ.git

# Navigate to project directory
cd LINQ

# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

### Running in Visual Studio

1. Open `LINQ.sln`
2. Set `Program.cs` as the startup file
3. Press `F5` (Debug) or `Ctrl + F5` (Run without debugging)

---

## 📁 Project Structure

```
LINQ/
│
├── Program.cs                  # Main entry point with all LINQ examples
├── ListGenerator.cs            # Data generator for products, customers, orders
└── README.md                   # This file
```

---

## 🎯 Learning Objectives

By exploring this project, you'll master:

- ✅ **Filtering data** with `Where` clauses
- ✅ **Selecting elements** with `First`, `FirstOrDefault`, `ElementAt`
- ✅ **Aggregating data** with `Count`, `Sum`, `Min`, `Max`, `Average`
- ✅ **Sorting collections** with `OrderBy`, `ThenBy`, and custom comparers
- ✅ **Converting between query syntax and method syntax**

---

## 📝 Notes

> 💡 **Dual Syntax Examples**  
> Most queries are demonstrated in both **query syntax** and **method syntax** for comparison

---

## 🤝 Contributing

This repository represents an active learning journey! Contributions are welcome:

- 🐛 **Report bugs** via [Issues](https://github.com/Ammar-Yasser8/LINQ/issues)
- 💡 **Suggest improvements** or additional LINQ examples
- 🔀 **Submit pull requests** with enhanced queries or refactorings
- ⭐ **Star the repo** if you find it helpful!

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

<div align="center">

### **Ammar Yasser**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ammar-yasser-a01772250/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ammar.yasser8920@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ammar-Yasser8)

*Passionate about C#, .NET, and clean code architecture*

</div>

---

<div align="center">

**Made with 💜 and LINQ**

⭐ **Star this repo** if it helped you learn LINQ!

</div>
