>[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15258126&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11 

To download and install windowws 11 i used the following 

Download the software
Accessing the official site<a href="https://www.microsoft.com/software-download/windows11">Windows 11 Download</a>

Choosing the correct operation system mine is 64 bit.

Extract the software file
I extracted the file to a folder on my c drive using 7 zip by right-clicking and selecting extract here(folder created).

Follow the installation wizard
I followed the installation wizard guided steps license agreement, components and features to install, using default settingss after the installation process was complete i then restarted my pc.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Access the official website to download <a href="https://code.visualstudio.com/Download">Visual Studio Code Download</a>

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 1.PNG>)

After downloading it appears in the downloads folder.

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 2.PNG>)

Start the installation process following the instructions accepting terms and conditions, choosing the location data then launch visual studio code.

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 3.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 4.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 5.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 6.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/VS Code 7.PNG>)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Download the latest version of Git <a href="git-scm.com">git-scm.com</a> and choose the 64/32 bit version. 

After the file is downloaded, install it in the system. 

Once installed, select Launch the Git Bash, then click on finish. The Git Bash is now launched. 

Configure Git: git config --global user.name "Your Name" git config --global user.email "your.email@example.com"

Create a GitHub Account:

Sign up at <a href="https://github.com/">GitHub</a>

Initialize a Git Repository: mkdir my-project cd my-project git init echo "plpacademy" > README.md git add README.md git commit -m "Initial commit" https://github.com/Snowza20/plpacademy.git git push -u origin master
  
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Access the official website <a href="https://www.python.org/downloads/">python download</a>

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/Python 1.PNG>)

Select te latest version and download.

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/Python 2.PNG>)

When download is complete run the installer program following the instructions ensure to add python to path by checking the option.

Go to IDLE, the three greater than >>> sign is called the Python command prompt, where we write our program and with a single enter key, it will give results so instantly.

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/Python 3.PNG>)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Check and install

![alt text](../Users/QHAKAZILE/Downloads/Screenshots/PIP.PNG)

Verify pip installation: pip --version.

Upgrade pip (if necessary) on the command prompt: python -m pip install --upgrade pip.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Access  the official MySQL website <a href="https://dev.mysql.com/downloads/windows/installer/5.7.html">MySQL Installer</a>

Start download select just start my download link to proceed MySql downloading.

After download locate download find file start running the installer follow the instructions to start the installation process.

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/MY SQL 3.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/MY SQL 4.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/MY SQL 5.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/MY SQL 6.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/MY SQL 7.PNG>)

![alt text](<../Users/QHAKAZILE/Downloads/Screenshots/MY SQL 8.PNG>)

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   
Access the website <a href="https://www.docker.com/products/docke-desktop/">Docker Download</a>

Install Docker Desktop for Windows.

The installer will ask you to install WSL2, select this will download and install WSL2.

Restart the computer it will open up the Docker windows.

Verify on command prompt docker --version

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   
Installed Extensions and Plugins Explore Visual Studio Code:

Python:<a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python">Python Extension for VS Code</a>

GitLens:<a href="https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens">GitLens Extension</a>

Prettier:<a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Prettier - Code formatter</a>

Live Server:<a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner">Live Server </a>

Code Runner: Code Runner <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer">Code Runner</a>

9. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Challenges were to fully configure MYSQL and the inability to set Up Development Environments and Virtualization.



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
