# 🧪 103.7 Search Text Files Using Regular Expressions 

## ✅ What I did in this lab
I worked through a series of tasks that helped me build regex patterns, apply them to search inside text files, and use different tools to manipulate text. Each task focuses on real-world scenarios that a Linux admin might encounter.

I’ve included some helpful links to guide you through the lab and for studying afterward:

[103.7 EXAM OBJECTIVE](https://www.lpi.org/our-certifications/exam-101-102-objectives/#103.7_Search_text_files_using_regular_expressions)

[OBJ.103.7 NOTES]()

[OBJ. 103.7 LAB]()

---

## 1️⃣ Basic Pattern Matching with grep
🔹 Understand simple regex patterns and search for them in files

🔹 Create a test file:

![dsF6U9c](https://github.com/user-attachments/assets/cf595f78-b599-4b8b-9882-146ae2796540)

🔹 Search for exact match "banana":

![drpjdfD](https://github.com/user-attachments/assets/3259d242-e1e6-44bc-b2d6-84eebd05e1fb)

🔹 Search for lines starting with "c":

![E0Rvjty](https://github.com/user-attachments/assets/46dbece5-ba37-441b-a052-b6ae771619e0)

🔹 Search for lines ending in "t":

![uYpH3PH](https://github.com/user-attachments/assets/754cba57-5386-4bde-9656-fb85fd45593a)


## 2️⃣ Using Character Classes and Special Characters
🔹 Learn how to use ranges, wildcards, and escaped characters

🔹 Match any word with vowels:

![InclWef](https://github.com/user-attachments/assets/0714c311-6662-4b1a-9d2b-58a04983eb28)

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
