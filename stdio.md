### การใช้ standrad Input/ Output
# C language
- `string` ในที่นี้หมายถึง `char[]` arrayทั้งหมดของ char 
- ต้องมีการ `#include <stdio.h>` ทุกครั้งการจะใช้ฟังชั่น input output

printf()

- ใช้ในรูปแบบ `printf("ข้อความๆๆๆๆ",arg1,arg2,.....);` 
- สามารถนำ arg1, arg2  มาอทยที่ใสข้อความด้วยการใช้สิ่งที่เรียกว่า **format specifiers**
  - `%d` ใช้กับ `int`
  - `%f` ใช้กับ `float` (สามารถกำหนดจำนวนทศนิยมที่จะแสดงได้ด้วยการเขียน `"%.nf"` เมื่อ n คือจำนวนทศนิยมที่ต้องการให้แสดง)
     เช่น `%.2f` จะได้ผลลัพธ์ `x.xx`
  - `%c` ใช้กับ `char`
  - `%s` ใช้กับ string(`char[]`)

ตัวอย่างเช่น

```
int x = 5;
float y = 1;
char z = 'z';
printf("")
```
