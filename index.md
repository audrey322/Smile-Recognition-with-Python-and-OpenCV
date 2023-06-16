# Smile Recognition with Python

<!-- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->

| **Engineer** | **School** | **Areas of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Audrey Z | Lynbrook High School | Electrical Engineering | Incoming Sophmore

<!-- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
 # Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE
<iframe width="560" height="315" src="https://www.youtube.com/embed/Uia_CRZ00F8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
# Second Milestone
For my second milestone I added a new message for not smiling text and made them red and green for when you are smiling or when you aren't. I also finished my eye detention program that's separate. I also finished coding my eye detction program. The second time it was a lot simpler to code eye detection because it was a lot of the same things, for example cropping down the face and converting it to grayscale. However it was interesting to figure out the dimensions for eyes because it took a lot of trial and error to find the right placement of the eye squares on the interface. Later in the demo you will see that there is the same square around the face and this time there are also two squares around the eyes that show that the program is working and it knows where your eyes are. This time I also used an eye cascade and  a face cascade like I did for my smile detection. 

Next I would like to learn how to make my own cascade and train it to recognize smiling eyes and then connect that with my original program to make it more accurate to see if you are truly smiling or not and in the future some possible modifications include connecting the program to a handheld device integrating an Arduino and Led. Overall I learned alot in this milestone and gained deeper understainding about how image and object detection works becuase I had to essentially recreate my first program but the target object was eyes. 


<iframe width="560" height="315" src="https://www.youtube.com/embed/Uia_CRZ00F8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
My project is the smile recognition with Python and openCV. This program uses two haarcascades, one to recognize the users face and the other one to recognize if the user is similing or not. These Haarcascades are made up with large amouts of data to pre-train the program. The program crops the users face down to the dimentions like that in the haarcascades and then coverts it into greyscale to again, be similar to the examples. One of the things that took me the longest time to resolve was trying to figure out what to dowlonad. I needed numpy and opencv for this program but and to download an intaller first. The internet told me to download pip but it wasnt compatable with my computer so I ended up dowloading homebrew. After this I had to dowload the newest version of python becuase they still weren't compatable with my computer. In the end, I got my program working. 

Next I would like to make it more efficient and clear to the user whether they are smiling or not. For example as of now it only shows text if you are smiling, I would like to add a not smiling text in red while the smiling text is green. Additionally I would like to play around with the certain values to see if I can get it to be more accurate. In the future I would also like to add some way to use eyes to make it more accurate. For example a real smile is when your eyes also crinkle. I think it would be a cool idea to also input that into the program. 


<iframe width="560" height="315" src="https://www.youtube.com/embed/8-t_CaiJ4nM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!-- # Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

 # Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->
# Starter Project
My starter project was the custom arduino project, where you can add your own input and output. My input was the PIR Motion Sensor and my output was the LED. First I wired up the arduino to the sensor and then uploaded the code. The program first identifies the input, and led pins and then contsntly detects if there is motion infront of the sensor. then it will light up the led accordingly and print a "Motion Detected", "Motion ended" on the serial moniter. After I got all parts to work I soldered on the proto shield and capacitors, restrictors,leds, and buttons, and then replicated the wiring on the proto shield. Overall this project was a fun wiring and soldering project and I had fun. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/FgX3ZWk1tlU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!-- # Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. -->
