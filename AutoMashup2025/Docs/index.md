# AutoMashup

### A workflow app which generates mashups

![Animation](./images/animation.gif)

Hello there! We're a group of students who worked to develop an application that aims to create mashups automatically.

### How does it work?

Given several songs, our app uses state-of-the-art tools to separate the sources of the songs and then to reunite them to create a new song.

## Examples of mashups realized with the app

### Audio: Hi-Q - My Sweetie Went Away
<audio controls>
  <source src="./mashups/mashup_Bam Bam - Hi-Q_Bessie Smith - My Sweetie Went Away.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

### Audio: Jewel - Ein sonniger Tag mit dir
<audio controls>
  <source src="./mashups/mashup_ZOE LEELA - Jewel_deef - Ein sonniger Tag mit dir.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>


## Tutorial

#### Import and preprocess songs

Browse through the files on your computer to import the songs of your choice.  
![Import](./images/1.png)

Trigger preprocessing to add your song to the list of songs. This will take a while... 
![Preprocess](./images/2.png)  
Once it's done, your song will be added to the list, along with information about its BPM and key. 

![Song List](./images/3.png)

Now, you can start creating your mashup.   
![Creating Mashup](./images/4.png)

#### Track Workflow

First, add your 'Track' blocks and choose the songs you want to mix using the elevator.  
![Track Blocks](./images/6.png)

Then, add a 'Mixer' block and choose your mashup technique.  
![Mixer Block](./images/7.png)

Now, link your 'Track' blocks to your 'Mixer' block by selecting the vocals or instruments of your choice for each input.  
![Linking Blocks](./images/8.png)


#### Execution

Once it’s done, you can execute it.  
![Execution](./images/10.png)  

It will take a few seconds, and then the player will appear.  
Congratulations, you can now listen to your own mashup!  
![Mashup Player](./images/11.png)
