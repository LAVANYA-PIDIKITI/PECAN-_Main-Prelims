# Jurassic Graphic
Steghide is a steganography program that is able to hide data in various kinds of image and audio files. Can I hide a flag within this image? You bet Jurassican.

See if you can uncover the secrets hiding within this image, before it goes extinct.
# Solution
Firstly I checked binwalk and `binwalk filename` and found out the passphrase <br>
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/02fe7569-6af9-4745-9eff-e6131dfb3d1c)
Next I understood they used Steghide to hide the some data with passphrase so to install the same I used `sudo apt install steghide` . Now I used `steghide -sf filename.jpg` to uncover the files<br>
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/3b90c5c3-fda5-4f20-9e8f-270b4f44d309) <br>
Lastly , `cat filename.jpg` or open the file to retrieve the flag <br>
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/549dd6df-c208-4ef5-b6d4-2daccf6df09a)



