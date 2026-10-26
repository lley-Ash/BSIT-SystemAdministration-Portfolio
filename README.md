# Week 1 – Building My Professional Environment

## Student Information

**Name:** Martinez, Ashley May M.  
**Course:** Bachelor of Science in Information Technology  
**Section:** BSIT 4E  
**Subject:** ITEP 414 – System Administration and Maintenance  

---

## Objectives

This laboratory activity aims to establish a professional system administration environment by installing essential software, configuring development tools, and creating professional online accounts.

Specifically, the activity aims to:

1. Install and verify essential software for system administration.
2. Establish professional GitHub and LinkedIn profiles.
3. Create an organized GitHub portfolio repository.
4. Develop technical documentation skills using Markdown.
5. Understand the importance of version control and professional development.

---

## Software Installed

The following software and operating system images are required for the laboratory:

- Git
- GitHub Desktop
- Visual Studio Code
- Oracle VirtualBox
- Ubuntu 26.04 ISO
- Windows 11 Enterprise Evaluation ISO

**Note:** Update this section to indicate which applications have been successfully installed and verified.

---

## Professional Accounts

**GitHub Profile:** https://github.com/lley-Ash

**LinkedIn Profile:** www.linkedin.com/in/ashleymay-martinez

These accounts will serve as platforms for professional development, technical documentation, and showcasing academic achievements.

---

## Installation Screenshots

### 1. Git

![Git Installation](screenshots/git.png)

### 2. GitHub Desktop

![GitHub Desktop Installation](screenshots/github-desktop.png)

### 3. Visual Studio Code

![VS Code Installation](screenshots/vscode.png)

### 4. VirtualBox

![VirtualBox Installation](screenshots/virtualbox.png)

### 5. Ubuntu ISO

![Ubuntu ISO Verification](screenshots/ubuntu-iso.png)

### 6. Windows 11 Enterprise Evaluation ISO

![Windows ISO Verification](screenshots/windows-iso.png)

---

## Professional Account Screenshots

### GitHub Profile

![GitHub Profile](accounts/github-profile.png)

### LinkedIn Profile

![LinkedIn Profile](accounts/linkedin-profile.png)

---

## Challenges Encountered

### Challenge 1: Administrator Permission Error

While verifying the Windows 11 Enterprise Evaluation ISO using DISM, I encountered Error 740, indicating that administrator permissions were required to execute the command.

**Solution:**  I reopened Command Prompt using the "Run as Administrator" option and executed the command again. This allowed me to successfully access the information about the Windows installation image.

### Challenge 2: Installation Image File Not Found

When attempting to verify the Windows installation image using the install.esd file, DISM returned Error 2, indicating that the specified file could not be found.

**Solution:** I checked the installation files and discovered that the Windows ISO contained install.wim instead of install.esd. After using the correct file path, I successfully verified the Windows 11 Enterprise Evaluation ISO.

### Challenge 3: Identifying and Verifying ISO Files
Initially, I had difficulty understanding why the downloaded Ubuntu and Windows ISO files appeared as DVD drives in File Explorer. I was unsure whether the operating systems had already been installed or if the files were simply mounted.

**Solution:**  I learned that mounting an ISO file creates a virtual DVD drive without installing the operating system. I used Command Prompt to verify the Ubuntu release information and DISM to confirm the Windows 11 Enterprise Evaluation image. This helped me better understand how ISO files work.

---

## Reflection

During this laboratory activity, I learned the importance of preparing an organized and functional workspace for system administration. I became more familiar with the tools used by IT professionals, including Git, GitHub Desktop, Visual Studio Code, and VirtualBox. I also gained a better understanding of how these tools support version control, technical documentation, and virtual machine management.

One of the most valuable experiences was learning how to verify operating system ISO files using Command Prompt. While checking the Windows 11 Enterprise Evaluation ISO, I encountered errors related to administrator permissions and missing installation files. Instead of immediately assuming something was wrong with the downloaded file, I learned to identify the cause of each error and apply the appropriate solution. This experience helped me become more confident in troubleshooting technical problems.

Creating my GitHub and LinkedIn profiles also helped me recognize the importance of maintaining a professional online presence. Through GitHub, I can organize my academic activities, document my progress, and gradually build a portfolio that demonstrates my technical abilities.

As a fourth-year Information Technology student who is beginning to pursue Data Analytics, I see this activity as an important step in my professional development. The skills I gained in troubleshooting, documentation, and version control will be useful as I continue learning new technologies and working on future projects. Overall, this activity reminded me that becoming a competent IT professional requires patience, continuous learning, and the willingness to solve problems independently

---

## References

- GitHub Documentation: https://docs.github.com/
- Git: https://git-scm.com/
- GitHub Desktop: https://desktop.github.com/
- Visual Studio Code: https://code.visualstudio.com/
- Oracle VirtualBox: https://www.virtualbox.org/
- Ubuntu: https://ubuntu.com/
- Microsoft Evaluation Center: https://www.microsoft.com/evalcenter/
