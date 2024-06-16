[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15250361&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   
Windows installation media. This could be an installation ISO or DVD.
USB flash drive with at least 5GB free space,ensure the flash disk has nothing important since it will be formatted.
Technician PC - Windows PC that you'll use to format the USB flash drive
Destination PC - A PC that you'll install Windows on


Step 1 - Format the drive and set the primary partition as active.

Connect the USB flash drive to your technician PC.
Open Disk Management: Right-click on Start and choose Disk Management.
Format the partition: Right-click the USB drive partition and choose Format. Select the FAT32 file system to be able to boot either BIOS-based or UEFI-based PCs.
Set the partition as active: Right-click the USB drive partition and click Mark Partition as Active.


Step 2 - Copy Windows Setup to the USB flash drive.

Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.
Optional: add an unattend file to automate the installation process. For more information, see Automate Windows Setup.




Step 3 - Install Windows to the new PC.

Connect the USB flash drive to a new PC.
Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.
Windows Setup starts. Follow the instructions to install Windows.
Remove the USB flash drive.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Setting up Visual Studio involves a few steps. Here's a concise step-by-step guide:
1. Download Visual Studio:
Visit the Visual Studio website and click on "Download Visual Studio."
Follow the on-screen instructions to download the installer.
2. Run the Installer:
Run the downloaded installer.
Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.
3. Select Workloads and Components:
In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Development" or "Web Development."
4. Modify Installation (Optional):
If needed, you can customize the installation by clicking on the "Individual components" tab in the installer and selecting or deselecting specific components.
5. Install:
Click the "Install" button to start the installation process.
This may take some time, as it involves downloading and installing the selected components.
6. Launch Visual Studio:
Once the installation is complete, launch Visual Studio.
Sign in with your Microsoft account or create one if prompted.
7. Choose Development Environment:
On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
8. Start Coding:
You're now ready to start coding! Create a new project or open an existing one to begin your development work.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Installing Git
1. Windows:
Download the Git installer from the official Git website.
Run the installer and follow the setup instructions. You can choose the default settings during the installation process.
Once the installation is complete, open Command Prompt or PowerShell and type git --version to verify the installation.
2. macOS:
Git should already be installed on macOS. Open the Terminal application and type git --version to check if it's installed.
If Git is not installed, you can install it via Homebrew (a package manager for macOS). Open Terminal and run.
3. Linux:
Use your distribution's package manager to install Git. For example, on Ubuntu or Debian, you can use: sudo apt update sudo apt install git.

Creating A GitHub Account:
1. Visit GitHub - go to Github in your browser.
2. Sign Up - Click on Sign up at the top right corner of the GitHub homepage. 
Fill in your desired username, email address and password.
Click on Create Account.
3. Verification - GitHub may ask you to complete a verfication step through your email address. Follow the instructions provided in the verfication email.
4. Welcome to GitHub - once verified, you'll be directed to the Github welcome page.

Setting Up Git Configuration:
After installing Git, configure your username and email address to be associated with Git commits:
Open a Terminal (or Git Bash on Windows); Run the following commands, replacing Your Name and your.email@example.com with your GitHub username and email address.

Create Your First Repository:
1. Create a New Repository on GitHub:
Log in to your GitHub account. Click on the + icon in the top right corner, then select New repository. Give your repository a name and optionally a description.
Choose whether your repository should be public or private. Click Create repository.
2. Clone Your Repository:
After creating a repository on GitHub, you can clone it to your local machine using the following commmand - git clone https://github.com/your-username/your-repository.git
Replace your-username with your GitHub username and your-repository with the name of your repository.
3. Start Working:
Add files, make changes, commit those changes, and push them back to Github using Git commands.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

1. Install Python
On Windows:
Download the Python installer from the official Python website.
Run the installer. Ensure you check "Add Python to PATH" before clicking "Install Now".
To verify the installation, open Command Prompt and type:
python --version

On macOS:
Open Terminal.
Use Homebrew to install Python:
brew install python

Verify the installation by typing:
python3 --version

On Linux:
For Debian-based distributions (like Ubuntu):
sudo apt update
sudo apt install python3 python3-pip

For Red Hat-based distributions (like Fedora):
sudo dnf install python3 python3-pip
For other distributions, use the package manager specific to your distribution.

Verify the installation by typing:
python3 --version

2. Install pip
pip is usually installed by default with Python. You can check if pip is installed and install it if it’s not:

On Windows:
Open Command Prompt and type:
python -m ensurepip --upgrade

On macOS and Linux:
Open Terminal and type:
python3 -m ensurepip --upgrade

Verify the pip installation:
pip --version
or
pip3 --version

3. Install Virtualenv (Optional but Recommended)
Using virtual environments to manage dependencies for different projects is a good practice.

Open your command line interface.
Install virtualenv:
pip install virtualenv

To create a virtual environment, navigate to your project directory and run:
virtualenv venv

Replace venv with your desired virtual environment name.
To activate the virtual environment:
On Windows:
.\venv\Scripts\activate
On macOS and Linux:
source venv/bin/activate

4. Install Other Languages and Runtimes (If Needed)
Java:
Install the JDK from the official Oracle website or use an open-source alternative like OpenJDK.
Verify the installation by typing:
java -version

Node.js (JavaScript/TypeScript):
Download and install Node.js from the official Node.js website.
Verify the installation by typing:
node -v
npm -v

Ruby:
Install Ruby using a version manager like RVM or from the official Ruby website.
Verify the installation by typing:
ruby -v
C/C++:

On Windows, install the MinGW compiler or use Visual Studio.
On macOS, install the Xcode Command Line Tools:
xcode-select --install
On Linux, install GCC:
sudo apt install build-essential
Verify the installation by typing:
gcc --version
g++ --version
Go:
Download and install Go from the official Go website.
Verify the installation by typing:
go version
5. Installing IDEs and Code Editors
Depending on your preference and the programming languages you use, you might want to install an Integrated Development Environment (IDE) or a code editor:

Visual Studio Code: A lightweight but powerful source code editor which supports many languages.

Download from the Visual Studio Code website.
PyCharm: An IDE specifically for Python development.

Download from the JetBrains website.
IntelliJ IDEA: A powerful IDE for Java, Kotlin, and other languages.

Download from the JetBrains website.
Eclipse: An IDE for Java and other languages.

Download from the Eclipse website.
Atom: A hackable text editor for the 21st century.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

  Installing Python
On Windows:

Download the Python installer from the official Python website.
Run the installer. Make sure to check the box that says "Add Python to PATH" before clicking "Install Now".
Follow the prompts to complete the installation.
To verify the installation, open Command Prompt and type:
python --version
On macOS:

Open Terminal.
Use Homebrew to install Python (if you don't have Homebrew installed, follow the instructions on the Homebrew website):
brew install python

To verify the installation, type:
python3 --version

On Linux:

For Debian-based distributions (like Ubuntu):
sudo apt update
sudo apt install python3
For Red Hat-based distributions (like Fedora):
sudo dnf install python3
For other distributions, use the package manager specific to your distribution.

To verify the installation, type:
python3 --version
Installing pip (Python Package Installer)
pip is usually installed by default with Python. You can check if pip is installed and install it if it's not:

On Windows:

Open Command Prompt and type:
python -m ensurepip --upgrade
On macOS and Linux:

Open Terminal and type:
python3 -m ensurepip --upgrade
Verifying pip Installation
To verify the pip installation, type:
pip --version
or
pip3 --version
Installing Virtualenv (Optional)
It is recommended to use virtual environments to manage dependencies for different projects. Here's how to install virtualenv:

Open your command line interface (Command Prompt, Terminal, etc.).
Run the following command to install virtualenv:
pip install virtualenv

To create a virtual environment, navigate to your project directory and run:
virtualenv venv

Replace venv with your desired virtual environment name.
To activate the virtual environment:
On Windows:
.\venv\Scripts\activate

On macOS and Linux:
source venv/bin/activate
Installing Packages with pip
To install packages with pip, use the following command:
pip install package_name
Replace package_name with the name of the package you want to install.

You've now installed Python, verified the installation, and learned how to use pip and virtualenv! 

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Downloading MySQL
1. Go to the official MySQL website.
2. Choose your operating system and download the MySQL installer.

Installing MySQL on Windows
1. Run the MySQL Installer that you downloaded.
2. Choose the setup type. For most users, the "Developer Default" setup type is recommended.
3. The installer will check for any missing prerequisites and offer to install them if necessary.
4. Choose the MySQL Server and any other MySQL products you want to install, then click "Next."
5. Configure the MySQL Server:
Choose a configuration type (e.g., "Development Machine" or "Server Machine").
Set the connectivity options, including the port number (default is 3306).
Configure the authentication method. It's recommended to use the "Use Strong Password Encryption" option.
Set the root password and create any additional user accounts you need.
6. Start the MySQL Server and apply the configuration settings.
7. Complete the installation and close the installer.
To verify the installation, open Command Prompt and type:
mysql --version

Installing MySQL on macOS

1. Open the downloaded DMG file and run the MySQL installer package.
2. Follow the prompts in the installer, including selecting a destination for the installation.
3. After installation, the MySQL preference pane will open in System Preferences. Here, you can start and stop the MySQL server.
4. Configure the MySQL Server:
Set the root password.
Configure any additional settings as needed.
To verify the installation, open Terminal and type:
mysql --version

Installing MySQL on Linux
On Debian-based distributions (like Ubuntu):
1. Update your package index:
sudo apt update
2. Install MySQL Server:
sudo apt install mysql-server
3. Run the MySQL Secure Installation to improve security:
sudo mysql_secure_installation
4. Follow the prompts to set the root password and remove anonymous users, disable root login remotely, and remove test databases.
To verify the installation, open Terminal and type:
mysql --version

On Red Hat-based distributions (like Fedora):
Add the MySQL repository:
sudo dnf install https://dev.mysql.com/get/mysql80-community-release-fc32-1.noarch.rpm
Install MySQL Server:
sudo dnf install mysql-server

Start and enable the MySQL service:
sudo systemctl start mysqld
sudo systemctl enable mysqld

Run the MySQL Secure Installation to improve security:
sudo mysql_secure_installation

Follow the prompts to set the root password and remove anonymous users, disable root login remotely, and remove test databases.
To verify the installation, open Terminal and type:
mysql --version

Setting Up MySQL Workbench (Optional)
MySQL Workbench is a unified visual tool for database architects, developers, and DBAs. It's optional but highly recommended for managing MySQL databases.

Download MySQL Workbench from the MySQL Workbench download page.
Install MySQL Workbench by following the installation instructions for your operating system.
Open MySQL Workbench and connect to your MySQL server using the root account credentials you set during the installation.
By following these steps, you'll have MySQL installed and running on your machine, and optionally, MySQL Workbench for managing your databases.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Using virtualization tools like Docker or virtual machines (VMs) is an excellent way to isolate project dependencies and ensure a consistent environment across different machines. Here's a guide to setting up and using Docker and VMs for your projects.

Docker
Docker is a platform that uses containerization to run applications in isolated environments. Containers are lightweight, portable, and ensure consistency across different environments.

Installing Docker
On Windows:

1. Download Docker Desktop from the official Docker website.
2. Run the installer and follow the setup instructions.
3. After installation, Docker Desktop will start automatically. You may need to log out and log back in to complete the setup.
4. Verify the installation by opening Command Prompt or PowerShell and typing:
docker --version

On macOS:

Download Docker Desktop from the official Docker website.
Open the downloaded .dmg file and drag Docker to the Applications folder.
Start Docker Desktop from the Applications folder.
Verify the installation by opening Terminal and typing:
docker --version

On Linux:
1. Update your package database:
sudo apt update
2. Install Docker using the convenience script provided by Docker:
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
3. Add your user to the docker group to run Docker without sudo (you may need to log out and log back in for this change to take effect):
sudo usermod -aG docker $USER
4. Verify the installation by typing:
docker --version

Using Docker
Creating a Dockerfile:
Create a Dockerfile in your project directory. This file defines your application environment. Here’s an example for a Python application:

Dockerfile
# Use the official Python image from the Docker Hub
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Run app.py when the container launches
CMD ["python", "app.py"]
Building and Running the Docker Container:
Open a terminal in the directory containing your Dockerfile and run:
docker build -t my-python-app .
docker run -p 4000:80 my-python-app

Using Docker Compose:
Docker Compose allows you to define and run multi-container Docker applications. Create a docker-compose.yml file:
version: '3'
services:
  web:
    build: .
    ports:
      - "4000:80"
    volumes:
      - .:/app
    environment:
      - FLASK_ENV=development
Then run:
docker-compose up
Virtual Machines
Virtual Machines provide a full-fledged environment with its own operating system, running on top of your existing OS. Tools like VirtualBox or VMware are popular choices for creating VMs.

Using VirtualBox
Download and Install VirtualBox:
Download VirtualBox from the official VirtualBox website and follow the installation instructions for your OS.

Create a New VM:

Open VirtualBox and click "New".
Follow the prompts to create a new VM, choosing the OS type and version, allocating memory, and creating a virtual hard disk.
Install the OS:

Start the VM and provide the installation media (ISO file) for the OS you want to install.
Follow the OS installation instructions.
Install Guest Additions:

After installing the OS, install VirtualBox Guest Additions for better performance and additional features.
Go to "Devices" > "Insert Guest Additions CD image…" and follow the installation instructions inside the VM.
Setting Up the Development Environment:

Install the necessary programming languages, tools, and dependencies inside the VM as you would on a physical machine.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Visual Studio Code (VS Code)
Extensions:

Syntax Highlighting:

Python: Python Extension for Visual Studio Code
JavaScript/TypeScript: JavaScript and TypeScript Nightly
HTML/CSS: HTML CSS Support
Linting:

ESLint: ESLint
Pylint: Python Extension (includes Pylint)
Flake8: Python Extension (supports Flake8)
Code Formatting:

Prettier: Prettier - Code formatter
Black (for Python): Python Extension (supports Black)
Version Control Integration:

Git: GitLens
GitHub: GitHub Pull Requests and Issues
PyCharm
Plugins:

Syntax Highlighting:

PyCharm comes with built-in support for Python syntax highlighting.
For other languages, you can install plugins from the JetBrains plugin repository.
Linting:

Pylint: Pylint
Flake8: Configure Flake8 in the project settings (Preferences > Tools > External Tools).
Code Formatting:

Black: Install Black and configure it in the project settings (Preferences > Tools > External Tools).
Prettier (for web development): Prettier
Version Control Integration:

PyCharm has built-in support for Git, GitHub, and other version control systems.
GitToolBox: GitToolBox enhances Git integration with additional features.
IntelliJ IDEA
Plugins:

Syntax Highlighting:

IntelliJ IDEA has built-in support for many languages.
For additional languages, check the JetBrains plugin repository.
Linting:

ESLint: ESLint
Pylint: Pylint
Code Formatting:

Prettier: Prettier
Black: Configure Black in the project settings (Preferences > Tools > External Tools).
Version Control Integration:

IntelliJ IDEA has built-in support for Git, GitHub, and other version control systems.
GitToolBox: GitToolBox
Atom
Packages:

Syntax Highlighting:

language-python: language-python
language-javascript: language-javascript
language-html: language-html
Linting:

linter: linter
linter-eslint: linter-eslint
linter-flake8: linter-flake8
Code Formatting:

prettier-atom: prettier-atom
atom-beautify: atom-beautify
Version Control Integration:

git-plus: git-plus
github: github
Sublime Text
Packages:

Syntax Highlighting:

Python: Built-in support, additional features with Anaconda
JavaScript/TypeScript: Babel
HTML/CSS: Built-in support
Linting:

SublimeLinter: SublimeLinter
SublimeLinter-contrib-eslint: SublimeLinter-contrib-eslint
SublimeLinter-flake8: SublimeLinter-flake8
Code Formatting:

JsPrettier: JsPrettier
Black (for Python): Install Black and configure it to run as an external command.
Version Control Integration:

GitGutter: GitGutter
Git: Git

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

   Comprehensive Guide to Setting Up Your Developer Environment
This document outlines the steps taken to set up a developer environment, including the installation of necessary tools, configurations, customizations, and troubleshooting steps encountered.

Table of Contents
1. Introduction
2. Installing Python
3. Installing MySQL Database
4. Virtualization Tools
5. Enhancing Your Text Editor or IDE
6. Summary

Introduction
Setting up a robust and flexible developer environment is essential for productivity and consistency across different machines and projects. This guide will help you install and configure essential tools, including Python, MySQL, Docker, and popular text editors or IDEs like Visual Studio Code, PyCharm, IntelliJ IDEA, Atom, and Sublime Text.

Installing Python
Windows
Download and Install:
Download the Python installer from the official Python website.
Run the installer. Ensure you check "Add Python to PATH" before clicking "Install Now".
Verify the installation by opening Command Prompt and typing:
python --version

macOS
Install with Homebrew:
Open Terminal.
Install Python using Homebrew:
brew install python

Verify the installation:
python3 --version

Linux
Debian-based distributions (like Ubuntu):
sudo apt update
sudo apt install python3 python3-pip
Red Hat-based distributions (like Fedora):
sudo dnf install python3 python3-pip

Verify the installation:
python3 --version
Installing pip
pip is usually installed by default with Python. Verify and install pip if needed:
pip --version
or
pip3 --version

Installing Virtualenv (Optional but Recommended)
Install Virtualenv:
pip install virtualenv

Create and Activate a Virtual Environment:
virtualenv venv
# Activate:
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
Installing MySQL Database
Windows
Download and Install:
Download the MySQL Installer from the official MySQL website.
Run the installer and follow the setup instructions, choosing the "Developer Default" setup type.
Configure the MySQL Server, set the root password, and create any additional user accounts.
Verify the installation by opening Command Prompt and typing:
mysql --version

macOS
Download and Install:
Open the downloaded DMG file and run the MySQL installer package.
Set the root password and configure any additional settings.
Verify the installation by opening Terminal and typing:
mysql --version

Linux
Debian-based distributions (like Ubuntu):
sudo apt update
sudo apt install mysql-server
sudo mysql_secure_installation

Red Hat-based distributions (like Fedora):
sudo dnf install mysql-server
sudo systemctl start mysqld
sudo systemctl enable mysqld
sudo mysql_secure_installation

Verify the installation:
mysql --version
Using Virtualization Tools
Docker
Installing Docker:

Windows and macOS:

Download Docker Desktop from the official Docker website.
Run the installer and follow the setup instructions.
Verify the installation:
docker --version

Linux:

Install Docker using the convenience script:
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker $USER
Using Docker:

Create a Dockerfile for your application.

Build and run the Docker container:
docker build -t my-python-app .
docker run -p 4000:80 my-python-app
Using Docker Compose:

Create a docker-compose.yml file:
version: '3'
services:
  web:
    build: .
    ports:
      - "4000:80"
    volumes:
      - .:/app
    environment:
      - FLASK_ENV=development
Run:
docker-compose up
Virtual Machines
Using VirtualBox:

Download and Install VirtualBox:

Download from the official VirtualBox website.
Follow the installation instructions.
Create and Configure a VM:

Open VirtualBox and click "New".
Follow the prompts to create a new VM, selecting the OS type and version, allocating memory, and creating a virtual hard disk.
Install the OS using the installation media.
Install Guest Additions for Enhanced Performance:

Go to "Devices" > "Insert Guest Additions CD image…" and follow the installation instructions.
Set Up Development Environment:

Install necessary tools and dependencies within the VM.
Enhancing Your Text Editor or IDE
Visual Studio Code (VS Code)
Extensions:
Python: Python Extension for Visual Studio Code
ESLint: ESLint
Prettier: Prettier - Code formatter
GitLens: GitLens
GitHub: GitHub Pull Requests and Issues
PyCharm
Plugins:
Pylint: Pylint
Prettier: Prettier
GitToolBox: GitToolBox
IntelliJ IDEA
Plugins:
ESLint: ESLint
Pylint: Pylint
Prettier: Prettier
GitToolBox: GitToolBox
Atom
Packages:
language-python: language-python
linter: linter
prettier-atom: prettier-atom
git-plus: git-plus
github: github
Sublime Text
Packages:
Anaconda (Python): Anaconda
SublimeLinter: SublimeLinter
JsPrettier: JsPrettier
GitGutter: GitGutter 

#Deliverables:
- DoScument detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
