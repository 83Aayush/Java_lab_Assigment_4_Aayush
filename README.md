# 📘 Student Record Management System  

This project implements a **Student Record Management System** using:

- File Handling (BufferedReader, BufferedWriter)
- Java Collections (ArrayList)
- Sorting using Comparator
- Display using Iterator
- Persistent storage using students.txt
- RandomAccessFile for random access reading

---

## 🎯 Objective
- Use file handling for reading/writing student data  
- Store and manage records using collections  
- Implement sorting, searching, deleting  
- Display data using Iterator  
- Demonstrate RandomAccessFile  

---

## 🧩 Class Structure

| Class | Description |
|-------|-------------|
| Student | Model class for student data |
| FileUtil | Reads/writes student data from/to file |
| StudentManager | CRUD operations + sorting + iterator |
| Main | Menu-driven application |

---

## 📁 File Format (students.txt)
Each line in the file must follow:

```
roll,name,email,course,marks
```

Example:
```
101,Ankit,ankit@mail.com,B.Tech,85.5
102,Riya,riya@mail.com,M.Tech,91.0
```

---

## 🖥️ Expected Output
```
Loaded students from file:
Roll No: 101
Name: Ankit
Email: ankit@mail.com
Course: B.Tech
Marks: 85.5
Roll No: 102
Name: Riya
Email: riya@mail.com
Course: M.Tech
Marks: 91.0
===== Capstone Student Menu =====
1. Add Student
2. View All Students
3. Search by Name
4. Delete by Name
5. Sort by Marks
6. Save and Exit
Enter choice: 1
Enter Roll No: 103
Enter Name: Karan
Enter Email: karan@mail.com
Enter Course: BCA
Enter Marks: 76.2
Sorted Student List by Marks:
Roll No: 102
Name: Riya
Email: riya@mail.com
Course: M.Tech
Marks: 91.0
```

        while
