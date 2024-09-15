# CV Website - Sai Harsha Varma Sangaraju

This repository contains the source code for the CV website of **Sai Harsha Varma Sangaraju**. The website is built using **Django** with template inheritance to dynamically render different sections of the CV such as Education, Experience, Skills, Projects, and Achievements.

## Project Overview

This project is part of the **Software Engineering (CS-GY 6063)** course, Section I2, instructed by **Professor Raz Saremi** at **New York University**. The purpose of this assignment was to convert a CV into a website using Django's template.

### Project Structure

- **base.html**: This is the base template which includes common elements such as the header, contact info, and social links. All other templates extend this.
- **index.html**: The main page that includes the content of all sections by using Django's `{% include %}` template tag.
- **education.html**: Contains the Education section.
- **experience.html**: Contains the Experience section.
- **skills.html**: Contains the Skills section.
- **projects.html**: Contains the Projects section.
- **achievements.html**: Contains the Achievements section.

### How to Run

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/saiharshavarma/CV-website.git](https://github.com/saiharshavarma/Software-Engineering-Assignment-1-CV.git)
   cd Software-Engineering-Assignment-1-CV
   ```
2. **Set up a virtual environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # For Windows: env\Scripts\activate
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. ***Run the Django server***:
   ```bash
   python manage.py runserver
   ```
5. Visit http://127.0.0.1:8000 in your browser to view the website.
