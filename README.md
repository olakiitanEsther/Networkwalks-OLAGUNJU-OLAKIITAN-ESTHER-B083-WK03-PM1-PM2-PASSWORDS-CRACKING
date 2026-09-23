# Week 3 Project | PDF Password Recovery Using Password Cracking Techniques

This hands-on project, completed as part of my Week 3A internship at Networkwalks, focused on recovering the password of a secured PDF document. The exercise involved exploring two password-cracking approaches: using John the Ripper (JTR) and its Johnny graphical interface on a Windows PC, and Hash Calculator and Password Cracker tools provided by Networkwalks on kali linux.

### Skills & Tools Covered
* **Skills:** Cybersecurity, Password Recovery, Hash Extraction, Ethical Hacking
* **Operating Systems:** Kali Linux 2026.2, Windows 11 Pro
* **Tools Used:** John the Ripper (JTR), Johnny GUI, Networkwalks Online Tools
* **Author:** Olakiitan Esther


## :pushpin: About This Project

As part of my Week 3A Cybersecurity internship at Networkwalks, I carried out a hands-on exercise involving the recovery of a password-protected PDF file (My Locked PDF1.pdf). The project introduced me to different password recovery techniques using John the Ripper (JTR) and Johnny GUI on my Windows PC. I also explored HashCrack.com and Networkwalks' Hash Calculator and Password Cracker tools.

The same secured PDF document was used throughout the exercise to test different recovery methods. I explored offline password cracking with John the Ripper and Johnny GUI, alongside web-based techniques using HashCrack.com and Networkwalks' online tools. This practical session helped me develop a better understanding of PDF hash extraction, password recovery processes, and the application of password-cracking tools in cybersecurity.

## :warning: Liability Disclaimer

This project was conducted solely for learning and practical training as part of my Cybersecurity internship at Networkwalks. The PDF document used in the exercise was provided specifically for password recovery practice. I recognize that attempting to access protected files or systems without the owner's authorization may breach privacy and applicable laws. Any future use of the techniques and skills gained from this exercise will be restricted to ethical, lawful, and properly authorized activities.

---

## :wrench: TOOL USED

| Tool Used | Link | Purpose |
| :--- | :--- | :--- |
| John the Ripper | https://ibiblio.org | Cracks password hashes to recover passwords. |
| Johnny GUI | https://openwall.info | Provides a graphical interface for running John the Ripper. |
| Pdf Hash Extractor | https://onlinehashcrack.com | Extracts password hashes from protected PDF files for cracking. |
| Networkwalks Hash Calculator | https://networkwalks.com | Calculates and identifies hash values for password analysis. |
| Password cracker tools | https://networkwalks.com | Attempts to recover passwords using extracted hashes. |

---

## :computer: 4.1 Password Cracking with John the Ripper (JTR) – W03-PM1

As part of the Week 3 cybersecurity practical activities, I performed a password recovery exercise on a password-protected PDF document named “My Locked PDF1.pdf.” The exercise was carried out on a Windows PC using John the Ripper (JTR) and its graphical user interface, Johnny. The objective was to understand how password hashes can be extracted from protected files and processed using password-cracking tools in an authorized laboratory environment.

### Step 1: Downloading John the Ripper and Johnny
<img src="Downloading%20the%20JTR%20and%20Johnny%201.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I downloaded the John the Ripper (JTR) package and the Johnny GUI from the provided Google Drive resource.

<br clear="left"/>


### Step 2: Installing Johnny
<img src="installing%20Johnny%202.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I ran the setup file and followed the installation process to install the Johnny graphical interface on my Windows PC.

<br clear="left"/>

### Step 3: Launching Johnny
<img src="Launching%20Johnny%203.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
After completing the installation, I opened Johnny to begin configuring the password recovery exercise.

<br clear="left"/>

### Step 4: Configuring the John Executable
<img src="configuring%20the%20john%20executable%204.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I opened the Settings section in Johnny and browsed to the location of the john.exe file. I selected the executable so that Johnny could use the John the Ripper engine for the password recovery process.

<br clear="left"/>


### Step 5: Preparing the Protected PDF
I downloaded the encrypted PDF document, “My Locked PDF1.pdf,” to my Windows PC so that it could be used for the practical exercise.

### Step 6: Extracting the PDF Hash
<img src="extracting%20the%20pdf%20hash%205.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I used the designated hash-processing website to upload the protected PDF and obtain the corresponding password hash required for the recovery process.

<br clear="left"/>

### Step 7: Saving the Hash
<img src="Saving%20the%20Hash%206.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I copied the generated hash output and pasted it into a Notepad file. I saved the file as “hash1.txt” so that it could be loaded into Johnny for processing.

<br clear="left"/>
### Step 8: Loading the Password File into Johnny
<img src="loading%20the%20password%20file%20into%20johnnny%207.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I reopened Johnny and selected the “Open Passwords File” option to load the hash file generated in the previous step.

<br clear="left"/>

### Step 9: Selecting the Hash File
I browsed to the location where hash1.txt was saved, selected the file, and clicked Open to load it into Johnny.


