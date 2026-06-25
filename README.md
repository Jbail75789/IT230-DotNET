# IT230-DotNET
# Computer Science Portfolio - C#.NET Development

Welcome to my computer science development portfolio. This repository houses software applications developed as part of my academic coursework, focusing on object-oriented programming, graphical user interface (GUI) design, and software engineering principles using C# and the .NET framework.

## Featured Project: WPF Student Registration Application

An interactive Windows Presentation Foundation (WPF) desktop application that simulates a student course registration system. This project transitions functional backend console logic into a modern, event-driven graphical user interface.

### Key Features
* **Dynamic UI Controls:** Utilizes WPF ComboBoxes, ListBoxes, Labels, and TextBoxes to manage user selections and instantly reflect system updates.
* **Robust Input Validation:** Implements data validation logic within event handlers to ensure selections map accurately to system rules.
* **Business Logic Enforcement:** Incorporates Boolean logic and flow control loops to strictly enforce course limits:
  * Restricts duplicate registration for identical courses.
  * Caps maximum student workload to 9 credit hours (3 courses total).
* **Automated Mathematical Computations:** Programmatically tracks, aggregates, and updates cumulative credit hour variables upon successful registration confirmation.

### Technologies Used
* **Language:** C#
* **Framework:** .NET / WPF (Windows Presentation Foundation)
* **IDE:** Visual Studio

📘 Final Project Reflection
1. Application Requirements and Goals
The goal of this application was to create a student course registration system. It was designed to help users easily select courses, prevent them from accidentally signing up for the same class twice, and make sure they don’t exceed the maximum limit of 9 credit hours (3 courses total). It addresses the user's need for an error-free, simple way to manage an academic schedule.

2. What I Did Well
I think I did particularly well with the logic that handles the math and checks for duplicates. Making sure the system instantly updates the total credit hours and blocks a user from adding a class they are already taking worked smoothly and prevents data errors.

3. Console vs. WPF Application Designs
The Console version was purely text-based, which required the user to type commands perfectly into a black box. The WPF version turned that into a visual interface with dropdown menus (ComboBoxes) and lists (ListBoxes). The visual UI is much more user-centered because it keeps users from making typing typos and lets them see their current schedule update in real time. It was successful because it is intuitive and requires no technical knowledge to use.

4. Debugging and Coding Approach
My approach was to work in small steps. I would write one small piece of logic, test it to see if it worked, and fix any errors before moving on to the next feature. I used Visual Studio’s error list constantly to track down typos or syntax issues. In the future, I will keep using this step-by-step testing method because it stops small bugs from turning into giant problems later on.

5. Overcoming Challenges with Innovation
I had to be innovative when figuring out how to pass data between the user controls and the backend logic—specifically making sure the application correctly recognized which course object was being clicked in the dropdown menu. I overcame this by learning how to properly cast the selected items so the program understood exactly what data it was looking at.

---
*Created by Michael Bailey as part of IT-230: Software Development with C#.NET.*
