# Wh4tS th1s f1l3?
We've found this suspicious file on a computer during a court case. Your job as the forensic analyst is to recover the data contained within the file. See if you can extract the relevant data from the file.

Hint: perhaps it's a backup of a drive?
# Solution
Download the hidden.fs file and
```bash
sudo mount -o loop /path/to/hidden.fs /mnt/hidden
```
Now
```bash
cd /mnt/hidden
ls
```
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/49d08921-02b4-4bb4-9616-5685a616034a)
To view the hidden files
```bash
 ls -a
```
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/4d34950c-69dd-4707-9d2f-1d49983a836a)
Now move the hidden flag.odt
```bash
mv .flag.odt flag.odt
```
If permission denied then try 
```bash
sudo mv .flag.odt flag.odt
```
Last , use an online tool to view the odt file - https://products.aspose.app/words/viewer/odt . Make sure you click on other locations of computer, browse and then upload the flag.odt <br>
![image](https://github.com/LAVANYA-PIDIKITI/PECAN-_Main-Prelims/assets/98797256/be52df75-8c9d-40d2-bd8c-21bd476e9884)



