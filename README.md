<img width="1280" alt="readme-banner" src="https://github.com/user-attachments/assets/35332e92-44cb-425b-9dff-27bcf1023c6c">

# CompliGo🎯


## Basic Details
### Team Name: A10 scn aa


### Team Members
- Team Lead: Ziyan Tharick - TKMCE
- Member 2: Athuldev - TKMCE
- Member 3: Mohammed Shidhath C - TKMCE

### Project Description
it is a webpage which gives you real time compliments based on ur facial expressions as it has camera access which tracks ur face. Getting good compliments can enhance ones mood which may even result in having an amazing day to day experience from using our web page.

### The Problem (that doesn't exist)
People get bad compliments everytime which weakens their mood.

### The Solution (that nobody asked for)
Provide Random compliments to make up for all the bad ones thereby giving the user a sense of happiness.

## Technical Details
### Technologies/Components Used
For Software:
1. HTML, CSS, and JavaScript
HTML: Used for the structure and layout of the webpage.
CSS: Used to style the elements, including gradient animations, button effects, and general layout.
JavaScript: Used to handle the tab switching, camera functions, and compliment display logic.
2. Fonts
Google Fonts (Poppins): Imported via a link to give the webpage a custom font style.
3. JavaScript Libraries
jQuery: Imported from a CDN, used to simplify DOM manipulation and event handling.
Source: https://code.jquery.com/jquery-3.6.0.min.js
tracking.js: A JavaScript library for tracking objects (in this case, faces) in the video feed.
Source: https://cdn.rawgit.com/eduardolundgren/tracking.js/master/build/tracking-min.js
Face Tracking Plugin: https://cdn.rawgit.com/eduardolundgren/tracking.js/master/build/data/face.min.js
4. Browser APIs
WebRTC (Web Real-Time Communication): The getUserMedia() API is used to access the user's camera, allowing for video capture.
Canvas API: Used for drawing a bounding box around detected faces on the video feed.
5. CSS Animations
Keyframes Animation: Used to create a gradient background transition and fade-in effect for compliments.
6. HTML5 Video and Canvas Elements
Video Element (<video>): Displays the live video feed from the user's camera.
Canvas Element (<canvas>): Used to overlay graphics (like face bounding boxes) on top of the video feed.


### Implementation
For Software: Virtual Source Code
# Installation
type the following into the terminal
git clone https://github.com/your-username/Compligo.git
cd Compligo
python3 -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install Flask

### Project Documentation
For Software: Compligo is a web app providing real-time compliments based on live face detection. Built with HTML, CSS, and JavaScript for the frontend, it uses Flask as the backend to serve templates. The app incorporates tracking.js for face detection and jQuery for DOM interactions. Users enable the camera to receive compliments when a face is detected.

# Screenshots (Add at least 3)
![image](https://github.com/user-attachments/assets/909ccb49-952e-49d8-adf2-b38cb1ea430a)
 VScode
this is just a glimpse of our code

![image](https://github.com/user-attachments/assets/2a8e27d9-285c-4bbf-bdad-31437c066d38)
Front Page
This shows the landing page upon clicking run

![image](https://github.com/user-attachments/assets/d33f611d-7d25-419b-8252-e86ba4314705)
2nd page
This page has the face tracker and gives you compliments

# Diagrams
No Diagrams

### Project Demo
# Video
[The video attached shows how the code runs and the output Webpage it gives which is CompliGo. You can see that it has a real time face tracker and also shows various compliments to brighten up your mood.
](https://drive.google.com/file/d/1EUQgqVpiCv07dgKLfNs4U1fUyHIgI36a/view?usp=drive_link)

## Team Contributions
- Ziyan Tharick: Additional Ideas and Coding Work
- Athuldev: Core Idea which we used
- Mohammed Shidhath C: Coding Work

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProject--24-24?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)



