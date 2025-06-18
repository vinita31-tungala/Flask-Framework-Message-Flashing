📄 README.md
markdown
Copy
Edit
Flask Message Flashing App

This is a simple **Flask web application** that demonstrates how to use **message flashing** in Flask. Flash messages are used to show notifications like login success or error messages to the user.

📁 Project Structure

flask_message_flashing/
├── templates/
│ ├── index.html
│ └── log_in.html
├── venv/ # Virtual environment (not uploaded to GitHub)
└── flash.py # Main Flask application

markdown
Copy
Edit

 🚀 Features

- Login form with username and password.
- Flash message for:
  - Successful login.
  - Invalid login.
  - Reminder to log out.

 🛠 Requirements

- Python 3.x
- Flask

🔧 Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Create and activate a virtual environment:

bash
Copy
Edit
python -m venv venv
.\venv\Scripts\Activate.ps1    # PowerShell
 OR
venv\Scripts\activate.bat      # Command Prompt
Install Flask:

bash
Copy
Edit
pip install flask
Run the Flask app:

bash
Copy
Edit
python flash.py
Open your browser and go to:
👉 http://localhost:5000

📝 Default Credentials
Username: admin

Password: admin
