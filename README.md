# Installing Python and Pip on Windows

This guide will show you how to install Python and Pip on a Windows computer, enabling you to start developing Python programs.

## Step 1: Download and Install Python

1. Visit the official Python website: [Python Downloads](https://www.python.org/downloads/windows/).

2. Download the latest stable version by clicking the appropriate download button.

3. Select the installer file that matches your system, typically 64-bit. Click the download link to save the file.

4. Open the downloaded file.

5. Ensure that the "Add Python X.Y to PATH" option is enabled (X.Y represents the Python version).

6. Click "Install Now" and wait for the installation to complete.

## Step 2: Verify Python Installation

1. Open the Command Prompt by pressing the "Windows key," typing "cmd," and pressing Enter.

2. Type the command `python --version` and press Enter to display the installed Python version.

## Step 3: Install Pip (Python Package Manager)

1. With Python installed, you can use Pip automatically. Enter the following command in the Command Prompt:

   ```bash
   python -m ensurepip --default-pip
   ```
  Confirm that Pip was properly installed by running the command pip --version.

That's it! You have successfully installed Python and Pip on your Windows computer. You can now start writing Python programs and install Python packages using Pip. Happy coding!
