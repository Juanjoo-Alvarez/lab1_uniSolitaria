# The Abandoned University – Choose Your Own Adventure

## Description

**The Abandoned University** is a *Choose Your Own Adventure* (COYA) interactive story developed using only HTML.  
The story follows a student who arrives late to their university and discovers that the campus is completely abandoned.  
Throughout the game, the player must make decisions that lead to different paths and multiple endings.

This project was created as part of an academic laboratory focused on HTML navigation and web hosting using NGINX.

---

## How the Game Works

- The story is divided into multiple HTML pages.
- Each page presents part of the narrative and **at least two decisions**.
- All decisions are made exclusively using HTML links (`<a>` tags).
- Each decision leads to a completely different page.
- The story has **three distinct endings**:
  - **Good Ending** – The truth is revealed.
  - **Neutral Ending** – The player escapes without answers.
  - **Bad Ending** – The player is lost inside the university.

There is **no use of JavaScript or CSS**.  
All interaction is handled through basic HTML navigation.

---


- No HTML files are located in the root directory.
- HTML files are organized by narrative purpose.
- Images are stored separately.

---

## Requirements

- Web browser (Chrome, Firefox, etc.)
- NGINX
- UNIX terminal or WSL (Windows Subsystem for Linux)

---

## How to Run the Project with NGINX

1. Install NGINX:
   ```bash
   sudo apt update
   sudo apt install nginx

2. Copy the project folder into the NGINX web directory:

    sudo cp -r  /var/www/html/Lab1 \ HTML


3. Start or restart NGINX:

    sudo systemctl restart nginx


4. Open a browser and go to:

    http://127.0.0.1/Lab1%20HTML/inicio/index.html


5. Navigate the story by clicking the links

## Author

    Juan José Rivas Álvarez
    Computer Science Engineering Student
