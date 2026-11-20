# PASSWORD CRACKING WITH JOHN THE RIPPER(JTR) AND NETWORKWALK TOOLS REPORT
### Password cracking on password protected files

| Field | Detail |
|---|---|
| **Security tester (Cybersecurity Intern)** | **Enoch Muza** |
| **Program/Batch** | B084-Networkwalks |
| **Date** | 19 November 2026 |
| **Modules completed** | W3-PM1 (JTR)<br>W3-PM2 (Networkwalk tools)<br>W2-OPTIONAL1 (JTR+AI) |
| **Target files** | Local locked pdf files|
| **Phases covered** | Password cracking with JTR and AI integration|

# 1. Liability Disclaimer

I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. 
All these materials are for education and research purpose only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. 
Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged.

# 2. Introduction

This report covers the activities that were performed in cracking the passwords of several pdf files that were provided for educational purposes.

The tools and commands used were used in both Windows 10 and Kali linux environment. 

# 3. Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux & Windows | Operating systems used for password cracking |
| John the Ripper(JTR)                | Password cracking tool   |
| Johnny              | Graphical version of JTR       |
| [www.onlinehashcrack.com](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php) | Used to quickly extract the pdf hash |
| [networkwalks.com/hash-calculator](https://networkwalks.com/hash-calculator) | NW tool, used to quickly extract the pdf hash  |
| [networkwalks.com/password-cracker](https://networkwalks.com/password-cracker/) | NW Password cracking online tool  |
| Hexstrike | AI-Powered MCP Cybersecurity Automation Platform |
| Claude | AI-agent for automating password cracking |
| Wordlist | Provided various wordlists for password cracking |


# 4. Activities Performed

## 4.1 Password cracking with JTR

The pdf used in this project tasks was "My Locked PDF1.pdf".
I used windows, to install Johnny and JTR, and the online pdf hash extractor to get the hash of the pdf starting with $pdf$, and uploaded
the hash to JTR, and begin its attack on the pdf hash, until JTR successfully returned the password of that locked pdf file. 
<br/>Password for this pdf: **good-luck** 

## 4.2 Password cracking with Netwokwalks tools

The pdf used in this project tasks was "My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf".
I used the online Networkwalks pdf hash extractor, and it returned similar output with $pdf$, then used Networkwalks password cracking tool, using that 
pdf hash, to crack the password for that pdf.
<br/>Password for this pdf: **password1** 

### 4.3 Password cracking with Hexstrike+Claude AI + JTR

The pdfs used in this optional project tasks was "My Locked PDF2.pdf" and "My Locked PDF3.pdf".
I first installed Claude Desktop, then Hexstrike. Adjusted one of the python requirements of Hexstrike so that it could complete downloading
the main required dependenices. Edited Claude Desktop, MCP configuration, point at Hexstrike server. Performed health checks to see what
Claude can access, and what tools are available. I then executed AI prompts for Claude, to extract the pdfs hash, and execute jtr through
Hexstrike, to crack the password of the two pdfs.
<br/>Password for "My Locked PDF2.pdf": **password1** 
<br/>Password for "My Locked PDF3.pdf": **1qaz2wsx** 

# 5. Recommendations

Based on the observations from these activities, I recommend the following security improvements

<br/>- Password lengths should be longer
<br/>- Passwords should be a mix of characters (numbers,punctuations,different cases)
<br/>- Passwords should not refer to common daily words
<br/>- Avoiding to use passwords that are known in past data breaches

# 7. Conclusion

During Week 3 of my Cybersecurity internship, I completed practical activities covering password cracking with John the Ripper, Johnny,
online hash calculators, Automation security testing with Claude AI.
Faced some initial challenges setting up the software due to version mismatch from what was document and the latest versions, but
managed to troubleshoot the problems and got everything working as expected.

Learnt how to calculate hashes of files using available software,  to use John the Ripper in cracking common passwords. Learn the best practices of how some passwords can be weak or strong
Experienced how to intergrate Hexstrike with Claude AI, for automated security testing.

# 8. Evidences Collected









