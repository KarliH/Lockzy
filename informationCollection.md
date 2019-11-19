# Resources might be used  

## For input  

#### 1. Get input
> //TODO**



## For main functions  

#### 1. check password  

``` 
void checkPassword(){
  if (password.evaluate()){
    digitalWrite(greenLED, HIGH);
    lcd.clear();
    delay(30);
    lcd.setCursor(1, 0);
    lcd.print("Acces Granted");
    lcd.setCursor(4, 1);
    lcd.print("Welcome");
    unlockdoor();
    delay(2500);
    displayCodeEntryScreen();
  }
  else{
    loop(); {
      redlight();
    }
    lcd.clear();
    delay(10);
    lcd.setCursor(2, 0);
    lcd.print("Acces Denied");
    delay(2500);
    lcd.clear();
    displayCodeEntryScreen();
  }
}
``` 
[Resources from](https://www.instructables.com/id/Arduino-password-lock/)  

---

## For output  

#### 1. lock / unlock the door  
> //TODO**

