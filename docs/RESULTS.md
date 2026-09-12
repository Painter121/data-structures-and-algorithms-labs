# Experiment Results

ผลในเอกสารนี้ได้จากการ compile source code ใน repository แล้วรันบน Windows ด้วย **MinGW g++ 14.2.0** เมื่อวันที่ 12 กันยายน 2026

## Sorting benchmark

คำสั่งที่ใช้:

```sh
g++ -std=c++11 -O2 -Wall -Wextra -pedantic Sort/main.cpp -o sort_lab
sort_lab 1000
sort_lab 5000
sort_lab 10000
```

แต่ละขนาดรัน 3 ครั้ง ตารางแสดงค่าเฉลี่ย โปรแกรมตรวจซ้ำหลังจบว่า array ทั้งสองเรียงจากมากไปน้อยถูกต้อง

| Data size | Selection Sort | Insertion Sort |
|---:|---:|---:|
| 1,000 | 1 ms | < 1 ms |
| 5,000 | 24 ms | 1 ms |
| 10,000 | 97 ms | 3 ms |

ข้อมูลทดลองครึ่งแรกเรียงจากมากไปน้อยอยู่แล้ว ส่วนครึ่งหลังเป็นเลขสุ่ม และทั้งสองอัลกอริทึมได้รับสำเนาของข้อมูลชุดเดียวกัน ผลนี้ใช้เปรียบเทียบแนวโน้มบน workload นี้เท่านั้น ไม่ควรใช้เป็น benchmark ข้ามเครื่อง

## Binary Search Tree traversal

ชุดคำสั่ง:

```text
1 8
1 3
1 10
1 1
1 6
1 14
1 4
1 7
1 13
6
4
5
7
```

ผลลัพธ์:

```text
8 3 1 6 4 7 10 14 13
1 3 4 6 7 8 10 13 14
1 4 7 6 3 13 14 10 8
9
Min = 1 and Max = 14
```

สามบรรทัดแรกคือ Preorder, Inorder และ Postorder ตามลำดับ

## Prim's minimum spanning tree

Input:

```text
5 7
0 1 2
0 3 6
1 2 3
1 3 8
1 4 5
2 4 7
3 4 9
0
```

Output:

```text
0 -> 1
1 -> 2
1 -> 4
0 -> 3
16
```

MST ของกราฟที่เชื่อมต่อกัน 5 vertices ต้องมี 4 edges พอดี และตัวอย่างนี้มีน้ำหนักรวม `2 + 3 + 5 + 6 = 16`

## Parentheses checker

Input:

```text
{a+[b*(c-d)]}
```

Output:

```text
Correct
```
