---
title: Cyberpatriot Competition Preparation
---

>[!danger] Don't be stupid. Access to these resources is a privilege.

>For actions that require an admin password, ask Mrs. Christie

>**BE RESPONSIBLE**
## <u>Competition Preparation</u>
### Resources Preparation
1. Each team should need no more than 5 laptops, one per team member competing at a time. Label each using your team name and what image it will be used for:
	- Ubuntu/Mint
	- Windows
	- Server
	- Cisco
	- Research/Debian
2. Take a plastic tub for your team and make a supply container. Include your team name on the box. The box should include:
	- 6 ethernet cables and a switch *(optional this year as we have WiFi)*
	- Surge protector
	- Chargers for your laptops
	- Mouses if your team wants them
### Laptop Preparation
1. Login to your laptops using your school login.
	- `firstname.lastname` & `lunch number`
	- `@stu.hsv-k12.org` is not required to login
1. Run all Windows updates 
	- **Do not install preview updates**
2. Ensure Public user folders are clear
	- `C:\Users\Public\Downloads` and `Documents`
3. Clean any files that are **not** needed for competition. Music, videos, photos, games etc.
	- **Ensure file name extensions AND hidden files are enabled.**
4. Install the required software:
	- For the laptops with images (Windows, Server, Ubuntu, Debian, etc.) install VMware workstation using the link on the [Cyberpatriot Website](https://www.uscyberpatriot.org/competition/technical-specifications)
	- Cisco laptops will need downloads from the [Netacad Website](https://legacy.netacad.com/portal/resources/packet-tracer)
5. Once laptops have finished installing updates and software, restart the laptops.
6. Using the Google spreadsheet provided to you, find the laptop number of the laptop you prepared, and list your procedures and name. <span style="color:b11e1e;"><b>This is not optional. All unlisted laptops will need to be re-cleaned for security purposes.</b></span>
### Image Preparation
Prior to competition (as early as you can), download the respective images on each of the laptops, using the links provided to you on the email from your instructor.
- Save the images to `C:\Users\Public\Downloads` (the directory should be empty).
- Verify the images using WinMD5 (downloaded in previous steps).
>[!warning] **Do not extract until competition day**
## <u>Competition Day</u>
You will be assigned either a spot in Mrs. Christie's room or your own private room to compete in. Ensure you have all of your laptops, chargers, and any other resources you may need.

<b>For laptops with images:</b>
1. Take a photo of your competition space to return it back to normal after competition
2. Connect everything: surge protector, laptop chargers, and ethernet+switch (if applicable)
3. Ensure your laptops have a valid network connection using the [CyberPatriot Competition System (CSS) Connection Test](https://ccs-software.s3.amazonaws.com/ccsv13/New_Connection_13.0/CCS_Test_Connection-13.0.7z).
4. Extract the images on the laptops into the `C:\Users\Public\Downloads` folder using 7-zip.
5. Open VMware Workstation, and select "Open a Virtual Machine" then navigate to the folder in which you extract the image. Select the `.vmx` file to open it in VMware.
6. Select the virtual machine, and click "Edit virtual machine settings". Change your memory to 8 GB, and your CPUs to `cores=2, threads=2` (can be scaled up depending on the laptop you're using, check task manager if you want).
8. Start your image and input your Unique Identifier, provided in the email from your instructor.
	- If prompted, select "I Coped It"
9. Have fun!

<b>Netacad laptop:</b>
1. Login to the laptop using your school email/password and login to Netacad with the credentials provided in the email from your instructor.
2. Complete the Netacad quiz and download the packet tracer assignment.
	- **Save every 15 minutes** and submit the assignment when finished.
	- Delete all files from the device upon completion.
## <u>Post-competition round</u>
1. Ensure you have selected `Stop scoring` when finished with the images.
2. Power off the virtual machines. **Do not suspend**.
3. Delete all images in `C:\Users\Public\Downloads`
4. Pack up all belongings and resources and use the picture to restore your workspace to its original state.
## <u>Troubleshooting</u>

>[!example]- Scoring report issues
>Ensure your Unique Identifier was entered correctly. You cannot enter your UID too many times. You can also check the Scoring Report for any errors. If all else fails: Power off, delete, re-extract, and power back on your virtual machine. **Will reset scoring, ensure you have taken pictures of your scoring reports**

>[!example]- Image freezing
>- Power off, delete, re-extract, and power on your virtual machine.
>- **Will reset scoring, ensure you have taken pictures of your scoring reports**

>[!example]- Penalties
>Review the Scoring Report and identify the cause of the penalty.

>[!example]- Ubuntu password lockout
>This is a canon event. Power off, delete, re-extract, and power on your virtual machine.
>**Will reset scoring, ensure you have taken pictures of your scoring reports**

>[!example]- Other problems
>Use online resources to troubleshoot the problem. If all else fails, ask Hugh or Owen.

## <u>Tips and Tricks</u>
- **Windows**: Use `secpol.msc` for additional points; read the Readme closely
- **Windows Server**: Identify and harden the server type by removing unnecessary packages.
- **Ubuntu/Debian**: Familiarize yourself with terminal file navigation and commands. The terminal is extremely powerful when used correctly.
- The netacad course provides everything for a high score; use the built in Netacad Ctrl + F to quickly find answers during tests.
## <u>Networing Tips</u>
- Study the netacad course: All test and Cisco Packet Tracer activity content is here.
- Preview competition topics: Review the modules needed for each round at the [CyberPatriot Website](https://www.uscyberpatriot.org/competition/current-competition/challenges-by-round).
- Understand core concepts: For each unit, know both the what and why of the topics.

## <u>ChatGPT and LLM usage</u>
According to CyberPatriot's website, you are permitted to use ChatGPT and other generative AI/LLMs to assist you **outside of competitions**. Meaning, you are allowed to use it to help you make scripts, plan competitions, etc, as long as it is not being used during a competition round.

>[!danger] Failure to comply with this *might* get you disqualified. I wouldn't test it.
