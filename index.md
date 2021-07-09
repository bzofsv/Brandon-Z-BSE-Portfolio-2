# 32 x 8 LED Matrix Spectrum Analyzer
This project is an LED Matrix Spectrum Analyzer using Arduino and a 32 x 8 NeoPixel LED Matrix. It uses an FFT analyzer to convert audio input to numbers to be displayed on the matrix. It takes computer audio and displays the spectrum onto the LED Matrix. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Brandon Zhang | Lynbrook High School | Electrical Engineering | Incoming Sophmore

![LEDMatrixThumbnail](https://user-images.githubusercontent.com/64446009/124314501-5ae38600-db27-11eb-8300-bf81c78d73fe.jpeg)
  
# Final Milestone
My final milestone is getting the computer sound inputted into the computer so that my LED Matrix can analyze computer sounds as well as microphone sounds. I also added a button to the project, wired from the Arduino to the breadboard, in order to toggle between computer and microphone sounds. Using the button, I can change between displaying my microphone sound and my computer sound using the button. The button input is taken into the Arduino, printed to the Serial monitor, and read the input through Processing. Using the numbers from the button, I can toggle the sound from microphone to computer and back. The way I originally had the button wired, it was very inconsistent, so I had to rewire the button using a pull up resistor instead of a pull down.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/ezvlisAyfmk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>

# Second Milestone
My second milestone is getting the basic project working with my microphone input. I used an FFT analyzer on Processing to convert the input sounds into numbers representing the heights of each of the columns on the matrix. In Processing, I converted the number output of the FFt analyzer to numbers 1-8, representing the height of the columns in the matrix. One problem I ran into was that Processing did not have permission to take audio input from my computer, but Processing was not asking for permission at all, so I was not able to give it microphone access. I worked around this issue by restarting Processing and writing code that would require a microphone, which caused Processing to ask for microphone access. 

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/DgJuS6sL5Zc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>

# First Milestone
  
My first milestone is getting the LED Matrix to light up in a snaking pattern all throughout the matrix. I used the Arduino with the NeoPixel LED Matrix library to write code to do this. This helped me familiarize myself with the NeoPixel Matrix code and the Arduino IDE, and allowed me to experiment with the coding process and how everything was wired together.

<html><iframe width="560" height="315" src="https://www.youtube.com/embed/lD5OQyxPeas" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></html>



# Reflection

Through this project, I practiced with hardware and circuts, instead of software like I was used to. Previously I have made software games using purely software, so it was interesting to integrate hardware and software together to complete a project. I discovered my interest in circuts and wiring through this project. My favorite part of this project is how the LEDs turn on and off, and are very bright and colorful. I also enjoyed coding and debugging this project, since all the changes I made were visual, and I could see my progress as I fixed something, the improvement was visible and showed up on the matrix.
