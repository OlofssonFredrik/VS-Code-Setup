# Python - VS Code Setup

Welcome to this beginner-friendly guide for setting up your Python development environment using Visual Studio Code (VS Code). This guide will walk you through each step from downloading VS Code to installing Python, necessary extensions, and libraries.

## Step 1: Install VS Code
Download VS Code from their official site and install it on your system. The download button is clearly visible on the site and corresponds to your specific operating system (Windows, MacOS, Linux).
![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/71a4f4c5-2d5d-4eec-a229-a8b4c9c20b9d)

## Step 2: Install Python
Download the latest version of Python from the official Python website. Important: Ensure to tick the box that says "Add Python to PATH" during the installation process to enable access to Python from any terminal
![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/4cd4e3a4-2d06-4764-b70f-9e5112d2e8fd)

Next up, to be able to run common scripts, you need to install special libraries for python, for example Matplotlib for plotting and visualization: Search for Command Prompt in the search bar on your computer open it and paste this: 
pip install numpy plotly matplotlib h5py pandas imageio scipy ipywidgets hdf5plugin
![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/017a7596-7596-4bfe-bd9f-414cdec54a63)

Let it take its time, it can take a minute or two depending on your internet. When finished it will look like this, dont worry about any warning messages:
![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/2d0de27e-6add-4272-854b-e6f6be7ae1ed)

Now, find your Visual Studio Code application on your computer. Initially it will ask for a theme and choose any of your preference, dark theme is preffered by programmers:
![image](https://github.com/OlofssonFredrik/VS-Code-Setup/assets/107762409/6b913a2a-1529-46b5-bfa2-ba7b00a6e7e3)

Extentions:


HTML:
Auto Close tag,
Auto Rename tag,


Python: 
Python extention pack,
Jupyter,
Black formatter,
Pylance,
Pip install black and enable python provider 


General:
Github Copilot,
Github Copilot Nightly,
Github Copilot Labs,
JSON,
Material Icon Theme,
Prettier,
Code Spell Checker,
Marp,




Maybe:
Gitlens,
Indent Rainbow

Kaleido: c:\Users\SEOLOFSSOF\AppData\Local\Programs\Python\Python311\python.exe -m pip install -U kaleido
Problem not occuring on pip list in jupyter environment but at machine when doing pip install -U kaleido
