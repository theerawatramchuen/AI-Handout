# AI-Handout
# What is Deep learning?
ทุกคนยอมรับนะครับว่า มนุษย์ครองโลกใบนี้เพราะ สมองมนุษย์มีความสามารถในการเรียนรู้  จึงมีแนวคิดว่าถ้าจะทำให้คอมฯมีความสามารถนี้ได้ก็ต้องต้องสร้างสมองเทียมเลียนแบบสมองมนุษย์

เรามีอินพุทสีเหลืองจะกี่อินพุทก็แล้วแต่ ที่เราคาดว่ามันมีอิทธืพลต่อ เอาท์พุนสีแดง ตัวอย่างข้อมูลของลูกค้าธนาคาร เครดิต เงินฝากในบญชี เพศ เงินเข้าออกบัญชี ยอดหนี้ และอื่นๆ  ซึ่งจะเป็นอินพุท  ส่วนเอาท์พุทก็อยากจะรู้ว่าลูกค้าคนนี้จะอยู่เป็นลูกค้าธนาคารต่อไปหรือไม่ สีเขียวที่ถูกเรียกว่า hidden layer เป็นส่วนที่นำข้อมูลทางอินพุทมาประมวลผลเพื่อพยากรณ์ว่าเอาท์พุทควรเป็นอย่างไร 

ที่ถูกเรียกว่า deep learning เพราะว่ามันจะถูกจับตั้ง ชั้นบนสุดจะเป็นอินพุท ส่วนเอาท์พุทจะอยู่ด้านล่าง

# Plan of Attack
ให้มองเห็นการทำงานของ Neural Network ก่อน ซึ่งจะทำให้เข้าใจได้ดีกว่าที่จะ ไปเริ่มที่ขบวนการเรียนรู้ของ Neural Network 

# The Neuron
Dendrites  ตัวรับ  
Axon  ตัวส่ง
Neuron โนด
database 1 record
excel 1 row
 input value need Normalization
Output เป็นราคา คะแนนสอบ เปอร์เซนต์ของเสีย เป็นใข่หรือไม่ไช่ หรือจัดอยู่ในกลุ่มไหน
Weight  เป็นส่วนที่สำคัญมี่ทำให้ Neuton เรียนรู้และนำไปปรับใช้ให้เกิด output ด้วย activation function
# The Activation Function
![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/The%20Activation%20Function.jpg)
รูปแบบเอาท์พุท y ที่แปรผันตามค่า Sum of Product แกน x 
ความน่าจะเป็น sigmoid 
Rectifyให้ค่า 0 เมื่อ Sum of Product ได้ค่าติดลบ

# How do Neural Networks work?
ตัวอย่างที่ยกมาเป็นการ neural Network ที่ถูกเทรนมาแล้วเพื่อให้เสนอราคาบ้านที่เหมาะสมจากข้อมูลของบ้าน
![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/The%20Activation%20Function%20House%20Price.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20work%2001.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20work%2002.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20work%2003.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20work%2004.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20work%2005.jpg)

# How do Neural Networks Learn?
การให้คอมฯประมวลผลจากข้อมูลเข้าแล้วส่งข้อมูลออกให้เรามีสองรูปแบบวิธี หนึ่งคือเราสร้างโปรแกรมโดยเตรียมเงื่อนไขกฏเกณฑ์ทุกอย่างรวมถึงความสัมพันธ์ของข้อมูลเข้าและออก สองสร้าง Nerual Network
![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2001.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2002.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2003.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2004.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2005.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2006.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2007.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2008.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2009.jpg)
