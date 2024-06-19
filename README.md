[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15296525&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

In order to upgrade to Windows 11, your computer must meet Windows 11 minimum requirements and should be running the most up-to-date Windows 10 version. If this is not the case, it may be best to consider moving to a Windows-11-compatible device.

Microsoft’s official minimum Windows 11 system requirements include:

●     CPU: 1 GHz with two or more cores on a 64-bit processor
●     Memory: 4 GB
●     Display: Measures 9 inches diagonally and high definition (720 p)
●     Storage: 64 GB
●     Graphics Card: DirectX 12 with WDDM 2.0 driver compatibility
●     Security: TPM 2.0, UEFI, Secure Boot
●     RAM: 4 GB
If your device does not meet these Windows 11 minimum system requirements, installation of Windows 11 could result in compatibility issues and malfunctioning, and your manufacturer’s warranty will not cover any damage to incompatible devices. Moreover, Microsoft does not provide Windows 11 support for devices that do not meet these minimum requirements. This puts you at risk, since you may not be able to get important security updates, for example. Installation in such cases is therefore not recommended.
![alt text](Capture.PNG)
Windows 10 users can check whether their devices are compatible and meet the minimum requirements using the PC Health Check App. Despite the name, it is important to note that the app only indicates whether your device is -compatible with Windows 11; it doesn’t report the overall health of your computer.
my laptop did not meet the requirements in order to intall windows 11 but typically after the laptop health check is then you proceed to install windows 11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
-once the link is clicked it directs you to visualstudio webpage
-click on for windows when using windows then VS setup will start downloading 
-when downloading is completed the VS setup will be located on the downloaded file.
-Once the installer launches, step through the installation process. First, accept the License
Agreement, then click Next >.![alt text](<vs code.PNG>)
-Accept the default location for installation by clicking Next >.
-Optionally check the boxes for 'Creating a desktop icon', and adding VS Code to the Right-
Click menu functionality of Windows File Explorer, then click Next >.
-Confirm the installation options, then click Install.
-The installation will proceed.
Click Finish to exit the installation and (by default) launch Visual Studio Code
-The Visual Studio Code installer will create an icon in the ⊞ Start Menu. To locate it, click on
the Start Menu and search for 'Code':
-Visual Studio Code will launch.
-which the application when opened will be welcomed with the welcome message and on the left side of the application that is where the menu is with different icons![alt text](image.png)
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Install Git for windows:
   -Download the Git installer from Git for Windows.
    -Run the installer and follow the instructions.
    -After installing Git, you need to set your Git username and email. These are used to identify the author of the commits
    -Open Terminal (or Git Bash on Windows) and run the following commands:
    git config --global user.name "Your Name" git config --global user.email "your-email@example.com"
    - Create a GitHub Account
    -Click on "Sign up" and follow the instructions to create a new account.
    -Open Terminal (or Git Bash on Windows).
    -Navigate to your project directory:
      cd /path/to/your/project
   -Initialize a new Git repository:
    git init
    -Add your project files to the staging area:
    git add .
    -Commit the files to the repository:
    git commit -m "my first commit"
    Push to GitHub
   Create a new repository on GitHub:
  -Go to your GitHub account.
  -Click on the "New" button to create a new repository.
  -Fill in the repository name, description (optional), and choose visibility (public or private).
Click on "Create repository".
Link your local repository to the GitHub repository:
git remote add origin https://github.com/your-username/your-repository-name.git
Push your commits to GitHub:
git push -u origin master
Your project is now hosted on GitHub. You can view it by navigating to https://github.com/your-username/your-repository-name in your web browser.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Install Python for Windows:
Go to the Python Downloads page.
-Download the latest Python installer for Windows.
-Run the installer. Make sure to check the box that says "Add Python to PATH" before clicking "Install Now."

Verify Python Installation
To verify that Python has been installed correctly, open your terminal (or Command Prompt/PowerShell on Windows) and type:
-python --version

 Install pip
pip is the package installer for Python and should be included with the Python installation. Verify its installation by typing:
-pip --version

 Install Necessary Tools and Libraries
Depending on your project requirements, you might need to install additional libraries. You can do this using pip. For example, to install the requests library, you would run:
-pip install requests
Set Up a Virtual Environment (Optional but Recommended)
Using a virtual environment can help manage dependencies for different projects. To create and activate a virtual environment:
-python -m venv env
Windows:
.\env\Scripts\activate
 Install Project-Specific Dependencies
With the virtual environment activated, install the necessary dependencies listed in your requirements.txt file (if you have one):
pip install -r requirements.txt
Run Your Python Code
You can now run your Python code using:
python your_script.py
Install Package Managers:
-If applicable, install package managers like pip (Python).
   Verify if pip is Already Installed
pip usually comes bundled with Python installations. To check if pip is already installed, open your terminal (or Command Prompt/PowerShell on Windows) and type:
-pip --version
Install pip (if not already installed)
For Windows/macOS/Linux:
If pip is not installed, you can use the following method to install it.
Download get-pip.py from the official source using curl:
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Or you can download it directly from your browser here.
Run the script to install pip:
-python get-pip.py

6. Configure a Database (MySQL):
  Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

For Windows:
Download MySQL Installer:
Go to the MySQL Community Downloads page.
Download the MySQL Installer for Windows.

Run the Installer:
Run the downloaded mysql-installer-web-community-X.X.X.X.msi file.
Choose the setup type. For a typical installation, select "Developer Default" or "Full" to install MySQL Server, MySQL Workbench, and other components.
Follow the prompts to complete the installation. During the setup, you will be asked to configure the MySQL Server, including setting a root password and configuring the MySQL Server as a service.

Configure MySQL:
Follow the configuration steps, including setting up the MySQL root password, creating user accounts, and selecting the server configuration.
After installation, the MySQL server will start automatically. You can manage it using the MySQL Workbench or MySQL command-line client.
7. Set Up Development Environments and Virtualization (Optional):
Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Using Docker
Docker is a containerization platform that allows you to package applications and their dependencies into lightweight containers. This ensures that your application runs consistently across different environments, from development to production.

Steps to Integrate Docker:
Install Docker:
Download and install Docker Desktop for your operating system from Docker Hub.
Create a Dockerfile for Your Application:
Define the environment and dependencies needed for your application using a Dockerfile. Here’s a basic example for a Python application:

dockerfile
Copy code
# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
Build the Docker Image:

Navigate to your project directory containing the Dockerfile and build the Docker image:
docker build -t my-python-app .

Run Your Docker Container:
Start a Docker container based on the image you built:
docker run -p 4000:80 my-python-app
This command runs your container on port 4000, mapping it to port 80 inside the container.

Share Docker Image:
You can push your Docker image to Docker Hub or another container registry to share it with others or deploy it to a server.
Benefits of Using Docker:
Isolation: Each container has its own dependencies, ensuring consistency and preventing conflicts with other projects.
Portability: Containers can run on any system that supports Docker, ensuring your application behaves the same way everywhere.
Reproducibility: Docker images are defined by a Dockerfile, making it easy to recreate and share environments.
Using Virtual Machines
Virtual machines (VMs) provide complete virtualized environments, including an operating system, within a host system. This approach is useful for projects that require different operating systems or configurations.

Steps to Use Virtual Machines:
Install a Virtualization Tool:
Examples include VirtualBox or VMware Workstation.
Create a Virtual Machine:
Create a new VM and install the desired operating system (e.g., Ubuntu, Windows) and development tools.
Snapshot or Template Creation:
Create snapshots or templates of your VMs to quickly replicate them for new projects or when testing different configurations.
Share or Clone VMs:
Export VMs as OVF/OVA files or clone them to distribute or deploy on other machines.
Benefits of Using Virtual Machines:
Full Environment: VMs provide complete isolation, allowing you to configure and use different operating systems or versions.
Flexibility: Easily clone or migrate VMs between different host systems.
Security: VMs can be sandboxed, enhancing security by isolating potentially vulnerable environments.
Integration into Developer Environment Setup
Choose Based on Project Requirements: Select Docker for lightweight, consistent environments across platforms. Choose VMs for full OS isolation and specific configuration needs.
Automate Setup with Infrastructure as Code: Use tools like Docker Compose or Vagrant to automate the setup of multi-container Docker applications or VM environments.
Document Configuration: Document Dockerfiles or VM configurations to ensure team members can replicate the environment easily.

8. Explore Extensions and Plugins:
  Choosing the right extensions, plugins, and add-ons can significantly enhance the functionality of your text editor or Integrated Development Environment (IDE). Below are some of the most popular text editors and IDEs, along with recommended extensions for various functionalities like syntax highlighting, linting, code formatting, and version control integration.

Visual Studio Code (VS Code)
Extensions for VS Code:
Syntax Highlighting and Language Support:
Python: Python
JavaScript/TypeScript: JavaScript (ES6) code snippets
HTML/CSS: HTML CSS Support
Linting:
ESLint: ESLint
Pylint: Included with the Python extension above, but can be configured separately.
Code Formatting:

Prettier: Prettier - Code formatter
Version Control Integration:
GitLens: GitLens — Git supercharged
Other Useful Extensions:
Live Server: Live Server
Docker: Docker
PyCharm
Plugins for PyCharm:
Syntax Highlighting and Language Support:
Python: Built-in support
Markdown: Markdown
Linting:
Pylint: Pylint
Code Formatting:
Prettier: Prettie

Version Control Integration:
Git: Built-in support
GitToolBox: GitToolBox
Other Useful Plugins:

Docker: Docker
Sublime Text
Packages for Sublime Text:
Syntax Highlighting and Language Support:
Python: Anaconda
JavaScript: Babel
Linting:
SublimeLinter: SublimeLinter
SublimeLinter-pylint: SublimeLinter-pylint
Code Formatting:

AutoPEP8: SublimeAutoPEP8
Prettier: JsPrettier
Version Control Integration:

GitGutter: GitGutter
Other Useful Packages:
Package Control: Package Control
SideBarEnhancements: SideBarEnhancements

Atom
Packages for Atom:
Syntax Highlighting and Language Support:
Python: python-language-server
JavaScript: atom-typescript
Linting:
Linter: linter
Linter Pylint: linter-pylint
Code Formatting:

Prettier: prettier-atom
Version Control Integration:

Git Plus: git-plus
Other Useful Packages:

PlatformIO IDE Terminal: platformio-ide-terminal
file-icons: file-icons
Installing Extensions/Plugins/Add-ons
For VS Code:

Press Ctrl+Shift+X or Cmd+Shift+X to open the Extensions view.
Search for the desired extension and click Install.
For PyCharm:
Go to File > Settings > Plugins.
Search for the desired plugin and click Install.
For Sublime Text:
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Install Package and select Package Control: Install Package.
Search for the desired package and install it.
For Atom:
Go to Edit > Preferences > Install.
Search for the desired package and click Install.
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Developer Environment Setup Guide
Table of Contents
System Requirements
Installing Essential Software
2.1. Operating System Updates
2.2. Text Editor or IDE Installation
2.3. Version Control System
2.4. Programming Languages and Runtimes
2.5. Database Management System
2.6. Other Tools and Utilities
Configuring Tools
3.1. Text Editor or IDE Configurations
3.2. Version Control Integration
3.3. Setting Up SSH Keys (if applicable)
3.4. Configuring Environment Variables
Installing and Managing Dependencies
4.1. Package Managers Setup
4.2. Virtual Environments (if applicable)
Customizations and Extensions
5.1. Text Editor or IDE Extensions
5.2. Plugins and Add-ons

Testing the Setup
Troubleshooting Common Issues
Next Steps and Additional Resources

System Requirements
Before starting the setup process, ensure your system meets the following requirements:
Adequate RAM and disk space for development tools and projects.
Internet connectivity for downloading software and updates.
Compatibility with the operating system (Windows, macOS, Linux).

2. Installing Essential Software
2.1. Operating System Updates
Windows:
Ensure Windows is up to date by installing the latest updates through Settings > Update & Security.
macOS:
Update macOS to the latest version by going to the Apple menu > System Preferences > Software Update.
Linux (Debian/Ubuntu):
Update the package index and upgrade installed packages using:
sudo apt upgrade

2.2. Text Editor or IDE Installation
Choose and install a suitable text editor or Integrated Development Environment (IDE) based on your preferences and project requirements:

Visual Studio Code: Download from VS Code.
PyCharm: Download from JetBrains.
Sublime Text: Download from Sublime Text.
Atom: Download from Atom.
2.3. Version Control System
Install a version control system to manage your project's source code:
Git: Download from Git and follow installation instructions for your operating system.

2.4. Programming Languages and Runtimes
Install programming languages and their respective runtimes required for your projects:
Python: Download from Python (ensure to add to PATH during installation on Windows).
Node.js: Download from Node.js (includes npm for package management).
Java: Download from Java (JDK for Java development).

2.5. Database Management System
Install a database management system (DBMS) for storing and managing data:
MySQL: Download from MySQL and follow installation instructions specific to your operating system.

2.6. Other Tools and Utilities
Install additional tools and utilities depending on your project requirements:
Docker: Download from Docker for containerization.
Postman: Download from Postman for API development and testing.
IDE Plugins: Install plugins or extensions for your chosen IDE or text editor to enhance functionality (e.g., linting, debugging).

3. Configuring Tools
3.1. Text Editor or IDE Configurations
Configure your text editor or IDE settings according to your preferences:
Set themes, font sizes, and color schemes.
Configure keyboard shortcuts for efficient coding.
Enable extensions or plugins for syntax highlighting, code completion, and debugging.

3.2. Version Control Integration
Integrate Git with your IDE or text editor:
Set up Git credentials (name, email) using git config --global user.name "Your Name" and git config --global user.email "your-email@example.com".
Link your IDE to Git repositories or configure SSH keys for secure access.

3.3. Setting Up SSH Keys (if applicable)
Generate SSH keys for secure communication with remote repositories:
Generate SSH keys using ssh-keygen and add the public key to your Git hosting provider (e.g., GitHub, GitLab).

3.4. Configuring Environment Variables
Set environment variables required for your development environment:
Edit .bashrc or .bash_profile (Linux/macOS) or configure environment variables through System Properties > Environment Variables (Windows).

4. Installing and Managing Dependencies
4.1. Package Managers Setup
Install and configure package managers for dependency management:
pip: Already installed with Python. Upgrade using pip install --upgrade pip.
npm: Included with Node.js. Update using npm install -g npm.

4.2. Virtual Environments (if applicable)
Use virtual environments to isolate project dependencies:
Create virtual environments using python -m venv env and activate with . env/bin/activate (Linux/macOS) or .\env\Scripts\activate (Windows).

5. Customizations and Extensions
Enhance your development environment with customizations and extensions:
5.1. Text Editor or IDE Extensions
Install extensions for additional features:
VS Code: Explore extensions for linting, formatting, and language support (e.g., Python, JavaScript).
PyCharm: Install plugins for database management, code inspections, and test runners.
Sublime Text: Add packages for syntax highlighting, snippets, and Git integration.
Atom: Install packages for version control, autocomplete, and project navigation.

5.2. Plugins and Add-ons
Integrate plugins and add-ons for specific tasks:
Linting: Install linters such as ESLint, Pylint for code quality checks.
Formatting: Use tools like Prettier, AutoPEP8 for consistent code formatting.
Debugging: Set up debuggers for Python, JavaScript, or other languages you use.
Database Tools: Include MySQL Workbench, pgAdmin for database management tasks.

6. Testing the Setup
Verify your development environment setup:
Create a sample project.
Write code, run tests, and debug issues.
Ensure dependencies install correctly and tools perform as expected.

7. Troubleshooting Common Issues
Troubleshoot and resolve common setup issues:
Check system requirements and compatibility.
Verify installation paths and environment variables.
Review error messages and consult documentation or community forums.
8. Next Steps and Additional Resources
Explore advanced configurations and optimize your workflow:
Learn shortcuts and advanced features of your IDE/text editor.
Customize build configurations and integrate CI/CD pipelines.
Stay updated with new releases and community plugins/extensions.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
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
