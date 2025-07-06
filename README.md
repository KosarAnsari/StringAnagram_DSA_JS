# 🧠 Day 3 – String Anagram Problem

## 📌 Challenge:
Check whether two given strings are **anagrams** of each other.

> Two strings are anagrams if they contain the same characters in the same frequency, just rearranged.

---

## 🔍 Problem Statement

Write a function `isAnagram(string1, string2)` that returns `true` if the two input strings are anagrams, and `false` otherwise.

---

## ✅ Approach:

1. First, check if both strings have the same length. If not, return false immediately.
2. Create a frequency counter (object) to count how many times each character appears in the first string.
3. Loop through the second string and decrease the count for each character.
4. If a character is not found or its count becomes zero before processing all characters, return `false`.
5. If the loop completes without issues, return `true`.

---
🧠 Key Concepts Used:

Hashmaps / Frequency counters

String traversal using for...of loops

Basic conditional logic



---

⏱ Time & Space Complexity:

Time Complexity: O(n)

Space Complexity: O(n)



---

📅 Progress:

Day 3 of 21 in my 21-Day JavaScript DSA Challenge!


---

🚀 Let's Connect:

If you're also doing a similar challenge, feel free to connect and share your journey!


---

🔗 Tags:

#21DaysOfDSA #JavaScript #CodingChallenge #AnagramProblem #DeveloperJourney #100DaysOfCode

