# Allow List Update Automation in Python

## 🔍 What is this?
This project is a Python script I built as part of my cybersecurity training. The goal was to automate a common administrative task: updating an IP allow list (`allow_list.txt`) by automatically removing addresses found on a separate removal list. 

## 🛠️ Concepts & Skills Used
- **File Handling:** Opening, reading, and writing files using Python's `with` statement safely.
- **Data Manipulation:** Converting strings to lists using `.split()` and rejoining them using `.join()`.
- **Automation Logic:** Using `for` loops and `if` conditions to filter out unauthorized IP addresses.

## 📋 How I Built the Script
1. **Reading the File:** Opened the allow list file in read mode (`"r"`) and stored the contents as a string.
2. **Converting to a List:** Used `.split()` to transform the string of IP addresses into a list so it's easier to modify item by item.
3. **Filtering and Removing:** Created a loop to go through the removal list and safely drop any matching IP address from our allow list.
4. **Saving Changes:** Converted the updated list back into a string (putting each IP on a new line with `\n`) and overwrote the file using write mode (`"w"`).

## 🚀 What I Learned
Working on this script helped me practice core Python concepts applied directly to IT and security scenarios, making it much easier to understand how automation reduces manual errors.

---
*Part of Romina's Cybersecurity & IT Portfolio.*
