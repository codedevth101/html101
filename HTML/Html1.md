# สัดส่วนในภาษา HTML

ในภาษานี้เราจะเเบ่งสัดส่วนใหญ่ๆออกเป็น 2 ส่วน เเละ สัดส่วนย่อยออกเป็น อีก 2 ส่วน
โดยเราจะเรียกว่า TAG เช่น `<head></head>` เรียกว่า tag head ซึ่งในตัวเเท็กด้านหลัง </head> จะต้องมี / เสมอ

## สัดส่วนใหญ่ๆ

### ส่วน head
สิ่งที่จะใส่ใน tag head จะเป็นส่วนที่จะไม่ปรากฎบนหน้าเว็บไซต์
``` html
<!--Head เป็นส่วนที่จำเป็นต้องมีในการเขียน HTML-->
<head>

</head>
```
### ส่วน body
สิ่งที่จะใส่ใน tag body จะปรากฎบนหน้าเว็บไซต์
``` html
<!--Body เป็นส่วนที่จำเป็นต้องมีในการเขียน HTML-->
<body>

</body>
```
## สัดส่วนย่อยๆ

### ส่วน style
ใน tag style จะเอาไว้เขียนภาษา CSS โดยจะนำเเท็กนี้ไปไว้ใน tag head
``` html
<head>
    <style>
    
    </style>
</head>
```
### ส่วน script
ใน tag script จะเอาไว้เขียนภาษา Javascript โดยจะนำเเท็กนี้ไปไว้ใน tag head หรือ tag body ก็ได้

- head
``` html
<head>
    <script>
    
    </script>
</head>
```

- body
``` html
<body>
    <script>
    
    </script>
</body>
```

[<< ย้อนกลับ](https://github.com/codedevth101/html101/blob/main/HTML/intro.md) | [รู้จัก tag ใน HTML >>](https://github.com/codedevth101/html101/blob/main/HTML/Html2.md)
