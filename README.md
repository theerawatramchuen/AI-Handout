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

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/How%20do%20Neural%20Networks%20Learn%2011.jpg)

# Gradient Descent
คือวิธีที่หาค่า weight ที่ให้ค่า C น้อยที่สุด และนั่นคือจุดที่ Neurual Network ให้ค่าได้ใกล้เคียงกับข้อมูที่ใช้ train 
![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Gradient%20Descent%2001.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Gradient%20Descent%2004.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Gradient%20Descent%2002.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Gradient%20Descent%2003.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Gradient%20Descent%2005.jpg)

# Guild to Convolutional Neural Network (CNN)
![alt text](https://www.superdatascience.com/blogs/the-ultimate-guide-to-convolutional-neural-networks-cnn)
# Stochastic Gradient Descent
ในกรณีที่ cost function ของชุดข้อมูลที่จะใช้สอน Neurual Network ไม่ได้เป็นผลต่างกำลังสอง ซึ่งมักจะพบกับข้อมูลที่มีความซับซ้อนในความสัมพันธ์กับข้อมูลขาออก y

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Stochastic%20Gradient%20Descent%2001.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Stochastic%20Gradient%20Descent%2002.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Stochastic%20Gradient%20Descent%2003.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Stochastic%20Gradient%20Descent%2004.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Stochastic%20Gradient%20Descent%2005.jpg)

# Backpropagation
![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Backpropagation%2001.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Backpropagation%2002.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/Backpropagation%2003.jpg)

# Guild to Convolutional Neural Networks (CNN)
https://www.superdatascience.com/blogs/the-ultimate-guide-to-convolutional-neural-networks-cnn

# Plan of Attack
![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2001.jpg)

# What are convolution neural network?
Convolutional Neural Network (CNN) หรือ โครงข่ายประสาทแบบคอนโวลูชัน เป็นโครงข่ายประสาทเทียมหนึ่งในกลุ่ม bio-inspired โดยที่ CNN จะจำลองการมองเห็นของมนุษย์ที่มองพื้นที่เป็นที่ย่อยๆ และนำกลุ่มของพื้นที่ย่อยๆมาผสานกัน เพื่อดูว่าสิ่งที่เห็นอยู่เป็นอะไรกันแน่

การมองพื้นที่ย่อยของมนุษย์จะมีการแยกคุณลักษณะ (feature) ของพื้นที่
ย่อยนั้น เช่น ลายเส้น และการตัดกันของสี ซึ่งการที่มนุษย์รู้ว่าพื้นที่ตรงนี้เป็นเส้นตรงหรือสีตัดกัน เพราะมนุษย์ดูทั้งจุดที่สนใจและบริเวณรอบ ๆ ประกอบกัน

![alt text](https://cdn-images-1.medium.com/max/1600/1*9HPPZjXOem6afR9iSZgVcA.png)

ถ้าเราเปรียบว่ากรอบสีเหลี่ยมสีเหลืองนั้น คือพื้นที่ที่มนุษย์กำลังให้ความสนใจอยู่ แต่เราสามารถรับรู้ได้ว่าสิ่งนี้คือหนู เพราะเรากวาดสายตามองรอบๆ

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2002.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2003.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2004.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2005.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2006.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2007.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2008.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2009.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2010.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2011.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2012.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2013.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2014.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2015.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2016.jpg)

![alt text](https://github.com/theerawatramchuen/AI-Handout/blob/master/Slides/CNN%2017.jpg)

Feature Extraction
แนวคิดของ CNN นั้นค่อนข้างเป็นแนวคิดที่ดีมาก แต่สิ่งที่ซับซ้อนของมันคือระบบการคำนวณที่สอดคล้องกับ Concept ของมันเองและต้องมีคณิตศาสตร์มารองรับ โดยการคำนวณตามแนวคิดนี้ใช้หลักการเดียวกันกับ คอนโวลูชันเชิงพื้นที่ (Spatial Convolution) ในการทำงานด้าน Image Processing
การคำนวณนี้จะเริ่มจากการกำหนดค่าใน ตัวกรอง (filter) หรือ เคอร์เนล
(kernel) ในที่นี้เค้าเรียก Feature Detector ที่ช่วยดึงคุณลักษณะที่ใช้ในการรู้จำวัตถุออก โดยปกติตัวกรอง/เคอร์เนลอันหนึ่งจะดึงคุณลักษณะที่สนใจออกมาได้หนึ่งอย่าง เราจึงจำเป็นต้องตัวกรองหลายตัวกรองด้วย เพื่อหาคุณลักษณะทางพื้นที่หลายอย่างประกอบกัน