### Step 10: Starting the Password Recovery Process
<img src="step%2010%20starting%20the%20password%20recovery%20process%208.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
After loading the hash file successfully, I selected “Start New Attack” to begin the password recovery process using John the Ripper.

<br clear="left"/>


### Step 11: Successful Password Recovery
John the Ripper successfully recovered the password associated with the protected PDF file. This exercise provided practical experience in understanding how password-protected files can be analyzed using password hashes and how JTR can be used for authorized password recovery and security testing.
<!-- Drag and drop image here: Successfully recovered PDF password -->

### Step 12: Opening the PDF with the Recovered Password
<img src="step%2012%20opening%20the%20pdf%20with%20the%20recovered%20passwords%209.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I used the recovered password to open the previously protected PDF file successfully. This confirmed that the password recovery process was completed successfully and that the recovered password was valid.

<br clear="left"/>

---

## :globe_with_meridians: 4.2 Password Cracking with Networkwalks Tools

I performed a password recovery exercise on an encrypted PDF file (My Locked PDF-1.pdf) using the Networkwalks Hash Calculator and Password Cracker tools on my Kali Linux system. Since both tools are web-based, I accessed them through a web browser.

### Activities Performed

### Step 1: Downloading the Encrypted PDF File
I downloaded the password-protected PDF file (My Locked PDF-1.pdf) to my laptop.

### Step 2: Accessing the Networkwalks Hash Calculator
I opened the Networkwalks Hash Calculator in my web browser.


### Step 3: Generating the PDF Hash
<img src="GENERATING%20THE%20PDF%20B.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I uploaded the encrypted PDF file to the Hash Calculator. The tool processed the file and generated a hash value beginning with `$pdf$`.

<br clear="left"/>

### Step 4: Submitting the Hash for Password Cracking
<img src="SUBMITING%20THE%20HASH%20FOR%20PASSWORD%20CRACKING%20C.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I copied the complete hash value generated by the Hash Calculator and pasted it into the Networkwalks Password Cracker tool.

<br clear="left"/>

### Step 5: Executing the Password Cracking Process
<img src="EXECUTING%20THE%20PASSWORD%20CRACKING%20D.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
I initiated the password-cracking attack. After the process was completed, the recovered password was displayed on the screen.

<br clear="left"/>

  
* **Step 6: Verifying the Recovered Password**
  <img src="Verifying%20the%20recovered%20passwords%20E.jpeg" align="left" width="380" style="margin-right: 15px; margin-bottom: 15px;"/>
  I used the recovered password to open the previously locked PDF file and confirmed that the document was accessible.
  <br clear="left"/>
  
* **Step 7: Lab Completion**
  I successfully completed the lab exercise by recovering the PDF password and gaining access to the protected document.

---

## :bar_chart: Risk Analysis & Impact Matrix

| Finding | Evidence (From Lab Activities) | Potential Impact |
| :--- | :--- | :--- |
| **Weak PDF Encryption / Simple Passwords** | John the Ripper (JTR) and Johnny GUI successfully recovered the file password. Networkwalks' web tools also quickly cracked the hash. | Unauthorized actors can rapidly bypass document locks, compromising data confidentiality. |
| **Trivial Hash Extraction** | The PDF hash was effortlessly extracted using a basic web browser and a public, designated hash-processing website. | Attackers do not need advanced technical exploits; anyone can isolate a file's security signature to initiate an offline attack. |
| **Availability of Web-Based Cracking Tools** | Networkwalks and HashCrack.com provide free, easily accessible web interfaces to calculate and crack security hashes. | Minimizes the barrier to entry for malicious actors, eliminating the need to install specialized operating systems like Kali Linux. |
| **Exposure of Offline Data Signatures** | Hashes were copied, saved locally into plain text files (`hash1.txt`), and processed entirely offline. | Attackers can run infinite brute-force variants locally without alerting the file owners or triggering account lockouts. |

---

## :bulb: Recommendations

* **Enforce Strong Password Policies:** Implement long, complex, and unique alphanumeric passphrases for all corporate and sensitive personal PDF documents to withstand dictionary or automated brute-force attempts.
* **Transition to Advanced Encryption Standards:** Move away from basic legacy PDF password restrictions. Utilize modern, corporate-grade encryption standards (such as AES-256) which dramatically increase the computational effort required to process extracted hashes.
* **Deploy Secure Content Delivery Platforms:** For high-stakes data, avoid distributing raw encrypted files over open channels. Instead, use secure document management repositories that leverage Multi-Factor Authentication (MFA) and granular, user-revocable access privileges.

---

## :checkered_flag: Conclusion

The hands-on exercises conducted during this internship project successfully demonstrate how easily password-protected PDFs can be compromised using standard penetration testing tools. By leveraging either offline frameworks (John the Ripper and Johnny GUI) or open web-based calculators, a security analyst—or an attacker—can systematically isolate a document's hash value and recover the plain-text password. Ultimately, static PDF password locks represent a low security barrier that should not be relied upon to safeguard high-value, highly confidential data without additional layered enterprise defenses.
