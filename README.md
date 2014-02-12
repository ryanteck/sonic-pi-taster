# Creating Music with Sonic Pi

**Intro**
We are going to make some funky songs on the Raspberry Pi. A Raspberry Pi is a small computer that we can use to create exciting technology. It was created in the UK by the Raspberry Pi Foundation to help young people like you learn how to code.

This small computer features amazing HD (high-definition) quality video and playback, sports high quality audio and has the ability to play 3D games. 

To get going with your Raspberry Pi, you will need to connect cables and add an SD card before logging in.

## Step 0: Setting Up your Pi
First check that you have all the parts you need to get your Raspberry Pi set up and working:

- Raspberry Pi
- Micro USB power adapter
- An SD Card with Raspbian already set up through NOOBS
- USB Keyboard
- USB Mouse
- HDMI cable
- A Monitor or TV
- Some headphones 

**Activity Checklist:**

1.	Place the SD card into the slot of your Raspberry Pi. It will only fit one way so be careful not to break the card. 

2.	Next connect the HDMI cable from the monitor (or TV) to the HDMI port on the Pi and turn on your monitor. 

3.	Plug in a USB keyboard and Mouse into the USB slots on the Pi.

4.	Plug in your headphones to the 3.5mm sound output jack.

5.	Plug in the micro USB power supply and you should see some text appear on your screen.

6.	When prompted to login type:

```
Login: pi
Password: raspberry
```

7.	Once you have logged in, type startx to load the desktop.

## Step 1: First Sounds with Sonic Pi

Let’s play some sounds. 

This is the Sonic Pi application interface. It has three windows. The largest one is for writing your code and we call it the Programming Panel. The top right hand window is the Output Panel and it displays information about your program as it runs. Underneath is the third window; the ‘Error Panel’ which displays information if there is a problem with your program or a bug.

**Activity Checklist:**
1.	Launch Sonic Pi by clicking on the Main Menu, then Education, and then Sonic Pi.
2.	Select Workspace 1.
3.	Type: 

```
play 60
```
4.	Click on the play icon at the top of the screen. What happens?

5.	What happens if you type pley 60 and click on the play icon?

This is an example of a bug in your code. In later activities, if the error panel displays text you will know that you have a bug that you need to fix. It could be that you have miss-spelt a word like play.

6.	Now type:

```
play 60
play 67
play 69
```
7.	Click on the play icon at the top of the screen. What happens?

The computer is playing each note in sequence (ne after the after) but it is happening so fast that to us they sound like they are playing at the same time. 

8.	We need to tell the computer to pause between each note. We can do this by typing the following after each play:

```
sleep 1
```

The value entered after the word sleep represents time in seconds. Using the value 1 represents one second. What would you type for half a second?

9.	Now write a sequence of play and sleep to make a cool sounding tune!


