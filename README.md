# WhatsApp-Automated-Bot

- This Python script automatically types a given text multiple times and presses Enter using the pyautogui library.

## Prerequisites

- Python 3.x
- pyautogui library

## Installation

1. Install Python from [here](https://www.python.org/downloads/)
2. Install the pyautogui library by running:
- pyautogui is a python module helps you to automatically click and control the mouse and keyboard event.
- to install pyautogui you need to open your command prompt (cmd) or terminal and enter the command.

##

time.sleep(5)
-------------
I have given a 5 seconds of sleep time so that the program does not start executing the commands instantly and I have time to place the mouse cursor on the chat field

## 


for i in range(100):
    pg.write("Anubhav Kumar Gupta")
    time.sleep(0.5)
    pg.press("Enter")
----------------------
In this block of code, I have run a for loop for repeat sending of messages and used pyautogui module and write the message after that I have given a 0.5 second the time interval between each message and after that, I have given the command to press Enter button in the last line to send messages.

