# Data Structures and Algorithms Labs

รวมงานแลปที่ทำตอนเรียนวิชา **04-061-212 Data Structures and Algorithms Laboratory** เขียนด้วย C++ ตั้งแต่ linked list, stack และ binary search tree ไปจนถึง sorting และกราฟ

## งานในวิชานี้

| Lab | สิ่งที่ทำ |
|---|---|
| [Singly Linked List](singlyLinkList/main.cpp) | ฝึกจัดการข้อมูลด้วยลิงก์ลิสต์ทางเดียว |
| [Doubly Linked List](DoublyLinkedList/main.cpp) | ฝึกจัดการโหนดที่เชื่อมกันทั้งด้านหน้าและด้านหลัง |
| [Stack — Check Balance](CheckBalance2/main.cpp) | ใช้ stack ตรวจว่ามีวงเล็บเปิดและปิดครบคู่หรือไม่ |
| [Binary Search Tree](BinarySearchTree2/main.cpp) | ฝึกจัดเก็บและจัดการข้อมูลในต้นไม้ค้นหาแบบทวิภาค |
| [Sorting](Sort/main.cpp) | เปรียบเทียบเวลาของ Selection Sort กับ Insertion Sort โดยใช้ข้อมูลชุดเดียวกัน |
| [Graph — Minimum Spanning Tree](GraphMST/main.cpp) | หาต้นไม้แผ่ทั่วที่มีน้ำหนักรวมน้อยที่สุดในกราฟ |

## วิธีรัน

แต่ละโฟลเดอร์เป็นคนละโปรแกรม เปิด `main.cpp` ของ lab ที่ต้องการใน Code::Blocks แล้ว Build & Run ได้เลย

ถ้าใช้ g++ ให้เข้าโฟลเดอร์ของ lab นั้นก่อน เช่น:

```sh
cd GraphMST
g++ -std=c++11 main.cpp -o lab
./lab
```

บน Windows ใช้ `.\lab.exe` เพื่อเปิดโปรแกรมหลังคอมไพล์

## งานกลุ่ม

Lab Graph, Binary Search Tree และ Sorting ทำร่วมกันโดย:

- Phuriphat Malison
- Nawadon Srikhao
- Chotiphat Suwannawong
