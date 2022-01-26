# test3
# Git-test
## Reprository
>**_เป็น folder ไว้ใช้เก็บงาน สามารถสร้าง branch หรือ folder ย่อย เพื่อแยกไปเขียน code ได้_**
>> - สร้าง markdown ใส่ใน folder ได้ โดยที่การเขียน markdown มีหลายรูปแบบไ เช่น
>>>   * ตัวหนา ใช้  ** content **, __ content __
>>>   * ตัวเอียง ใช้ * content *, _ content _
>>>   * ตัวหนา + ตัวเอียง ใช้ *** content ***, __* content *__
>>>   * ตีเส้นคั่น ใช้ ***, ---, ______
>>>   * ใส่รูป ใช้  ![detail](url)
>>>   * ใส่ link ในข้อความ [content](url)  
เป็นต้น
***


* Lab Branch *
- สร้าง branch  ใหม่ด้วย git branch
- checkout ไป branch ใหม่
- สร้าง ไฟล์ .txt
- แก้ไข ไฟล์ .txt
- upload file ขึ้น branch ใหม่
- สลับกลับมา master
- ดูการเปลี่ยนแปลงที่เกิดขึ้น
- ลบ branch ด้วย git branch -d branch_name
- ลอง ใช้คำสั่ง git checkout -b branch_name
- สร้างไฟล์ .txt upload
- สลับมา master
- ดูการเปลี่ยนแปลง


* Lab Merge *

กรณีมี conflict
- แก้ไข file .txt ใน master
- push ขึ้น repo
- สลับไป branch ที่สร้างเมื่อกี้
- แก้ไข file.txt ให้ไม่เหมือนใน master
- push ขึ้น repo
- ทำการ merge เข้ากับ master

กรณี ไม่มี conflict
- สลับมา branch ใหม่
- แก้ไขไฟล์ .txt
- push ขึ้น repo
- ทำการ merge เข้ากับ master อีกรอบ

กรณีมี การเพิ่ม comment
- สลับมา branch ใหม่
- แก้ไขไฟล์ .txt แบบ comment
- push ขึ้น repo
- ทำการ merge เข้ากับ master อีกรอบ

 
* Lab Rebase *

กรณีมี conflict 
- สร้าง branch ใหม่
- แก้ไข file .txt ใน master
- push ขึ้น repo
- สลับไป branch ที่สร้างเมื่อกี้
- แก้ไข file.txt ให้ไม่เหมือนใน master
- push ขึ้น repo
- ทำการ rebase เข้ากับ master

กรณี ไม่มี conflict
- สลับมา branch ใหม่
- แก้ไขไฟล์ .txt
- push ขึ้น repo
- ทำการ rebase เข้ากับ master อีกรอบ

* Lab Ignore *
- ลอง สร้างไฟล์ .html, .css, .js 
push repo

- ignore ไฟล์ .html
git rm --cached file_name
push repo

- edit ignore ไฟล์ .css
push repo
git rm --chached file_name
push repo

- ลอง สร้าง folder node_module
- ignore folder ที่สร้าง

- edit ignore ไฟล์ .js
push repo
git rm --cached file_name
push repo 


