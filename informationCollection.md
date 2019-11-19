# Resources might be used  

---

## Online resource

### Similar Projects
1. [Arduino Based Digital SAFE BOX](https://www.instructables.com/id/Arduino-Based-Digital-SAFE-BOX/) [video in Youtube](https://www.youtube.com/watch?v=u1Uiw4OZtvc)  
1. [How to Make Fingerprint Door Lock | Arduino Project](https://www.youtube.com/watch?v=gpXuEghz1zc) ** No source  
2. [An example using Servo Motor](https://www.geek-workshop.com/thread-1492-1-1.html) ** Need translation  
3. [Secret Knock Detecting Door Lock](https://www.instructables.com/id/Secret-Knock-Detecting-Door-Lock/)  
4. [My-O-Lock](https://github.com/davidxvuong/My-O-Lock) ** Python needed  
5. [Secure Lock With Arduino](https://www.instructables.com/id/Bike-Lock-With-Arduino/) ** More materials needed  

### Related topics

1.[Digital Combination Lock!](https://www.instructables.com/id/Digital-Combination-Lock/)  

### Related tutorials

1. [How Rotary Encoder Works and How To Use It with Arduino](https://howtomechatronics.com/tutorials/arduino/rotary-encoder-works-use-arduino/)  
2. [Workshops information at FabLab](https://www.fablabenschede.nl/workshops/)  
3. [2019 Best Free 3D Printing Software (Fall Update)](https://all3dp.com/1/best-free-3d-printing-software-3d-printer-program/)  

---

## Codes

### For input  

#### 1. Get input
> //TODO



## For main functions  

#### 1. check password  

``` 
void checkPassword(){

if (password.evaluate()){  
   
    Serial.println("Accepted");//open when password correct
    Serial.print(254, BYTE);delay(10);
    
    //following line are for debuging
    myservo.write(5); //160°
   
    digitalWrite(11, HIGH);//open
    delay(500); //wait for 5 seconds
    digitalWrite(11, LOW);// close
   
   
}else{
    Serial.println("Denied"); //keeping lock when password wrong
    Serial.print(254, BYTE);delay(10);
    
    //following line are for debuging
    myservo.write(0);

    digitalWrite(12, HIGH); //open
    delay(500); //wait for 5 seconds
    digitalWrite(12, LOW);//close
   
}
}
``` 
[Resources from](https://www.geek-workshop.com/thread-1492-1-1.html)  

---

## For output  

#### 1. lock / unlock the door  
> //TODO

