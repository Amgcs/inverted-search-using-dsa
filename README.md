# inverted-search-using-dsa
A File-Based Inverted Search Engine implemented in C using Data Structures. This project builds an inverted index from multiple text files and enables efficient word searching with file occurrence tracking.

# 🔎 Inverted Search Engine in C

## 📌 Project Overview

This project implements an **Inverted Search (Inverted Index) Engine** using the C programming language.  
It indexes multiple text files and allows fast searching of words across those files.

Instead of scanning every file repeatedly, the system creates an **inverted index** that maps:

Word → List of files → Word count in each file

This technique is widely used in **search engines**.

---

## 🚀 Features

- 📂 Index multiple text files
- 🔤 Create an inverted index
- 🔍 Search any word instantly
- 📊 Display word occurrence count per file
- 🗂 Store and update database
- ❌ Handle duplicate files
- ⚙ Efficient linked list implementation

---

## 🛠 Technologies Used

- C Programming
- Data Structures
  - Singly Linked List
  - Hashing
- File Handling
- Dynamic Memory Allocation
- Linux System Programming

---

## 🧠 Concept Used: Inverted Index

### What is Inverted Search?

Inverted Search stores data in this format:

```
Word
 ├── File1 → Count
 ├── File2 → Count
 └── File3 → Count
```

Instead of:

```
File1 → Words
File2 → Words
```

This improves search performance significantly.

---

## 🏗 Project Structure

```
.
├── main.c
├── inverted_search.h
├── create_database.c
├── search_database.c
├── insert_at_first.c
├── update_database.c
└── files.txt
```

---

## ⚙ How It Works

1. Read file names from command line
2. Validate files
3. Create hash table
4. Parse words from files
5. Insert into database
6. Allow user to search words
7. Display results

---

## ▶ How to Compile

```bash
make

```

## ▶ How to Run

```bash
./inverted.out file1.txt file2.txt file3.txt
```

---

## 📸 Sample Output

```
Enter the word to search: data

Word found!

File: file1.txt → 3 times
File: file2.txt → 1 time
```

---

## 🎯 Applications

- Search Engines
- Document Indexing Systems
- Log File Analysis
- Digital Libraries
- Data Retrieval Systems

---

## 📚 Learning Outcome

Through this project, I learned:

- Efficient data organization
- File handling in C
- Dynamic memory management
- Hash table implementation
- Linked list manipulation
- Real-world search engine working principle

---

## 📌 Conclusion

This project demonstrates how search engines internally organize and retrieve data efficiently using an inverted indexing mechanism.
