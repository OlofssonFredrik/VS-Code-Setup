Python - VS Code Setup Guide
Welcome to this beginner-friendly guide for setting up your Python development environment using Visual Studio Code (VS Code). This guide will walk you through each step from downloading VS Code to installing Python, necessary extensions, and libraries.

Step 1: Install VS Code
Download VS Code from their official site and install it on your system. The download button is clearly visible on the site and corresponds to your specific operating system (Windows, MacOS, Linux).

Step 2: Install Python
Download the latest version of Python from the official Python website. Important: Ensure to tick the box that says "Add Python to PATH" during the installation process to enable access to Python from any terminal.

Python installation

Step 3: Install Python Libraries
To run Python scripts, you'll need some additional libraries. These can be installed via the Command Prompt (Windows) or Terminal (MacOS, Linux). Run the following command:

bash
Copy code
pip install numpy plotly matplotlib h5py pandas imageio scipy ipywidgets hdf5plugin
Let the installation run; this might take a few minutes.

Step 4: Set Up VS Code
Launch VS Code. You'll be asked to select a theme of your preference.

VS Code Theme

Step 5: Install VS Code Extensions
VS Code extensions can enhance your coding experience. Install the extensions by going to the extensions tab (or press Ctrl+Shift+X). Here are some essential extensions:

Python Extension Pack: For Python language support.
Jupyter: For interactive notebooks support.
To install an extension, simply type its name in the search bar and press the install button.

Step 6: Open Python Project in VS Code
To open your Python project, navigate to File > Open Folder and select your project folder.

Recommended VS Code Extensions:
Here are some additional extensions you might find useful:

Python Extensions:

Black (Python formatter)
Pylance (Static type checking)
HTML Extensions:

Auto Close Tag
Auto Rename Tag
General Extensions:

Github Copilot
JSON
Material Icon Theme
Prettier (Code formatter)
Code Spell Checker
Marp (Markdown presentation)
These extensions can make your development experience smoother and more productive. You can install these the same way as in Step 5.

Optional Extensions:

GitLens
Indent Rainbow
Kaleido Installation:

For some projects, you might need the kaleido package. You can install it with the following command:

bash
Copy code
python -m pip install -U kaleido
This command uses your Python executable to install kaleido.

Note: The issues with kaleido not appearing in the list of installed packages in a Jupyter environment but being available in the system's Python environment can be due to environment mismatch. Make sure you're using the same Python environment across all platforms.

Kaleido: c:\Users\SEOLOFSSOF\AppData\Local\Programs\Python\Python311\python.exe -m pip install -U kaleido
Problem not occuring on pip list in jupyter environment but at machine when doing pip install -U kaleido
