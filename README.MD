# CTF Challenges

# Hardware
-----------------------------------------------------------
## Hello Hardware
Solved the challenge using ***logic gates***, and put the values in the simulator to get the flag

## Noice_UART
For Noice UART challenge, decyphered the *UART* to *Ascii* to get the flag

## 5niff--1t-
I used a tool called the **saleae logic tool**, and then had to use an *analyzer* to get the hex and changed it to ascii, which gave me a conversation which hinted on what to do to get the flag, *multiplying the baud rate by 12 times* and when i changed the baud rate i got the flag in the place of numbers

## Baby_IR
Decrypted each line of the binary to hexacode and compared it with the code in *tinker-cad* and got the flag



# Crypto
-------------------------------------------------------------
## Transkey
For the transkey challenge, i used many decyphers and one of them fethched me a *key* when given for autosolve and using that key, i got the flag

# Wireless
---------------------------------------------------------------
## 4Chan's Favourite
I used *Sonic Visualizer* for this challenge, put the .wav file in and  added a layer of spectrogram, i could see the image of Rick Astley.

## Murphy's Ghost
There were two files for this, one of them i did the same method and opened it in sonic visualizer and when added a spectogram i could see the work **COOPER.**
The other file was morse code, after deciphering the morse code, got a Random string of letters , used a decrypter and used the keyword for decrypting as 'COOPER' and i got the name "matthewmcconaughey" which was the flag. 

## Dots and Dashes
It was morse code, after i got rick rolled. So i Decyphered the morse code and got the flag

# Reversing
-----------------------------------------------------------------
## Easy as You
Had to use a tool called the IDA64 which was a decompiler, and then went through the code, which showed an ictf{Qm4vZr1vZk5qZv5Za4cc4fpi2} and then there was another modification being done to that, gave me the flag.

## Baby_rev
For this challenge, honestly i just opened the file in text editor and used command+f to find the flag.

## Awesome Numbers
I admit, i did this the hard way, learnt what the assembly level keywords do in each condition and used pen and paper to calculate the value of eax. I know it could have been done easily if i made the loop in C or Python, but I just went with the flow of what i was doing and didnt' want to stop.

# MISC
-------------------------------------------------
## Sanity Check 1
Got the flag

## Sanity Check 2
Got the flag

## IRC
For the irc challenge i had to join the libera chat of Bios-Hardware to get the flag. Client name - gungani

# WEB
---------------------------------------------------
## Web Inspector
Used Inspect element, to get the flag, the second flag was also seen but it didnt accept

## Inspeccionar_y_disfrutar
Just used the inspect element and got the flag

# OSINT
-----------------------------------------------------
## Finding Joey
For this challenge, If we look closely we can see some text on the image, but a reverse image google search made me find the place "The English National Ballet" and searching the nearest bus station gave me the canning town bus station.

# Programming
-------------------------------------------------------
## (net) cat of the bag
Got nc command after opening challenge instance, ran it in terminal and got the flag. Why SO SERIOUS ?


