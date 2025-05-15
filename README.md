# Personal Portfolio Website
This is a **Flask-based personal portfolio website**.
Hosted live on: [Render] https://my-portfolio-uags.onrender.com/ 
(GitHub Pages and Netlify don't support Python backend, so this site is deployed using Render.)

##  Features
The project consists of three main pages: Home, About, and Contact, all styled using custom HTML and CSS for a clean, responsive design.
The Flask backend handles routing for each page, while the frontend ensures a smooth user experience. This application is deployed using Render, a cloud platform that integrates directly with GitHub for seamless updates. It is served using Gunicorn and listens on the port automatically provided by Render.
For deployment, Render was used by linking the GitHub repository and setting the start command to gunicorn app:app. Render automatically detects the open port and deploys the service, making the application accessible online.

## Project Structure

portfolio/
├── static/
│ └── style.css # Custom CSS styles
├── templates/
│ ├── index.html # Home page
│ ├── about.html # About me
│ └── contact.html # Contact page
├── app.py # Flask backend
├── requirements.txt # Project dependencies

## Technologies Used

- **Frontend**: HTML5, CSS3
- **Backend**: Python Flask
- **Hosting**: Render
- **Web Server**: Gunicorn
