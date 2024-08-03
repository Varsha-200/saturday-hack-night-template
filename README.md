
![gitnotion](https://github.com/user-attachments/assets/079fdd2e-ba20-4a5b-9801-58448e81d8b9)




# Project Name
## Project Title: Resume Builder Based on GitHub Stats
### Overview
The "Resume Builder Based on GitHub Stats" is a web application that generates a resume using a user's GitHub activity. By simply entering a GitHub username, the app fetches real-time data from GitHub, including profile details, repositories, followers, and contributions, and organizes it into a professional resume format.

### Features
Easy to Use: Enter your GitHub username to instantly generate a resume.
Real-Time Data: Pulls the latest information directly from GitHub.
Comprehensive Summary: Includes profile details, GitHub stats, and top repositories.
Responsive Design: Styled with Bootstrap for a modern, mobile-friendly layout.
Customization: Easily tweak the layout with simple HTML and CSS edits.
### Benefits
This project is ideal for developers who want to quickly create a resume that highlights their open-source contributions. It saves time by automating data retrieval and formatting, ensuring the resume is always current and professionally presented.

### Technical Details
Backend: Built with Flask for efficient routing and GitHub API interaction.
Frontend: Utilizes Bootstrap for responsive and clean design.
Deployment: Easily deployable on platforms like Heroku or AWS.
### Conclusion
The "Resume Builder Based on GitHub Stats" is a powerful tool for developers looking to showcase their GitHub achievements. It's quick, efficient, and produces a polished resume that effectively highlights your contributions to the open-source community.


## Team members
1. Varsha S Panicker(https://github.com/TH-Activities/saturday-hack-night-template)
2. Nandana A(https://github.com/TH-Activities/saturday-hack-night-template)
## Link to product walkthrough
https://github.com/Varsha-200/saturday-hack-night-template/blob/4aafba676b2a5b035526e6d14b198343fb026329/GitHub%20Resume%20Builder%20Vedio
## How it Works ?
### 1. How It Works
The "Resume Builder Based on GitHub Stats" application is designed to generate a resume using a user's GitHub activity in a few simple steps:

#### User Input:

The user visits the application and is presented with a clean, user-friendly interface.
The user enters their GitHub username into a form and submits it.
#### Data Retrieval:

Upon submission, the backend (built with Flask) makes a request to the GitHub API using the provided username.
The application retrieves various details such as the user's profile information (name, bio, location), GitHub statistics (number of repositories, followers, following), and a list of the user's top repositories based on star count.
#### Data Processing:

The retrieved data is processed and organized into a structured format that will be displayed as a resume.
The top repositories are highlighted, showcasing the user’s most significant contributions to the GitHub community.
#### Resume Generation:

The data is then rendered into a beautifully styled HTML page using Bootstrap for the frontend.
The resume includes sections for the user’s profile, GitHub statistics, and a list of notable repositories, all neatly presented.
#### Viewing the Resume:

The user can view their resume directly on the application and share it with others.
The responsive design ensures that the resume looks great on all devices, from desktops to smartphones.
This process is designed to be efficient, allowing users to generate a professional-looking resume with minimal effort.

### 2. Embed video of project demo
https://github.com/Varsha-200/saturday-hack-night-template/blob/4aafba676b2a5b035526e6d14b198343fb026329/GitHub%20Resume%20Builder%20Vedio
## Libraries used
Flask - Version: 2.1.1
Requests - Version: 2.26.0
Bootstrap - Version: 5.3.0 (CDN)
## How to configure
Follow these steps to set up the "Resume Builder Based on GitHub Stats" project:

1. Prerequisites
Install Python (3.6+): python.org
Install Git (optional): git-scm.com
Install VS Code or another code editor: code.visualstudio.com

2. Clone the Project
git clone https://github.com/yourusername/resume-builder.git
cd resume-builder

3. Set Up Virtual Environment (Optional)
python -m venv venv
# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

4. Install Dependencies
pip install -r requirements.txt

5. Run the Application
python app.py

Access the app at http://127.0.0.1:5000/ in your browser.

6. Generate a Resume
Enter a GitHub username on the homepage and click "Generate Resume" to view the generated resume.

7. Stop the Server
Press CTRL+C in the terminal.
## How to Run

Follow these simple steps to run the "Resume Builder Based on GitHub Stats" project:

1. Open Your Terminal or Command Prompt
Navigate to the project directory:
cd path/to/resume-builder

2. Activate the Virtual Environment
If you have set up a virtual environment:

On Windows:
venv\Scripts\activate

Run the Flask Application
Start the Flask development server:
python app.py

You should see output indicating the server is running, such as:
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

4. Access the Application in Your Browser
Open your web browser and go to:
http://127.0.0.1:5000/

The homepage should load, where you can enter a GitHub username to generate a resume.

5. Stop the Application
When you're done, stop the Flask server by returning to your terminal and pressing:
CTRL+C

