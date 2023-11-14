# ASCII FTW

## Problem
This program has constructed the flag using hex ascii values. Identify the flag text by disassembling the program.

## Points
100

## Solution
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/479aae8c-0a44-41f6-ab9f-43caadbc6689)
This is what it says after executing.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/24ad6fd3-b97c-4dd6-b2ad-7a9b6dd497e4)

Used Ghidra to decompile the file.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/7d6aee2f-399a-4173-9562-1152cd285446)
Contains the ASCII value of each character in the flag
And plugged those ASCII values into a converter.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/ffb80d4b-1140-4a83-9e7e-25ca78e89f75)

## Flag 
picoCTF{ASCII_IS_EASY_3CF4BFAD}
