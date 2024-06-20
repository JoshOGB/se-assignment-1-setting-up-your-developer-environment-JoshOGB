[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283788&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   For windows installation, my machine came with Windows 11 so no need to install


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   -  I downloaded Visual Studio Code from https://code.visualstudio.com/Download, from the site I selected the “Download for Windows” button to start the download of the Visual Studio Code Application.
      ![alt text](VSCODE.jpeg)
   -  After the download was completed, I located the file from my download folder, extracted the file using Winrar, then the Visual Studio Code Icon appears in the downloads folder
   -  I Clicked on the Installer icon to start the installation process of the Visual Studio Code.
   -  After the Installer opened, it asked me to accept the terms and conditions of the Visual Studio Code. I Clicked on I accept the agreement and then clicked the Next button.
   -  I Chose the location data for running the Visual Studio Code. I ensured i selected add to path in the opgtions provided. Then click on the Next button.
   -  Then it asked to begin the installation setup. I Clicked on the Install button.
   -  After the Installation setup for Visual Studio Code was completed finished, I selected the “Launch Visual Studio Code” checkbox and then clicked Finished.



3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   -  I downloaded the latest version of Git and chose the 64 bit version. 
   -  After the file is downloaded, I installed it in my system. 
   -  After the installation, I selected the Launch the Git Bash button, then clicked on finish.
   -  After installation i Checked the Git version using:
      $ git --version
   -  Then I Create a local directory using the following command:
      $ mkdir test
      then navigated to the folder using:
      $ cd test
   -  Then, I initialized the directory using:
      $ git init
   -  Then i went to th folder where "test" was created and created a text document named "demo." I Opened "demo" and put in "This is a Demo text" Saved and closed the file.
   -  I Entered the Git bash interface and typed the command to check the status:
      $ git status
   -  I added the "demo" to the current directory using the following command:
      $ git add demo.txt
   -  Then, I made a commit using the following command:
      $ git commit -m "committing a text file"



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  -   I visited www.python.org, which is the official Python website.
  -   I clicked on the Downloads tab and then selected the Windows option. 
  -   Then I selected “Windows x86-64 executable installer”
  -   Once the executable file download was completed, I opened it from my download folder.
  -   I clicked on Run, to start the installation process.
  -   From the dialog box, I selected Install Now and Add to path.
  -   Once the installation is completed, a popup appeared showing: Setup was successful. then i clicked close.



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   PIP came installed with my python installation. ![alt text](pip.jpeg)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

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
