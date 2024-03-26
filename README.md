# Almost Gotcha!
### Evil USB

## Requirements
1. USB Rubber Ducky (or any other small computer that can act as a HID and reads DuckyScript)
2. MicroSD card
3. The almost_gotcha txt file compiled into an inject.bin file

## Introduction
The Evil USB is a password stealing penetration tool. It utilizes DuckyScript to transer an encoded Python script. This script goes into Chrome and pulls all usernames and passwords from whoever is logged in. It then puts all of these passwords into an email and ALMOST sends them to a recipient of your choice.

## Usage
1. Download the DuckyScript and input it into Hak5's payload generator: https://payloadstudio.com/login/
2. Transfer inject.bin file that is generated into a microSD card. (Note: The sd card needs to be formatted as FAT/FAT32, and have NO OTHER FILES/FOLDERS)
3. Place microSD into Rubber Ducky and surprise your friends.

## Potential Customization
What I have created is a template for this attack. You can customize this in many different ways. One easy way would be to change the email address that it sends the usernames and passwords to. A more creative way would be to hide these processes in the background so that the user has no idea this is happening. Up to you!

## Usage Agreement
This repositories contents are not intended for any use other than educational.

