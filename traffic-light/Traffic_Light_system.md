# Simple Traffic Light Turning ON and OFF system with Arduino

- Green -> 2 seconds delay
- Yellow -> 1 seconds delay
- Red -> 5 seconds delay


## Video


![watch the video](https://drive.google.com/file/d/1mo3BFqSNwGjTi3GKHJP0Y4SbirsGUYwd/preview)


## Code


```cpp
// C++ code
//
void setup()
{
  pinMode(6, OUTPUT); //Green led
  pinMode(4, OUTPUT); //yellow led
  pinMode(2, OUTPUT); //red led
}

void loop()
{
  digitalWrite(6, HIGH); // Turn on Green led
  delay(2000); // Wait for 2 second(s)
  digitalWrite(6, LOW); // Turn off Green led

  digitalWrite(4, HIGH); // Turn on yellow led
  delay(1000); // Wait for 1 second(s)
  digitalWrite(4, LOW); // Turn off yellow led
  
  digitalWrite(2, HIGH); // Turn on red led
  delay(5000); // Wait for 5 second(s)
  digitalWrite(2, LOW); // Turn off red led
}
```

