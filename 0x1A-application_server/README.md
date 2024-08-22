Application Server

This project involved deploying our AirBnB clone. I set up Nginx on Holberton School's web servers to serve a WSGI Flask app using Gunicorn. I also implemented an Upstart script to ensure the app restarts automatically after server reboots.

# 0x1A-application_server Project by Ruth Temiloluwa Sobande <volunteerme2021@gmail.com>


Key Tasks:

- Development Setup: Configured 'web_flask/0-hello_route.py' to serve content at '/airbnb-onepage/' on port 5000.
  
- Production Setup: Installed and configured Gunicorn to serve the app in a production environment.

- Nginx Configuration: Created an Nginx config file to proxy requests to the Gunicorn app.

- Dynamic Routes: Added a route with query parameters, handled by Nginx and Gunicorn.

- API Deployment: Configured the AirBnB API to run on Gunicorn and be served by Nginx.

- Full Deployment: Deployed the complete AirBnB clone with Nginx serving static assets.

- Continuous Operation: Created a Bash script for seamless Gunicorn reloads, ensuring no downtime.