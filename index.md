# Tensorflowlite Object Detector, By Jake Nanevicz
My project is an object detection system. To use the project, you place the object in front of the attatched camera, and the system will identify the object and print out that guess. It uses the raspberry pi system attached to a Braincraft Hat to display the detections on the screen. There is an external camera for the recording of the object, as there is no built in camera for the Braincraft Hat. 

The modification to the project that I decided on was mounting the system to a robot. The robot is commanded by myself, and I connect my laptop, through a VNC, to the raspberry pi so I can control the bot and see what the camera sees.

<!--- You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions: -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Jake N | Gunn | Electrical and Computer Engineering | Incoming Senior

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**   -->

<!---![Headstone Image](Jake.jpg)  -->
<img src="Jake.jpg" style="width: 50%; height: 50%">

# Modifications

<iframe width="560" height="315" src="https://www.youtube.com/embed/Bby9xVnMxLs?si=quy7sN0_08KX2NOO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Progress

My modification is to mount the raspberry pi to a three wheeled robot, allowing me to control the movement of the camera. So far, I have managed to mount the camera, a battery and I connected the pi to a VNC, allowing me to control the car remotely. My next steps right now are to fix the setup, as right now the setup is very messy, making it harder to work on the project. One of the problems I have faced with this is that I dont have enough space to fit all of my parts. I solved this by completely reshaping where I place my parts, as well as getting a smaller battery and 3d printing a mount for it.
## Challenges

One of the things I struggled with for the modifications was the VNC, as I got new errors each time I connected. From no host found, to authentication error, I could not consistently get the VNC to work. By the end, I realized that some of the ports on the pi were vlocked onn school wifi, so me and Arman started connecting to my personal hotspot. Once that worked, the next problem with my mods was the fitment. I had struggled to fit all of the parts on the chassis, as I was using tape to fit all of the parts, but the tape was taking up more space than the parts. So I took apart the entire chassis and reassembled it using hot glue and a 3d printed holder for the battery, and the parts barely fit.

# Final Milestone
<!--   **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share  Embed, and copy and paste the code to replace what's below.** -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/zEZe-Us_2-w?si=88xVcjys6cefbscA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Progress

The final milestone of the project was to complete the object detection. Using Tensorflow, I was able to set the camera to detect objects. Tensorflow has a database, so I did not have to train the ai model, but it is possible to improve the detection system through further training. I plan to modify the project in a different way, by integrating the system with a robot, allowing the robot to move based on the detections of the ai software. 

## Challenges

  Some of the challenges with this system came from linux and the raspberry pi. It was my first time dealing with both of them, so much of the things I had to do to set up the systems were brand new. As I got more familiar with both systems it became easier to coplete the project

## Accomplishments

  My biggest accomplishment for this project was getting the LCD display to function, as once the lcd display functioned, I had gained a lot of experience with linux through the time it took to get the LCD to work, and the rest of the project was much easier to complete.

## Goals

  I hope to learn more about linux using a Virtualbox, I hope to learn about how to control servos using the Tensorflow software, and I want to just gain experience with hardware through my mods
  
<!--- For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE    --->





# Second Milestone



<iframe width="560" height="315" src="https://www.youtube.com/embed/x2qqPhE9mOY?si=CU2d3d706k3Kq0zh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Progress

Since the last milestone, I have connected the camera to the Raspberry pi, connect the camera to the display, and gotten the AI functions to work. As well as setting up the AI, I have solved my hardware problems, as the ribbon cable arrived and that solved the problems of disconnections. 

## Challenges
<!-- Since the First Milestone, I was able to get the AI element of the project working. The main changes from the first milestone are: -->

The main problems from this section were software, as I had fixed all hardware issues. Not all of the installs worked as intended, as many caused errors. Specifically, many of the installs said that things needed to be installed to continue, but when I checked, they were already installed. Most of the problems could be solved by forcing the install, despite Linux saying that doing so could corrupt the system.

## Next steps

The next step in my project will be the audio system, where the system will be able to say what the system detects using the linux audio systems. 

# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/x42fLah2oPk?si=IGls7z8FMfvzWa6T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Progress

My first milestone included setting up the raspberry pi, setting up the camera, and then connecting the LCD display. I had to first connect the Pi to a monitor so I could run commands on linux and see what I was doing. Once I had set that up, I was able to run the commands that the instructions told me to and set up the LCD display. 

## Challenges

At the beginning, I struggled with getting the pi set up, but when I switched from a 32 bit os to a 64 bit os, I was able to get the system to work. After getting the initial setup working, the rest of the milestone was far easier. One of the other problems I had was from the hardware, where in the instructions they used a different setup than me, as they were able to directly connect the Braincraft Hat to the Raspberry Pi. But because I had to have a fan and heat sinks the Braincraft Hat could not fit on the Pi. At first I tried using extenders, but the Braincraft kept disconnecting. To solve the issue I had to individually wire each pin to its counterpart. I also ordered a ribbon cable to switch to later to solve problems of potential disconnects.
## Next Steps

My next step in this project is to set up the camera, connect it, and finally set up the AI detection system to use the camera output and actually detect objects. I will not be attempting to set up the audio, as I have heard that the audio takes much time, and I would like to get the system working first.

