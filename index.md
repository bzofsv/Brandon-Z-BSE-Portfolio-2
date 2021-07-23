# Phone Controlled Robotic Arm
This project is a phone controlled robotic arm. It uses an ESP32 to recieve signals through Bluetooth into an phone app. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Brandon Zhang | Lynbrook High School | Electrical Engineering | Incoming Sophmore

![LEDMatrixThumbnail](https://user-images.githubusercontent.com/64446009/124314501-5ae38600-db27-11eb-8300-bf81c78d73fe.jpeg)
  
# Final Milestone
My final milestone is finishing the Arduino code to take in values from Bluetooth, convert them to servo positions, and sets the servo to that position. The code takes inputs from Bluetooth and reads the first two characters to determine which servo. Afterwards, it ignores the first two and reads the number, which is 1-50, and converts to a number from 1-180 which is then intputted to the servos.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/5K65qKzmIDI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>

Arduino Code:

<img width="345" alt="Screen Shot 2021-07-23 at 11 08 37 AM" src="https://user-images.githubusercontent.com/64446009/126823546-db129fbd-7030-45a9-b592-ec0bf11888db.png">


# Second Milestone
My second milestone is finishing the phone app and connecting it to the ESP32. The phone app is designed using MIT App Inventor, an online software, and downloaded onto an Android phone. The phone connects to the ESP32 through Bluetooth, and using the sliders, controls each servo at the joints. The app also has two buttons to connect and disconnect, and text displaying whether or not Bluetooth is connected. When each slider is changed, the position of the slider, as well as a prefix to show the servo number, is printed to Bluetooth. 

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/CL_Ch6y5oyo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>

App code:
![MIT App Inventor Code](https://user-images.githubusercontent.com/64446009/126823391-31409fcc-2a69-4ecb-9b25-02d5727ed3c3.png)

# First Milestone
  
My first milestone is finishing the building of the robotic arm. The arm uses four servos to control the jaw, up and down, forward and back, and rotation. While building, some of the pieces were too thin and broke easily so I had to be careful not to damage the pieces. I also did not have enough nuts, so I was delayed by a few days while I built the arm.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/8CjLjfzTiBU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>



# Reflection

Through this project I learned how to send and receive information through Bluetooth, and also use the ESP32 as a Bluetooth device for other devices to connect to. I also learned how to design and code apps using MIT App Inventor and download them onto an Andriod phone. 
