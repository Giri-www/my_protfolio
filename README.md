# Django Portfolio

## Overview
This is a personal portfolio website built using Django. It showcases my projects, provides information about me, and allows visitors to contact me. The portfolio features a modern and attractive design with a responsive layout.

## Features
- **Home Page**: A welcoming section with an introduction and highlights.
- **Projects**: A showcase of my completed and ongoing projects.
- **About Us**: Details about my skills, experience, and background.
- **Contact Us**: A form for visitors to reach out to me.
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile views.
- **Modern UI/UX**: Uses a purple & blue theme with golden accents, smooth animations, and intuitive navigation.

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript (with animations)
- **Database**: MySQL
- **Deployment**: Hosted on Freehost

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-portfolio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-portfolio
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Apply migrations:
   ```bash
   python manage.py migrate
   ```
7. Run the development server:
   ```bash
   python manage.py runserver
   ```
8. Open your browser and visit `http://127.0.0.1:8000/`.

## Deployment
The portfolio is hosted on Freehost. To deploy:
1. Configure Freehost settings and upload your Django project.
2. Set up the MySQL database and update `settings.py` with the correct credentials.
3. Use a WSGI server like Gunicorn for production.

## Contact
For any inquiries or collaboration opportunities, feel free to reach out via the **Contact Us** section of the portfolio.

---

### License
This project is open-source and available for personal use. Contributions are welcome!

