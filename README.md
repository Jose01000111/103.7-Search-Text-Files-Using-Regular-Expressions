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

![i5jmQrR](https://github.com/user-attachments/assets/cbbad6c4-5e55-4ac7-a5f3-0b63a371648a)

🔹 Escape special characters:

![83naCaR](https://github.com/user-attachments/assets/49692345-ea6e-44dd-aa0b-5fef0df504d9)

## 3️⃣Using fgrep for Fixed Strings
🔹 Search without interpreting regex symbols

🔹 Match literally "banana split" with fgrep:

🔹 Try the same with grep and see the difference when using special characters.

![ctXF6Aa](https://github.com/user-attachments/assets/7dbaa6c6-bf42-4668-b31e-01044c82386f)

## 4️⃣ Text Substitution with sed
🔹 Replace, delete, or modify lines using sed with regex

🔹 Replace "banana" with "mango":

![oZh8nMQ](https://github.com/user-attachments/assets/7bfdcefd-ad25-4db9-9b62-5c7b073cd21e)

🔹 Remove lines that start with "c":

![ttJctJj](https://github.com/user-attachments/assets/3a480f60-2c98-40a9-8548-b205ae75a878)

🔹 Replace all instances of vowels with "*":

![RS4SbKj](https://github.com/user-attachments/assets/943d9a68-b7ba-45f9-836a-bf39afd31cce)

## 5️⃣ Combining Regex with File Search
🔹 Search for matching content within files across directories

🔹 Create test files:

![VADERuv](https://github.com/user-attachments/assets/5cdf033e-8312-4066-b906-14dff2fbaea1)

🔹 Use grep -r to search for "error":

![lDcwgRy](https://github.com/user-attachments/assets/1152a5f0-397d-464b-aab4-ea7c9a946514)

## 🧠 What I learned
This lab helped me solidify the fundamentals of regular expressions in Linux. I learned the difference between basic and extended regex, and when to use tools like grep, egrep, or fgrep. I also practiced powerful substitution techniques with sed, which I can use to quickly process and transform text in real-world scenarios. 🚀
