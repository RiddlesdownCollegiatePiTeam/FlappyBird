## CloudFly (using Pygame)

A clone of the popular app *Flappy Bird*, using Pygame.

## Playing the game

You control the little bird. You can make it climb by pressing the up arrow on the MakeyMakey, or using your voice through a USB microphone. Don't crash into any pipes! For every pipe you pass without colliding, you get one point.


## Requirements

You will require the following python modules to run it on your system - it does not have a specific system dependency (i.e. you can use Linux, Windows or Mac (although it hasn't been tested on the latter two) but you may find that the input device index changes on different systems:

-> SoundAnalyse  
-> PyAudio  
-> PyGame  

You can find a YouTube link to our project here: https://youtu.be/wXxLOExAK5k

## Installing Dependencies and Editing Instructions:
1. Install the necessary libraries on your Pi (sudo portaudio19-dev) 
2. Install the necessary Python modules (pip install pyaudio, pip install pygame, pip install)
3. Download/clone the GitHub repo
4. To run the program you may have to make a few edits, but the only changes you will likely have to make is changing the "PYAUDIO_DEVICE_INDEX" constant (which is currently set to 2, because on our test devices this was the device index, it may differ for your devices)
5. You can also edit other features such as:
   -> The font for the app (Python code - lines 331-333)
   -> The background image (Edit the "background.png" file in the "images" folder, along with the "WIN_WIDTH", and "WIN_HEIGHT" constants, which will correspond with your image)
   -> The "Bird" (Edit the "bird_wing_up.png" and "bird_wing_down.png" files in the "images" folder - take care to scale this down so that the bird fits through the pipes!)
   -> The "Pipes" (Edit the "pipe.png", "pipe_end.png" and "pipe_body.png" files in the "images" folder - make the dimensions of these similar to the current dimensions, to avoid having to edit the code.
6. Follow the instructions to run the program

## Instructions to Run:
1. Connect Raspberry Pi to a Display / VNC (Although we haven't tested this using a VNC client).
2. Connect Makey Makey to the Pi
3. Connect Microphone to the Pi
4. Run the Python code
6. Enjoy the game
7. Select us to win the Raspberry Pi competition!!

## Credits:
 - Chaitanya Katpatal (Main Coding)
 - Matthew Gale (Coding)
 - Parv Patel (Coding)
 - Luke Ward (Coding)
 - Michael Piscina (Logo Design)
 - Daniel Wallace (Designer)
 - Saad Majid (Designer)
 - Harrison Cadle (Designer)
 - Pranav Katpatal (YouTube Video)
 - Daniel Bates (YouTube Video)
 - Mathushan Shanthan (Write-Up)
