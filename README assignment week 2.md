 #ASSIGNMENT 2

1.DETAILED PROCESS OF DOWNLOADING AND INSTALLING WINDOWS 11

STEP 1:Backed up my data
STEP 2:Checked for compatibility
I ran the PC health check tool to see if my PC is compatible with windows 11
STEP 3:Download windows 11
I downloaded from the official windows 11 download page on microsoft website and installed using the windows 11 installation assistant method which is a tool for upgrading my already existinng windows 10
STEP 5:Install windows 11
following the on screen instructions, i completed my installation
STEP 6:windows 11 setup
This pocess included connecting to a network, selecting a region and signing in to my microsoft account
STEP 7:Instaling updates 
complete process

2.PROCESS OF DOWNLOADING AND INSTALING VS CODE

### Step 1: Downloading Visual Studio Code
To download Visual Studio Code (VS Code),I started by opening my web browser and navigating to the official VS Code website at (https://code.visualstudio.com/). On the homepage, I went to "Download" button that automatically detected my operating system (Windows).I started downloading the installer file for my OS which is windows.

### Step 2: Installing Visual Studio Code
Once the download was complete, I located the installer file in my Downloads folder and double-clicked it to start the installation process. On Windows, an installation wizard will guide you through the setup process. You'll need to accept the license agreement, choose an installation location, and select additional tasks such as creating a desktop icon or adding VS Code to your system PATH.

### Step 3: Setting Up Visual Studio Code
After installation,I opened Visual Studio Code by clicking its icon. When I first launched VS Code, I was prompted to install recommended extensions based on my preferred programming languages or frameworks. You can do this through the Extensions view by clicking the Extensions icon on the sidebar or pressing `Ctrl+Shift+X` . 

3.REPORT OF INSTALLING AND CONFIGURNG GIT ON MY LOCAL MACHINE

STEP 1:Installation Process
To install Git on my local machine, I began by visiting the official Git website at https://git-scm.com/. I clicked the "Download" button, which automatically detected my operating system (Windows). This action initiated the download of a .exe installer file. After downloading, I ran the installer, which guided me through an installation wizard. During this process, I customized several options, such as selecting my default text editor for Git, configuring the name of the initial branch, and ensuring that Git was added to my system's PATH environment. This installation process was straightforward and took only a few minutes to complete.

Initial Configuration
After successfully installing Git, I proceeded to configure it with my personal information to ensure proper identification in commit messages. I opened the command prompt and set my username and email address with the following commands:git config --global user.name "My Name"
git config --global user.email "my.email@example.com"
STEP 2:I set up a github account and initialied a repository and made my first commit. This is the repository link: https://github.com/Mwangi23-code/Demo-1

4.REPORT ON INSTALLING PYTHON
STEP 1:Installation Process
To install Python on my local machine, I began by visiting the official Python website at https://www.python.org/. I navigated to the "Downloads" section, which automatically suggested the latest version suitable for my operating system (Windows). I clicked the "Download" button to obtain the Python installer executable (python-<version>.exe). After downloading, I ran the installer, ensuring to select the option "Add Python to PATH" before proceeding. This option is crucial as it enables running Python from the command line. The installation wizard offered several customization options, but I opted for the default settings to streamline the process. The installation completed successfully, indicating Python was now ready for use on my system.

STEP 2:Initial Configuration
After installing Python, I verified the installation by opening the command prompt and running the commands python --version and pip --version. These commands confirmed the successful installation of Python and its package manager, pip. To manage packages efficiently, I decided to create a virtual environment for my projects. I navigated to my project directory and executed:python -m venv myenv
This command created a virtual environment named myenv. I activated the environment using myenv\Scripts\activate on Windows. Once activated, I used pip to install necessary packages, such as Flask for web development (pip install flask). This setup ensured a clean and isolated environment for my project dependencies.

STEP 3:Integrating with IDE and Configuring PATH
To enhance my development experience, I integrated Python with Visual Studio Code. I opened VS Code and installed the Python extension, which provides features like IntelliSense, linting, and debugging. I configured the interpreter by selecting the Python version from the Command Palette (Ctrl+Shift+P and then "Python: Select Interpreter"). Additionally, I ensured that the PATH environment variable was correctly configured by verifying it through the command prompt with echo %PATH%. This configuration allowed me to run Python scripts and manage packages directly from the terminal. The successful installation and configuration of Python provided a robust foundation for developing and managing my Python projects efficiently.

5.REPORT ON CONFIGURING A DATABASE (MY SQL)

STEP 1:Installation Process
To install MySQL on my local machine, I started by visiting the official MySQL website at https://dev.mysql.com/downloads/installer/. I chose the MySQL Community Edition, which is freely available and suitable for most users. I downloaded the MySQL Installer for Windows, specifically the mysql-installer-web-community-<version>.exe file. Once the download was complete, I ran the installer, which presented several installation options such as Developer Default, Server only, and Client only. I selected the "Developer Default" option to include MySQL Server, MySQL Workbench, and other useful tools. The installation process was straightforward, and I followed the prompts to complete it. The installer also checked for any missing dependencies and installed them as needed.

STEP 2:Initial Configuration
After the installation, the MySQL Installer launched the configuration wizard. I configured the MySQL Server by choosing the "Standalone MySQL Server / Classic MySQL Replication" option. I set the desired configuration type and connectivity settings, ensuring to select the default port 3306. I then created a root password and optionally set up additional user accounts. The wizard also allowed me to configure the Windows Service details, where I chose to run MySQL as a Windows service and set it to start automatically. This configuration ensured that MySQL Server would start with my computer and be readily available for use. After completing these steps, the configuration wizard applied the settings and started the MySQL Server.

STEP 3:Verifying Installation and Connecting with MySQL Workbench
To verify the installation, I opened MySQL Workbench, which was included in the installation package. I created a new connection by clicking on the "MySQL Connections" tile and entering the connection details, such as the connection name, hostname (localhost), port (3306), and the root user credentials set during the configuration. After testing the connection successfully, I opened the connection to interact with the MySQL Server. In MySQL Workbench, I could execute SQL queries, manage databases, and perform administrative tasks. Additionally, I confirmed that the MySQL service was running correctly by checking the Windows Services Manager. This comprehensive setup and configuration process ensured that MySQL was fully operational on my local machine, ready for database management and development activities.

6.CHALLENGHES FACED

A): CONFIGURATION ISSUES:For Git, this involves setting global configurations such as username and email
          For Python, setting up virtual environments and managing package installations can be tricky
B): PATH Environment Variable:During the installation of Python and Git,i had not ensured the installer had added the software to the PATH
