Human-Computer Interaction and Computer Graphics (HCI-CG) Lab Assignments
Overview
Welcome to the Human-Computer Interaction and Computer Graphics (HCI-CG) lab assignments repository, created by Farhan-Ul-Haq (SAP ID: 55853) for the HCI course at Riphah International University, under the supervision of Sir Usman Sharif. This repository contains 13 lab assignments that explore HCI principles, usability evaluation, interface design, prototyping, and the integration of HCI with computer graphics (CG). The primary tool used for wireframing and prototyping is Figma, complemented by coding in Python, HTML, CSS, and JavaScript.

Repository Contents
The repository includes lab assignments covering various aspects of HCI and its integration with CG. Below is a summary of the labs:

Lab 1: Introduction to HCI and CG integration, focusing on user-centered design and wireframing with Figma.
Lab 2: Analysis of real-world designs (e.g., iPhone home screen, microwave control panel) and redesigning poor interfaces using HCI principles.
Lab 3: Implementation of WIMP interfaces (Task Manager), direct manipulation enhancements, CLI calculators, and menu-driven to-do lists using Python (Tkinter).
Lab 4: Exploration of cognitive processes (attention, perception, memory, automation) using Tkinter, Matplotlib, and Selenium.
Lab 5: Application of Norman's Model to an online banking system and redesigning an ATM interface with HTML/CSS.
Lab 6: Redesign of an Issues-Evaluators Matrix using HTML for clear visualization of usability issues.
Lab 10: Design of a food delivery app with paper prototypes and HTML-based interfaces, applying Fitts's Law for usability.
Lab 11: Creation of personas (e.g., busy professional, college student) and wireframes for a food delivery app using Figma.
Lab 12: Application of the Question-Option-Criteria (QOC) framework for design decisions in a food ordering website, focusing on navigation and menu presentation.
Lab 13: Exploration of color theory in HCI and CG, designing an accessible mobile app login screen using Figma and tools like ColorZilla.
Tools Used
Primary Tool: Figma - Extensively used for wireframing and prototyping user interfaces (e.g., food delivery app, login screen).
Other Tools:
Python: Tkinter for WIMP interfaces, Matplotlib for data visualization, Selenium for automation, Pandas for task time analysis, and tkcalendar for date selection.
HTML/CSS/JavaScript: For interactive prototypes (e.g., food delivery app, ATM simulator, online banking system).
Adobe XD, Balsamiq: Secondary tools for wireframing and prototyping.
ColorZilla, Adobe Color, WCAG Contrast Checker: For color accessibility and design evaluation.
Key Learning Outcomes
Mastered HCI principles like usability, visibility, affordance, and feedback.
Applied Norman's Model and QOC framework to create user-centered designs.
Designed inclusive interfaces adhering to accessibility standards (e.g., WCAG guidelines for color contrast).
Integrated HCI with CG for immersive applications like VR, AR, and video games.
Developed and evaluated prototypes using Figma and other tools.
Analyzed cognitive processes (attention, perception, memory) in UI design.
Setup Instructions
To explore or run the code in this repository:

Clone the Repository:
bash

Copy
git clone https://github.com/Farhanulhaq19/Human-Computer-Interaction-CG.git
cd Human-Computer-Interaction-CG
For Python-based Labs (Labs 3, 4):
Ensure Python 3.x is installed.
Install required libraries:
bash

Copy
pip install tkinter matplotlib numpy pandas selenium tkcalendar
For Selenium (Lab 4), download and install the Chrome WebDriver matching your Chrome browser version.
Run Python scripts (e.g., Task Manager, CLI Calculator):
bash

Copy
python lab3/task_manager.py
For HTML/CSS/JavaScript Prototypes (Labs 5, 6, 10, 12):
Open HTML files (e.g., lab5/atm_simulator.html) in a browser like Chrome, or host them on a local server:
bash

Copy
python -m http.server 3000
Access at http://127.0.0.1:3000.
For Figma Prototypes:
Access wireframes and prototypes created in Figma for Labs 1, 11, and 13. (Note: Figma project links or files are not included in the repository; contact the author for access.)
Sign up for a free Figma account at figma.com to view or edit designs.
Usage
Python Scripts: Run scripts in lab3 or lab4 folders to interact with interfaces like the Task Manager or CLI Calculator.
HTML Prototypes: Open HTML files in lab5, lab6, lab10, or lab12 to explore interfaces like the food delivery app, ATM simulator, or food ordering website.
Figma Wireframes: Review wireframes for the food delivery app (Lab 11) or login screen (Lab 13) in Figma to understand user-centered design decisions.
Documentation: Each lab folder contains detailed reports (e.g., PDFs or text files) with explanations, screenshots, and theoretical insights.
Screenshots
Below are example outputs from the labs:

Food Delivery App (Lab 10):
Login Screen: Username/password input with a clean, responsive design.
Menu Screen: Grid-based food items with "Add to Cart" buttons.
Cart Screen: Displays selected items with remove options.
Student Attendance App (Lab 10):
Attendance Screen: Checkbox-based interface with automatic date/time display.
Issues-Evaluators Matrix (Lab 6):
HTML table with checkmarks for usability issues identified by evaluators.
Login Screen (Lab 13):
Blue-themed design (RGB: 0, 122, 255) ensuring accessibility and a trustworthy user experience.
Note: Screenshots are described based on lab outputs. If available, add image files to a /screenshots folder and reference them, e.g., ![Food Delivery App](screenshots/food_delivery.png).

References
Norman, D. (2013). The Design of Everyday Things.
Krug, S. (2014). Don't Make Me Think.
Dix, A., et al. Human-Computer Interaction.
Hughes, J. F., et al. Computer Graphics: Principles and Practice.
WCAG Guidelines for accessibility.
Online resources: Adobe Color, Coolors, Paletton, Figma tutorials.
Contributing
This repository is for educational purposes and represents coursework for the HCI-CG course. Contributions are not expected, but feedback or suggestions can be sent to farhanulhaq0013@gmail.com.

License
This project is licensed under the MIT License. See the LICENSE file for details.
