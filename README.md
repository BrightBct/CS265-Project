# CS265-Project

## สารบัญ

- [รายละเอียด project](#รายละเอียด-project)
- [ขั้นตอนการติดตั้ง](#ขั้นตอนการติดตั้ง)
  - [library](#library)
- [ขั้นตอนการใช้งาน](#ขั้นตอนการใช้งาน)
- [ผลลัพธ์การทำงาน](#ผลลัพธ์การทำงาน)
- [อ้างอิง](#อ้างอิง)
- [ชื่อผู้พัฒนา](#ชื่อผู้พัฒนา)

## รายละเอียด Project

CS265 AI Python Project

วิชา CS265 Artificial Intelligence Fundamentals ปัญญาประดิษฐ์เบื้องต้น

วิชาบังคับปี 2 เทอม 2 มหาวิทยาลัยธรรมศาสตร์ รังสิต สาขาวิทยาการคอมพิวเตอร์ ภาคพิเศษ

โดยเนื้อหา Project คือ การทำผู้ช่วยเสมือน Ramen เพื่อใช้ในการสนับสนุนหรือพัฒนานักเรียนหรือนักศึกษาที่ต้องการศึกษาหาความรู้ด้วยตนเองและต้องการพัฒนาความสามารถของตนเอง โดยสิ่งที่ Ramen สามารถทำได้ในตอนนี้คือการทำสรุปข้อความจากรูปภาพและจาก url ใน Wikipedia และสามารถฝึกคำศัพท์ภาษาอังกฤษให้แก่ผู้ใช้งาน และสามารถค้นหาความหมายของคำศัพท์ที่ผู้ใช้งานค้นหามาได้ 

ในภายหลัง คาดว่าจะพัฒนาให้ Ramen มีความสามารถในการพัฒนาหรือสนับสนุนผู้ใช้งานมากกว่านี้ และทำให้ตัวระบบมีความเสถียรมากกว่านี้ โดยขั้นตอนสุดท้ายหวังว่าจะสามารถทำเป็นโปรแกรมติดในเครื่อง เช่น Cortana Siri Alexa เป็นต้น

## ขั้นตอนการติดตั้ง

จะใช้ python version 3.8

ใช้คำสั่ง `$ git clone https://github.com/BrightBct/CS265-Project.git` ในการนำ project ไปติดตั้ง

### library

จะทำการติดตั้ง library ต่าง ๆ ด้วย [`pip`](https://pypi.org/project/stronghold/)

โดย library ที่ใช้มีดังนี้:

    1.speech_recognition
    2.pyttsx3
    3.wikipedia
    4.torch
    5.pyjokes
    6.nltk
    7.contractions
    8.re
    9.bs4
    10.numpy
    11.pandas
    12.heapq
    13.pytesseract

โดยจะใช้ไฟล์ `requirements.txt` ในการติดตั้ง library 

ด้วยการใช้คำสั่ง `$ pip install -r requirements.txt` ในการติดตั้ง

## ขั้นตอนการใช้งาน

ถ้าใช้ pycharm หรือ vscode สามารถใช้คำสั่ง run ที่มีมาให้ได้เลย

หรือถ้าใช้ cmd จะใช้คำสั่ง `$ main.py` ในการทำงาน

## ผลลัพธ์การทำงาน

ฟังก์ชันของ Ramen เนื่องจากเป็นผู้ช่วยเสมือนจะมีฟังก์ชันหลายอย่าง แต่จะมีฟังก์ชันที่หลัก ๆ ทั้งหมด 3 อย่าง ได้แก่
  - 1.การสรุปข้อความ
  - 2.การฝึกพูดคำศัพท์ภาษาอังกฤษ
  - 3.การค้นหาความหมายของคำศัพท์

## อ้างอิง

เนื้อหาโค้ดหลายอย่างสามารถศึกษาได้จาก 

    https://github.com/mmirthula02/AI-Personal-Voice-assistant-using-Python.git

## ชื่อผู้พัฒนา

6209650081 นายภีมภัช พจน์สุนทร (หัวหน้ากลุ่ม)<br/>
6209650149 นางสาวนวพร วิริยะภาพ (รองหัวหน้ากลุ่ม)<br/>
6209650297 นางสาวสมิตา ขวัญสุวรรณ (สมาชิกกลุ่ม)<br/>
6209650370 นายศุภวิชญ์ อิทธิศิริเวทย์ (สมาชิกกลุ่ม)<br/>
6209650586 นายพีรวิชญ์ บุตรสา (สมาชิกกลุ่ม)<br/>
6209650636 นางสาวณัชธิชา ฐิติธนานนท์ (สมาชิกกลุ่ม)
