# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img  (sleuth-kit)
sudo fdisk -l ~/disk.img (GNU)
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![image](https://github.com/user-attachments/assets/51f0c6b3-1756-40eb-8ece-f485c6267fb5)
![image](https://github.com/user-attachments/assets/d7e6f742-e2b4-4ee1-b32a-cd5efcddbf4d)
![image](https://github.com/user-attachments/assets/5e44a18f-8652-4243-a07b-f80a31494462)
![image](https://github.com/user-attachments/assets/baa60897-49b1-4997-943c-a1c8e4bf32f0)
![image](https://github.com/user-attachments/assets/8540c141-355c-4eff-a788-c7702b1dcf74)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

