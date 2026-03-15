# Stealth Webcam Access - Ethical Hacking Lab

**Student Name:** Zainab Noor  
**Roll Number:** F23-0545  
**Course:** Ethical Hacking Lab  

##  Project Overview
This project is a security proof-of-concept (PoC) designed to demonstrate how social engineering can be used to trick users into granting hardware permissions. The application disguises a live camera stream behind a fake "File Unlock" interface to show how easily users can be compromised.

##  Features
**Social Engineering UI:** A professional-looking landing page designed with student credentials to establish user trust[cite: 5].
**Stealth Capture:** Once the user clicks "Allow," the camera records in the background without a visible preview[cite: 5].
**Phase 1 (Local Storage):** Automatically records and downloads a 7-second video clip to the local machine as a .webm file[cite: 6].
**Phase 2 (Deployment):** Successfully hosted on Netlify to simulate a real-world web attack scenario via a live URL[cite: 7].

##  Security Disclaimer
This project is for **educational purposes only**. It highlights the importance of browser permission safety and the risks of clicking "Allow" on untrusted websites. [cite_start]It serves as a lesson that a simple permission click can give malicious sites control over hardware sensors[cite: 5].
