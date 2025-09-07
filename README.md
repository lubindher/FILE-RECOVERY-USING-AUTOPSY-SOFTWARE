# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM

<img width="577" height="785" alt="Screenshot 2025-08-22 151258" src="https://github.com/user-attachments/assets/0e9e4744-5534-4828-8715-d6210ba065c3" />

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

<img width="612" height="421" alt="a1" src="https://github.com/user-attachments/assets/b708135b-a982-48cd-a201-7bf8d571e78e" />

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="994" height="587" alt="Screenshot 2025-09-07 104112" src="https://github.com/user-attachments/assets/ae70448d-6458-4f7f-8e46-a3b3d2fd5c67" />



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

<img width="1070" height="673" alt="a3" src="https://github.com/user-attachments/assets/64e38d5d-35b1-42ee-af04-a07705af103f" />


- Select **Local Disk** → **next** 

<img width="1070" height="667" alt="a4" src="https://github.com/user-attachments/assets/afaabfeb-e422-4f9b-abce-d8a1178f8525" />


- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="1091" height="679" alt="Screenshot 2025-09-07 104232" src="https://github.com/user-attachments/assets/5c81dceb-6b4c-4892-8197-50aaf0814370" />


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  


<img width="1920" height="1080" alt="Screenshot 2025-09-07 105359" src="https://github.com/user-attachments/assets/3ac7ba55-a58b-4e23-94af-82c020abf649" />







- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :

#### Name - LUBINDHER S
#### Reg. No. - 212222240056

### Folder before deleting the files

<img width="1920" height="1080" alt="Screenshot 2025-09-07 105435" src="https://github.com/user-attachments/assets/03fa43a5-b1fd-4239-bfc1-ba9721bf1034" />


### Folder after deleting the files

<img width="1920" height="1080" alt="Screenshot 2025-09-07 105442" src="https://github.com/user-attachments/assets/d5ad4942-890f-4b34-8037-9549879b3045" />


### Folder after extracting the deleted images using autopsy

<img width="1861" height="943" alt="Screenshot 2025-09-07 110304" src="https://github.com/user-attachments/assets/f2fbe723-3062-43b6-a709-0e6108513cf1" />

<img width="1920" height="1080" alt="Screenshot 2025-09-07 105435" src="https://github.com/user-attachments/assets/7037e45c-fb4d-4958-8a87-31cfe10ffbdf" />



## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.
