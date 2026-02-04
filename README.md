# Rain-And-Waterfall-System-For-Terrariums-Paludariums-Design 

<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
<div align="center">


![Logo](/Assets_/1.jpg)

This project is an AI-powered automatic medication dispenser designed to improve medication adherence using a combination of image recognition, OCR, and natural language processing. The system is built for patients, caregivers, and healthcare providers to ensure safe and timely medication intake — all while being monitored remotely through a mobile app.

It integrates hardware control (Arduino), YOLO-based pill recognition, and a custom-trained spaCy NLP model to extract dosage and frequency instructions from prescription labels. A PyQt6 desktop interface manages the system on-device, and a mobile app enables remote supervision. 

All the resources I used for this project can be found in the following Google Drive, linked for your reference: https://drive.google.com/drive/folders/1BSqckdxfqDh0ZibXCd9fYPzXVN9h-TSW 


**This project is not currently licensed for use or redistribution. All rights reserved.**


[![Contributors](https://img.shields.io/github/last-commit/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-)](https://github.com/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-)](https://github.com/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-)
[![Forks](https://img.shields.io/github/forks/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-)](https://github.com/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-/network/members)
[![Stars](https://img.shields.io/github/stars/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-)](https://github.com/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-/stargazers)
[![Issues](https://img.shields.io/github/issues/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-)](https://github.com/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-/issues)
[![License](https://img.shields.io/github/license/SophieBarriault/Dispenser.svg)](https://github.com/SophieBarriault/Rain-And-Waterfall-System-For-Terrariums-Paludariums-Design/blob/main/LICENSE)

[View Demo](https://drive.google.com/file/d/1vlszCyn_WEQVgnMubaLK-mLIXZsSI-Hc/view?usp=sharing) ·
[Documentation](https://github.com/SophieBarriault/Dispenser/blob/main/README.MD)  ·
[Report Bug](https://github.com/SophieBarriault/Dispenser/issues) ·
[Request Feature](https://github.com/SophieBarriault/Dispenser/issues)

 
</div>

---

# 📔 Table of Contents

- [About the Project](#-about-the-project)
  - [Demo Video](#-screenshots) 
- [FAQ](#-faq) 
- [Contact](#-contact)
- [Acknowledgements](#-acknowledgements-) 


---

## 🌟 About the Project

This project presents an AI-powered automatic medication dispenser designed to improve medication adherence and safety for patients. Initially developed for the Massachusetts Science & Engineering Fair (MSEF), the device advanced to the State Level Finalist round, where it was recognized for its innovative integration of machine learning, computer vision, and IoT technologies in a healthcare setting. 


**Goal:**

To create an accessible, intelligent system that ensures patients take the correct medications at the correct times — reducing errors, improving adherence, and offering peace of mind for caregivers and family members. 



**Core Features:**

 - Image recognition model to verify whether medication has been taken correctly.

 - OCR + NLP (Named Entity Recognition) to extract dosage instructions from prescription labels.

 - Arduino-controlled dispensing system triggered by AI verification and scheduled reminders.

 - Mobile + Desktop interface (via Toga framework) for caregiver monitoring and remote updates.

 - Video evidence recording for accountability and patient monitoring. 


---

### 📷 Demo Video 

Click to watch the demo here! 

[![Watch the Demo Video](assets/to_demo.png)](https://drive.google.com/file/d/1wByr87FT2HsipwZgwH-gzBg_70QS4TUb/view?usp=sharing) 


---

<!-- FAQ -->
## :grey_question: FAQ

- **Why did you make this project?** 

  + Because I've always wanted to make my own terrarium, and I specifically wanted to make one that simulates a rainforest. 

- **What was your source of inspiration for this project?** 

  + My sources of inspiration are the various raining rainforest terrariums and waterfall terrariums I saw people making online, as well as the Cloud Rainforest in Costa Rica. 

    1. Detects the presence of a pill

    2. Checks if it’s picked up

    3. Confirms the hand is empty (pill was consumed). 
      If not, an alert is triggered. 


- **How does the dispenser work?** 

  + A built-in camera detects if a pill is taken using a YOLO image recognition model.

  + OCR and NER extract dosage info from prescription labels.

  + The system activates an Arduino-controlled dispenser and verifies intake.

  + Caretakers can view updates via a mobile app.





 
<!-- Contact -->
## :handshake: Contact

Sophie Barriault - [Linkedin](www.linkedin.com/in/sophie-barriault) - sophiebarriaultofficial@gmail.com 

Project Link: [https://github.com/SophieBarriault/Dispenser/tree/main](https://github.com/SophieBarriault/Dispenser/tree/main)


<!-- Acknowledgments -->
## :gem: Acknowledgements 

Sources of inspiration for my project: 


 - [Shields.io](https://shields.io/)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)
 - [Lang diy - Rainfall Terrarium](https://www.youtube.com/watch?v=4Qb6_zVYcik)
 - [AntsCanada - Cloud Rainforest Vivrarium](https://www.youtube.com/watch?v=ZUSEdRb3yVk&t=944s)
 - [Lang diy - Tabletop Terrarium With Waterfall](https://www.youtube.com/watch?v=P3Hv-mUxCJU) 







































