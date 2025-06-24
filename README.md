# 🧪 LPIC-1 Lab: Search Text Files Using Regular Expressions (Objective 103.7)

## ✅ What I did in this lab
I worked through a series of tasks that helped me build regex patterns, apply them to search inside text files, and use different tools to manipulate text. Each task focuses on real-world scenarios that a Linux admin might encounter.

## 1️⃣ Basic Pattern Matching with grep
🔹 Understand simple regex patterns and search for them in files

🔹 Create a test file:

🔹 Search for exact match "banana":

🔹 Search for lines starting with "c":

🔹 Search for lines ending in "t":

## 2️⃣ Using Character Classes and Special Characters
🔹 Learn how to use ranges, wildcards, and escaped characters

🔹 Match any word with vowels:

🔹 Match lines with any 6-character word:

🔹 Escape special characters:

## 3️⃣ Extended Regex with egrep (or grep -E)
🔹 Use alternation and grouping with extended regex

🔹 Match lines with either apple or banana:

🔹 Use parentheses and repetition:

## 4️⃣ Using fgrep for Fixed Strings
🔹 Search without interpreting regex symbols

🔹 Match literally "banana split" with fgrep:

🔹 Try the same with grep and see the difference when using special characters.

## 5️⃣ Text Substitution with sed
🔹 Replace, delete, or modify lines using sed with regex

🔹 Replace "banana" with "mango":

🔹 Remove lines that start with "c":

🔹 Replace all instances of vowels with "*":

## 6️⃣ Combining Regex with File Search
🔹 Search for matching content within files across directories

🔹 Create test files:

🔹 Use grep -r to search for "error":


## 🧠 What I learned
This lab helped me solidify the fundamentals of regular expressions in Linux. I learned the difference between basic and extended regex, and when to use tools like grep, egrep, or fgrep. I also practiced powerful substitution techniques with sed, which I can use to quickly process and transform text in real-world scenarios. 🚀
