[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15248599&assignment_repo_type=AssignmentRepo)
Names: HAKUZWIMANA Silas
Email: hakusilas@gmail.com 
Date: On Monday, June 17th,2024

DEV_SETUP
Assignment: Setting up your development environment.
#Objective: This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

1. Select Your Operating System (OS)
Since you already have Windows 11 Home Single Language installed, we can skip the installation of the OS.
2. Install a Text Editor or Integrated Development Environment (IDE)
We'll install Visual Studio Code (VS Code), which is a popular and powerful code editor.
Steps:
1.	Download Visual Studio Code:
	Go to Visual Studio Code Download via https://code.visualstudio.com/Download.
	Download the Windows installer.

2.	Install Visual Studio Code:
	Run the downloaded installer.
	Follow the setup instructions and complete the installation.
3. Set Up Version Control System
We'll install Git and create a GitHub account for version control.
Steps:
1.	Download and Install Git:
	Go to Git for Windows via https://git-scm.com/download/win.
	Download the installer and run it.
	Follow the installation instructions, selecting the default options.

2.	Configure Git:
	Open Git Bash (installed with Git); It is recommended to open or run it with an administrator privilege to avoid any denial of services needed.
	Set your username and email:



3.	Create a GitHub Account:
	Go to GitHub via https://github.com/.
	Sign up for a new account.

4.	Initialize a Git Repository:
	Create a new folder for your project.
	Open Git Bash in that folder and run:

5. Install Necessary Programming Languages and Runtimes
We'll install Python.
Steps:
1.	Download and Install Python:
	Go to Python Downloads via https://www.python.org/downloads/.
	Download the latest Python installer for Windows.
	Run the installer, making sure to check the "Add Python to PATH" option.
	Follow the installation instructions.
2.	Verify Python Installation:
Open Command Prompt and run:
Run the code:
python --version
pip --version
3.	Install Package Managers
Pip is already installed with Python, so you’re all set here.

6. Configure a Database (MySQL)
We'll install MySQL.
Steps:
1.	Download and Install MySQL:
	Go to MySQL Installer via https://dev.mysql.com/downloads/windows/installer/5.7.html.
	Download the installer and run it.
	Choose the setup type (Developer Default is recommended).
	Follow the installation instructions.

2.	Configure MySQL:
	During installation, you’ll be prompted to configure MySQL. Set a root password and create a new user if needed.
	Complete the installation.

7. Set Up Development Environments and Virtualization (Using Virtual Environments)
Steps:
1.	Install virtualenv:
o	Open Command Prompt and install virtualenv using pip:
Run the code:

pip install virtualenv
2.	Create a Virtual Environment:
o	Navigate to your project directory:
Run the code:

Cd C:\DjangoMayProject
o	Create a virtual environment. Replace env with the desired name for your virtual environment:
Run the code:

virtualenv mayproject/(virtual env name).
3.	Activate the Virtual Environment:
o	On Windows, activate the virtual environment:
Run the code:

source mayproject/Scripts/activate
o	Once activated, your command prompt should change to indicate you are now working within the virtual environment.
4.	Install Project Dependencies:
o	Install any necessary packages within the virtual environment. For example:
	Run code

	   pip install numpy pandas
o	You can create a requirements.txt file to list all the dependencies:
Run code

pip freeze > requirements.txt
5.	Deactivate the Virtual Environment:
o	When you're done working, deactivate the virtual environment:
Run code

deactivate
6.	Using the Virtual Environment in VS Code:
o	Open your project folder in VS Code.
o	Open the Command Palette (Ctrl+Shift+P) and type Python: Select Interpreter.
o	Select the interpreter from your virtual environment (it should appear in the list with the path to env).
8. Explore Extensions and Plugins
Enhance your VS Code with useful extensions.
•	 Recommended Extensions:
	Python: For Python development.
	GitLens: Supercharges the Git capabilities in VS Code.
	Prettier: Code formatter.
	ESLint: Integrates ESLint for JavaScript/TypeScript.
Steps:
•	Install Extensions:
•	Open VS Code.
•	Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
•	Search for and install the extensions mentioned above.

10. Reflection on the challenges.
Common Challenges and Solutions
1.	Installation Issues:
   o	Problem: Installation failures due to missing dependencies or incompatible versions.
   o	Solution: Carefully read installation documentation and ensure all prerequisites are met. Use installation logs and error messages to troubleshoot specific issues. Searching online forums and documentation can also help resolve specific errors.
2.	Configuration Problems:
   o	Problem: Incorrect configuration settings for tools like Git, Python, or VS Code.
   o	Solution: Double-check configuration steps in official documentation. If settings are complex, consider using step-by-step guides or tutorials. Validate configurations by running small test commands to ensure they work as expected.
3.	Environment Variables:
   o	Problem: Misconfigured environment variables leading to command not found errors or incorrect paths.
   o	Solution: Ensure environment variables like PATH are correctly set. For instance, make sure Python and Git paths are added to the PATH environment variable during installation.
4.	Virtual Environment Issues:
   o	Problem: Issues activating or using the virtual environment.
   o	Solution: Verify you are in the correct directory and that the virtual environment is correctly created. Use the full path to the activate script if necessary. Reinstall virtualenv if issues persist.
5.	Version Control Conflicts:
   o	Problem: Merge conflicts or issues with remote repositories in Git.
   o	Solution: Learn and use Git commands like git status, git diff, and git log to understand the current state of your repository. For merge conflicts, carefully read conflict markers and resolve issues manually.
6.	Dependency Management:
   o	Problem: Conflicts between package versions or missing dependencies.
   o	Solution: Use a requirements.txt file to manage dependencies. Run pip install -r requirements.txt to ensure all required packages are installed. Consider using virtual environments to isolate project dependencies.
7.	Database Configuration:
   o	Problem: Issues installing or configuring MySQL.
   o	Solution: Follow the official MySQL installation guide carefully. Use MySQL Workbench or command-line tools to test the connection and configuration. Ensure the MySQL service is running and accessible.
8.	IDE Configuration:
   o	Problem: Extensions or plugins not working as expected in VS Code.
   o	Solution: Make sure extensions are compatible with your VS Code version. Check extension settings and configurations. Restart VS Code after installing extensions to ensure they load correctly.
9.	Permissions Issues:
   o	Problem: Lack of proper permissions to execute certain commands or access files.
   o	Solution: Run the command prompt or terminal as an administrator when necessary. Adjust file and directory permissions using Windows security settings.
10.	Understanding New Tools:
   o	Problem: Difficulty understanding or using new tools and technologies.
   o	Solution: Invest time in reading official documentation and tutorials. Practice using the tools with small, manageable projects before integrating them into larger workflows.

   The link to my sample project is: https://github.com/SilasHakuzwimana/PLPDjangoMayProject/tree/main/my_flutter_app
   
   Main link:
   https://github.com/SilasHakuzwimana/PLPDjangoMayProject


