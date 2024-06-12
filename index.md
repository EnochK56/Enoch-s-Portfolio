Voice Assistance with AI

#Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

#You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Enoch K | Miramonte High School | Mechanical Engineering | Incoming Freshman

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone



<iframe width="560" height="315" src="https://www.youtube.com/embed/Mxdpz4Z4b1w?si=PSq9wP5v86IvT8AJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
After my first milestone, I worked on getting an Open AI key which is an identifier that can let people use Open AI or Chat GPT in projects. I also linked a speaker and microphone to the Raspberry Pi so it can hear and talk to you. I added a circuit using relays to try turning the lights on and off after I finished the project. What has been surprising to me so far is that I never knew that you could use Chat GPT in your project. Another challenge I encountered was that wires would not stay in their holes when they were put in. This was challenging because the wires would always break apart from the breadboard and I would always get confused on what holes the wires were just in. And also, since the LED is always so flimsy, it is hard to keep the LED in the wires. Before I could say I finished my final milestone, I have to code the microphone to make sure it's listening and code the speaker to make it respond.


# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/Mxdpz4Z4b1w?si=PSq9wP5v86IvT8AJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
After I finished my starter project, I moved on to my main project which is a voice assistant with AI. It will detect your command to it and transform the command into the thing that you want it to do. Like for example if you say "Hey Tom! turn off the lights." The voice assistant will then turn off the lights. This project is like Alexa or Siri. To build the voice Assistant, you will have to first set up a Raspberry Pi, and then, start coding in the Raspberry Pi to build the Voice Assistant. Afterward, wire in a speaker and microphone so the voice assistant can hear you and reply. And that's technically it. Right now, I have finished setting up my Raspberry Pi and started running tests on it to see if it works. The biggest challenge I am facing is getting Raspberry Pi set up. I had to get the installation on my computer then add in the MicroSD card. Then I had to put it in my Raspberry Pi, then use an HDMI cord to try to connect it to a monitor which I realize the cord is too big to fit. Then I had to get OBS to try to use Raspberry Pi on my computer which didn't work because I installed the wrong version of OBS. And after 3 and a half HOURS of grueling work, I finally set up my Raspberry Pi. My plan to complete this project is to continue to follow the codes and add them to the Raspberry Pi to complete my Voice Assistant.

# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/-osPt0VxOHs?si=fB-fBarGrkfehigB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my Starter project, I chose the retro mini arcade. A device that can play 5 different games; Tetris, Snakes, Race Cars, Space Invaders, and Slots. It can also remove sound or turn the brightness up. I chose this project because I thought it would be a great way to learn the basics of engineering and I would also want to learn how to solder things. The arcade works by pressing buttons that send messages to the chip. Afterward, the chip will relay the message to the screen to do what it was told to do. A challenge that occurred for me was the soldering. Since the arcade device was so small, it was a challenge to solder things precisely like for example, soldering the USB port to the chip of the arcade machine.

# Schematics 
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

# Bill of Materials
Here's where you'll list the parts of your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
