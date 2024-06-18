[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15253423&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Prepare the External Drive:
Connect a USB flash drive (at least 8 GB) to your computer.

Download Windows 11 Installation Media:
Visit the official Microsoft Windows 11 download page. Click on download to get the Windows 11 Installation Media Creation Tool.

Create Windows 11 Installation Media:
Run the Media Creation Tool after downloading. Accept the terms and conditions. Create installati for another PC and click Next. Choose your language, edition, and architecture. Select USB flash drive as the media to use.

Prepare Your Computer:
Ensure your computer is connected to a power source and backed up. Restart your computer and enter the BIOS or UEFI firmware settings.

Set Boot Priority:
In the BIOS/UEFI settings, navigate to the Boot options. Set the USB flash drive as the primary boot device. Save the changes and exit BIOS/UEFI settings. Your computer will restart.

Install Windows 11:
When your computer restarts, it should boot from the USB drive. Follow the on-screen instructions to start the Windows 11 installation process. Choose your language, time, and keyboard preferences. Click Install now. Enter your product key if prompted. Select the edition of Windows 11 you want to install. Accept the license terms and click Next.

Partition and Install:
Choose the drive where you want to install Windows 11. Select the partition style. Follow the prompts to format the partition and begin the installation. Windows will copy files, install features, and update your system.

Complete Setup:
Once installation completes, your computer will restart. Remove the USB drive when prompted. Follow the on-screen setup instructions to personalize your Windows 11 experience, including creating user accounts and configuring settings.

Install Drivers and Updates:
After setup is complete, connect to the internet and check for updates. Install any necessary drivers for your hardware components that Windows Update doesn't automatically handle.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Download Visual Studio Code:
Visit the Visual Studio Code download page. Select the version suitable for your operating system.

Install Visual Studio Code:
Run the downloaded installer. Follow the installation prompts. It's recommended to select Add to PATH during installation to access VS Code from the command line.

Launch Visual Studio Code:
Once installed, open Visual Studio Code from your applications or search for it in the Start menu. Customize your setup by installing extensions for your programming languages and tools.

Explore Features:
Familiarize yourself with features like the Command Palette (Ctrl+Shift+P), integrated terminal, and source control integration.



3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

 Install Git:
Download Git from the official website. Run the installer and follow the prompts to install Git. Open a terminal and verify the installation with git --version.

Configure Git:
Set your global username: git config --global user.name "Your Name". Set your global email: git config --global user.email "your_email@example.com".

Create a GitHub Account:
Go to github.com and sign up for an account. Follow the instructions to complete your profile setup.

Initialize a Git Repository:
Navigate to your project directory in the terminal. Initialize the repository with git init. Add files to the staging area with git add. Make your first commit with git commit -m.

Connect to GitHub:
Create a new repository on GitHub via the New repository button. Copy the remote repository URL provided by GitHub. Link your local repository to the remote one with git remote add origin [URL]. Push your commit to GitHub with git push -u origin master.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Download Python:
Go to the Python downloads page. Click on the download link for the latest version of Python.

Install Python:
Run the downloaded installer. Make sure to check the box that says "Add Python to PATH" before you click Install Now. Follow the rest of the prompts to complete the installation.

Verify Installation:
Open a command prompt or terminal. Type python --version and press Enter. You should see the version of Python that you installed.

Install pip:
Run python get-pip.py in your terminal.

Use pip to Install Packages:
Use pip to install other packages as needed with pip install package-name.



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Verify pip Installation:
Open a command prompt or terminal. Type pip --version and press Enter. If pip is installed, you'll see the version number.

Upgrade pip:
To ensure you have the latest version of pip, you can upgrade it using python -m pip install --upgrade pip.

Using pip:
To install a package with pip, use pip install package-name. To uninstall a package, use pip uninstall package-name. To list installed packages, use pip list.



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Download MySQL Installer:
Visit the MySQL Windows Installer download page. Select the version that matches your system. Click Download and start the download process.

Install MySQL:
Run the downloaded installer. Choose the setup type; Full will install all MySQL products and features. Click Next and proceed with the installation, accepting the license terms. When prompted, set up a root password for your MySQL server.

Configure MySQL:
The installer will guide you through configuration options; you can choose the default settings for most cases. Complete the installation process.

Verify Installation:
Open the MySQL Command Line Client from your Start menu. Enter the root password you created during installation. If you're logged in, MySQL is installed and ready to use.



7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   Download Docker:
Go to the Docker website. Choose the version for your operating system.

Install Docker:
Run the downloaded installer. Follow the prompts, and ensure you select the option to add Docker to your PATH if it's available.

Verify Installation:
Open a terminal or command prompt. Type docker --version to check that Docker was installed correctly.

Run Docker:
Start Docker from your applications menu or Start menu. You might need to log out and log back in or reboot your computer to complete the installation.

Use Docker:
To download and run an image, use docker run hello-world. This command downloads a test image and runs it in a container.



8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Open Extensions View:
Click on the Extensions icon in the Activity Bar on the side of the window.

Search for Extensions:
Use the search bar at the top of the Extensions view to find extensions. You can search by name, functionality, or even programming language.

Install Extensions:
Click Install on an extension to add it to VS Code. Some extensions will require you to reload VS Code to activate.

Configure Extensions:
Some extensions have settings that you can customize. Access these by opening the Command Palette and searching for Preferences: Open Settings (JSON).

Explore Recommended Extensions:
VS Code also provides a list of recommended extensions for different file types and projects in the Extensions view.



9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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
