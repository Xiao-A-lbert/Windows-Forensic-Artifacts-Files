# Windows Forensic Artifacts: Files

<h2>Description</h2>
In this Digital Forensics task, I used registry explorer and shellbags to explore windows files artifacts.

<h2>Languages and Utilities Used</h2>

- <b>Registry Explorer</b>
- <b>ShellBags Explorer</b>

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise</b> 

<br />
<br />
In registry explorer going to NTUSER.DAT\Software\Microsoft\Windows\Shell\Bags to see all the files currently on my desktop. 

![1) NTUSERDAT Software Micorsoft Windows Shell Bags ](https://github.com/user-attachments/assets/7df014b9-c075-442b-a8ff-02e3189b849a)

<br />
<br />
Using ShellBags Explorer to parse out this information further, I can see an example file called "Anything" that has been deleted and all of its artifacts like created date, modified date, etc.  

![2) Shellbags to examine anything file that was deleted ](https://github.com/user-attachments/assets/c3cc456c-27d5-432d-9e0d-950688f53c52)

<br />
<br />  
Back on registry explorer going to NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\ComDlh32\OpenSavePIDMRU to see files most recently saved files.

![3) NTUSERDAT Software Micorsoft Windows CurrentVersion Explorer ComDlh32 OpenSavePIDIMRU](https://github.com/user-attachments/assets/401ad6c6-c35e-43b9-badb-db5d17ffbebf)

<br />
<br />
Going to NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\RecentDocs will show the artifacts of most recely accessed files on the system. 

![4) NTUSERDAT Software Micorsoft Windows CurrentVersion Explorer RecentDocs](https://github.com/user-attachments/assets/bdc3cb56-a711-4a63-9b82-0d67b14aa77e)

<br />
<br />
Going to NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\RunMRU will show the most recent run commands. This sytem shows no run commands. 

![5) NTUSERDAT Software Micorsoft Windows CurrentVersion Explorer RunMRU](https://github.com/user-attachments/assets/2ce7377c-1150-4797-81b8-e4315508b9a1)

<br />
<br />  
Going to NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Explorer\TypedPaths will show the most recent typed paths in file explorer. This system shows no typed paths. 

![6) NTUSERDAT Software Micorsoft Windows CurrentVersion Explorer TypedPaths](https://github.com/user-attachments/assets/3a2b4307-1515-4803-adbb-85b52233f886)

<br />
<br />
