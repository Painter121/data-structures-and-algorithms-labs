# Data Structures and Algorithms Labs

คัด lab ที่มี implementation: GraphMST, DoublyLinkedList, CheckBalance2, BinarySearchTree2, singlyLinkList และ Sort
แสดงการฝึกกราฟ, linked list, stack, tree และ sorting; เก็บโค้ดเดิม ไม่เปลี่ยนเป็น implementation ใหม่

GraphMST มีหัวไฟล์ระบุรายวิชา **04-061-212 Data Structures and Algorithms Laboratory**
และผู้จัดทำร่วมสามคน รวม Phuriphat Malison จึงเป็นงานกลุ่มและคงเครดิตเดิมไว้
บางไฟล์อื่นไม่ระบุผู้เขียน จัดเป็นงานที่พบในคลังเรียน ไม่อ้างว่าทั้งหมดสร้างคนเดียว

เปิดแต่ละ main.cpp เป็นโปรแกรมแยก ใช้ Code::Blocks หรือ g++:

```sh
g++ -std=c++11 main.cpp -o lab
./lab
```

ยังไม่ได้ compile ใหม่เพราะไม่พบ g++ ใน PATH บางไฟล์ใช้ encoding ภาษาไทยเดิม
โค้ดเป็นงานเรียน อาจมีข้อจำกัดเรื่อง input และ edge cases


Repository แยกตามวิชา/หัวข้องานเรียน คงโค้ดและเครดิตเดิมไว้ ดูที่มาไฟล์ใน [provenance.json](provenance.json)

## เปิดแต่ละ lab

- [Graph — Minimum Spanning Tree](GraphMST/main.cpp)
- [Doubly Linked List](DoublyLinkedList/main.cpp)
- [Stack — Balanced Parentheses](CheckBalance2/main.cpp)
- [Binary Search Tree](BinarySearchTree2/main.cpp)
- [Singly Linked List](singlyLinkList/main.cpp)
- [Sorting](Sort/main.cpp)
