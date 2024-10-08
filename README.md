# Explanation of the script:
1. Download and Install Python:
The script retrieves the latest version of Python from the Python website using regex and downloads the installer.
It installs Python in quiet mode and adds Python to the system PATH.

2. Create Project Directory:
The script creates a directory called PythonProjects inside the Documents folder if it doesn’t already exist.

3. Download and Install Visual Studio Code:
The script downloads the latest version of Visual Studio Code (64-bit) and installs it silently.

4. Add Python to PATH (if needed):
The script checks if Python is already in the system PATH. If not, it adds Python's installation path to the user environment variable.

5. Verification:
It verifies both Python and Visual Studio Code installations by running the --version command for each tool.


# How to use:

1. Open PowerShell as Administrator.

2. Copy and paste the script into the PowerShell window.

3. Press Enter to execute the script.

This script will fully automate the installation of Python, setup of environment variables, project folder creation, and installation of Visual Studio Code.
