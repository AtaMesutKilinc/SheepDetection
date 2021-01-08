# Using Python YoloV3-608 Algorithm and Opencv Library for Sheep Detection and Printing on the Interface Designed in Qt Designer
80 objects can be detected with Opencv library and YoloV3-608 Real Time Object Detection Algorithm. I detected sheep / sheeps by pulled only the sheep label from the detected objects with the if loop. The global 'koyun' variable defined with count sheep detected in printed to console.
In the Qt Designer program, I designed an interface that displays the state of the object before it was detected, the state after it was detected, and the number of objects detected in the photo. I converted my design into python codes and integrated it into the code.

# Sample Interface Photo / Örnek Arayüz Fotoğrafı
![alt text](https://github.com/AtaMesutKilinc/SheepDetection/blob/main/sample%20interface.jpg?raw=true)

# Python YoloV3-608 Algoritması ve Opencv Kütüphanesi Kullanarak Koyun Tespiti Yapmak Qt Designer'da Tasarlanan Bir Arayüzde Yazdırmak
Opencv ve YoloV3-608 gerçek zamanlı nesne tespiti algoritması ile 80 adet nesne tespiti yapılabilmektedir. Tespit edilen nesnelerden sadece koyun etikeni if döngüsü ile çekerek  tespit ettim. Tanımladığım global koyun değişkeni ile tespit edilen koyun sayısını consol'a yazdırdım. 
Qt Designer programında, nesnenin tespit edilmeden önceki halini, tespit edildikten sonraki halini ve fotoğrafta kaç tane nesne tespit edildiğinin sayısını gösteren bir arayüz tasarladım.Tasarımımı python kodlarına dönüştürerek kodlara entegre ettim.


Coco names file: https://github.com/pjreddie/darknet/blob/master/data/coco.names

# YOLO: Real-Time Object Detection and YoloV3-608 Weights file : https://pjreddie.com/darknet/yolo/  



  
