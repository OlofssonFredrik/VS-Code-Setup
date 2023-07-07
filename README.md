# Python - Visual Studio Code (VS Code) Setup

Welcome to this beginner-friendly guide for setting up your Python development environment using Visual Studio Code (VS Code). This guide will walk you through each step from downloading VS Code to installing Python, necessary extensions, and libraries.

## Step 1: Install VS Code
Download VS Code from their official site and install it on your system. The download button is clearly visible on the site and corresponds to your specific operating system (Windows, MacOS, Linux).

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/71a4f4c5-2d5d-4eec-a229-a8b4c9c20b9d)
 
## Step 2: Install Python
Download the latest version of Python from the official Python website. Important: Ensure to tick the box that says "Add Python to PATH" during the installation process to enable access to Python from any terminal

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/4cd4e3a4-2d06-4764-b70f-9e5112d2e8fd)

## Step 3: Install Python Libraries
To run Python scripts, you'll need some additional libraries. These can be installed via the Command Prompt (Windows) or Terminal (MacOS, Linux). Run the following command:
pip install numpy plotly matplotlib h5py pandas imageio scipy ipywidgets hdf5plugin ipykernel

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/dbe3e51f-63cd-464f-9eea-397b4b20cffd)


### Let it take its time, it can take a minute or two depending on your internet. When finished it will look like this, dont worry about any warning messages:

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/2d0de27e-6add-4272-854b-e6f6be7ae1ed)

## Step 4: Set Up VS Code
Launch VS Code. You'll be asked to select a theme of your preference.

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/6b913a2a-1529-46b5-bfa2-ba7b00a6e7e3)

## Step 5: Install VS Code Extensions
VS Code extensions can enhance your coding experience. Install the extensions by going to the extensions tab (or press Ctrl+Shift+X). Here are some essential extensions:
### Python Extension Pack: For Python language support.
### Jupyter: For interactive notebooks support.
To install an extension, simply type its name in the search bar and press the install button.

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/b98c0e38-a676-4c4f-8856-af56608bd5ce)


## Step 6: Open Python Project in VS Code
To open your Python project, navigate to File > Open Folder and select your project folder.

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/be6424cc-f91a-413b-8135-02d2661545fa)

## Step 7: Selecting the Kernel/Interpreter
The kernel/interpreter you select defines the Python version that will be used to run your files. You should choose the one you've recently installed. To do this:

### Locate the version currently in use at the top right corner of VS Code.
### Click on it, then select Kernel --> Python Environments.
### Choose the version you've installed.

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/f2399fe3-74ea-4e1d-801f-63f57fc8da2d)

## Problem with ipykernel not installed
Running into a message that ipykernel is required is a common issue. First, verify that you're using the Python version you've downloaded. If the problem persists, click Install. If you still encounter issues, try the following steps:

Reload the VS Code application and attempt installation again.
Restart your computer and try installing again.
Run the command pip install ipykernel in your command prompt.

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/c58c2852-ca26-403d-9941-43e058b28b9a)


## Recommended VS Code Extensions
Consider enhancing your development experience with these extensions:

Black (Python formatter)
Pylance (Static type checking)
Auto Close Tag (HTML)
Auto Rename Tag (HTML)
Github Copilot (AI pair programming assistant, subscription required)
JSON
Material Icon Theme (Enhances readability)
Prettier (Code formatter)
Code Spell Checker
Marp (Markdown presentation)
GitLens (Git version history)
Indent Rainbow (Indentation support)
Install these extensions the same way as described in Step 5 for a smoother and more productive development experience.

## Installing Kaleido for Image Export
If you need to export plots to static images, you might require the kaleido package. If you find it installed globally but not in your current directory, you can specifically install it using the following command in your command prompt:

c:\Users\SEOLOFSSOF\AppData\Local\Programs\Python\Python311\python.exe -m pip install -U kaleido

### You can run pip list both at the root (where you installed all Python libraries) and in your code to see the libraries available at each level.

![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/790e41c9-717a-4f63-87c1-63f67fa1ee84)