# Starter Project
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17OwP32b1U?si=thviAxQ3rvXzbX2C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I chose the calculator as my starter project. The assembly process was mostly soldering. First, you would solder on the first part of the integrated circuit, then the buttons, and finally attach the button caps and the rest of the integrated circuit. By pressing the buttons, you send signals to the integrated circuit, and the circuit will send signals to the led display to show the outputs of the function. 

## Challenges

This was my first experience soldering, so I struggled with areas where I had to solder in small spaces. For example when soldering the integrated circuit, the pins were in close proximity, so I would often mess up older solders and struggled to make my solders nice. Along with these struggles, I had a hard time working with my second solder, as when I switched, the new solder would not get hot enough to easily melt the solder. As a result, I nearly burned the calculator, I messed up old solders, and I had to switch my soldering iron a second time. 


# Schematics 
![Pinouts](adafruit_products_Braincraft_HAT_RasPi_pinouts_schematic.png)
<!--Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->

Image from:https://learn.adafruit.com/adafruit-braincraft-hat-easy-machine-learning-for-raspberry-pi/pinouts

<!-- # Code
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
# Bill of Materials
<!--
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Adafruit BrainCraft HAT - Machine Learning for Raspberry Pi 4 | Small display for the raspberry pi | $44.95 | <a href="https://www.adafruit.com/product/4374"> Display </a> |
| Raspberry Pi 4 Model B - 4 GB RAM | Single board computer, the computer the system runs on | $45.00 | <a href="https://www.adafruit.com/product/4296"> Pi </a> |
| Raspberry Pi Camera Module 3 Standard - 12MP Autofocus | System camera | $25.00 | <a href="https://www.adafruit.com/product/5657"> Camera </a> |
| Miniature 5V Cooling Fan for Raspberry Pi | Cooling so the system does not overheat | $3.50 | <a href="https://www.adafruit.com/product/3368"> Fan </a> |
| Anker Power Core | portable battery | $21.99 | <a href="https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B01CU1EC6Y/ref=asc_df_B01CU1EC6Y/?tag=hyprod-20&linkCode=df0&hvadid=693712892542&hvpos=&hvnetw=g&hvrand=12042214632185757683&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-523807968135&psc=1&mcid=fdcb0f9cf99a38f59c978b1beff59d4f&gad_source=1"> Battery </a> |
| L298N Motor Driver H-Bridge | Controls motor directionality and movement | $6.49 | <a href="https://www.amazon.com/Diymall-Module-Stepper-Modules-Arduino/dp/B00NJOTBOK/ref=asc_df_B00NJOTBOK/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=14144357909606852772&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2281435177618&psc=1&mcid=170f1bbf2f773d04a1c0254ec6413a12&hvocijid=14144357909606852772-B00NJOTBOK-&hvexpln=73&gad_source=1"> Driver </a> |
| Official Raspberry Pi Power Supply 5.1V 3A with USB C | Power supply for the raspberry pi | $7.95 | <a href="https://www.adafruit.com/product/4298"> Power </a>|
| Emo Smart Robot Car Chassis Kit with Motors, Speed Encoder and Battery Box for DIY | Basic pieces for the robot including battery pack, motors and chassis | $12.99 | <a href="https://www.amazon.com/Smart-Chassis-Motors-Encoder-Battery/dp/B01LXY7CM3/ref=sr_1_4?crid=27ACD61NPNLO4&keywords=robot+car+kit&qid=1689698962&s=electronics&sprefix=robot+car+kit%2Celectronics%2C169&sr=1-4"> Chassis </a> |
| Rii Standard Office for Windows/Android TV Box/Raspberry Pi/PC/Laptop/PS3/4 | Keyboard to connect to the pi | $14.99 | <a href="https://www.amazon.com/Rii-Wireless-Keyboard-Standard-Raspberry/dp/B07WJYVCCN/ref=asc_df_B07WJYVCCN/?tag=hyprod-20&linkCode=df0&hvadid=693606546447&hvpos=&hvnetw=g&hvrand=17403698195771735250&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-837029688405&mcid=dc206b5c84c7385eaf0e70a8e1464ec6&gad_source=1&th=1"> Keyboard and mouse <a/> |
| Soldering Iron Kit, 60W Soldering Iron with Interchangeable Iron Tips, 10-in-1 Adjustable Temperature Soldering Welding Iron Kit for any Hobby Enthusiast 110V US Plug | Soldering iron to connect any wires the need to be attatced on a way not possible without soldering | $14.99 | <a href="https://www.amazon.com/Soldering-Interchangeable-Adjustable-Temperature-Enthusiast/dp/B087767KNW/ref=sr_1_5?crid=1QYWI5SBQAPH0&keywords=soldering%2Bkit&qid=1689900771&sprefix=soldering%2Bkit%2Caps%2C169&sr=8-5&th=1"> Soldering Kit </a> |
| 120pcs 20cm Dupont Wire Female to Female Breadboard Jumper Wires 7.9 inch 1pin-1pin 2.54mm Connector | Connecting wires between Motor Driver and Raspberry Pi | $7.98 | <a href="https://www.amazon.com/EDGELEC-Breadboard-1pin-1pin-Connector-Multicolored/dp/B07GCY6CH7/ref=sr_1_3?crid=3C4YB6HOGZ8ZQ&keywords=female%2Bto%2Bfemale%2Bjumper&qid=1689894791&s=electronics&sprefix=female%2Bto%2Bfemale%2Bjumper%2Celectronics%2C161&sr=1-3&th=1"> Connecting Wires </a> |

<!--- # Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. -->
