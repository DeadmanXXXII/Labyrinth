# Labyrinth

This tool has been updated and now consists of multiple features when the functions for V7 happen this tool will be completed.
This is now a cross platform Windows and Linux Automated Defense system, that uses unique encryption to protect files on the network that are view only.
Below is a step by step guide on how to use Labyrinth and it's keyfile generator.

Tested in Kali 2022-Newest, Windows 10 Home and Pro, Ubuntu 18.0.04 - 22 + new.

Step-by-Step Guide and extremely important.

*****###### These keys are unique per generation. If it gets lost I cannot help you quickly. Feel free to approach me about safe storage of keys. If you can't decrypt yourself don't worry we can help it just takes a bit of time to reverse engineer the encryption and an on-site visit. You don't have to use us other Cryptographers will be able to do this just again they'll have to be on site. #####*****

Step 1: Generate a Key File
1. Open the Key Generator Application:
Launch the Key Generator application.

2. Generate a Key:
Click on the "Generate Key" button.
A new key will be generated and displayed in the text box.

3. Save the Key:
Click on the "Save Key to File" button.
A save dialog will appear.
Choose the location where you want to save the key file.
Enter any name you like for the key file (e.g., `mykeyfile.txt`, `encryption_key.key`, `importantfile.xml`, etc.).
 
Click "Save".

Step 2: Set Up Labyrinth for Encryption/Decryption
1. Open the Labyrinth Tool:
Launch the Labyrinth application.

2. Select Directory to Monitor:
In the "Select a directory to monitor:" section, click the "Select Directory" button.
A file dialog will appear.
Choose the directory you want to monitor for encryption/decryption.

3. Select Key File:
In the "Select a key file:" section, click the "Select Key File" button.
A file dialog will appear.
Navigate to and select the key file you saved earlier.

4. Select Trigger for Encryption/Decryption:
In the "Select trigger for encryption:" section, choose the appropriate trigger from the dropdown menu (e.g., "Create", "Delete", "Modify").

5. Select Encryption/Decryption Mode:
In the "Select encryption mode:" section, choose the appropriate mode from the dropdown menu (e.g., "Individual", "Group", "All").
If you choose "Group", you will need to enter the group paths in the "Enter group paths (comma-separated):" section.

Step 3: Start Monitoring for Encryption/Decryption
1. Start Monitoring:
Click the "Start Monitoring" button.
Labyrinth will start monitoring the selected directory based on the chosen trigger and mode.
A message box will confirm that monitoring has started.

2. Stop Monitoring:
If you want to stop monitoring, click the "Stop Monitoring" button.
A message box will confirm that monitoring has stopped.

Additional Notes
Encryption:
When a monitored event (e.g., file creation) occurs, Labyrinth will encrypt the file using the key from the selected key file.
The original file will be replaced with an encrypted version (with a `.encrypted` extension).

Decryption:
When a monitored event occurs, Labyrinth will decrypt the encrypted file (with a `.encrypted` extension) back to its original form.
The decrypted file will have its original extension and name.

Troubleshooting
Error Messages:
If there is an issue with the key file (e.g., it cannot be read), Labyrinth will display an error message. Ensure the key file is correct and accessible.
If the selected directory is invalid or not accessible, an error message will appear. Make sure the directory exists and you have permission to access it.

Logs:
Labyrinth logs its activity to a file named `encryption_tool.log`. If you encounter issues, you can check this log file for detailed error messages and activity logs.

By following these steps, you should be able to successfully generate a key file and use it with the Labyrinth encryption and decryption tool.

Recently tested ie today. (Date of last update of text.)

The Labyrinth encryption tool and the key file generator are Python-based applications using the Tkinter library for the GUI and the Cryptography library for encryption. 
They should be compatible with any operating system that supports Python and these libraries. 
Here’s a list of compatible operating systems and some popular IDEs you can use to run them:



2. MacOS:
   - Python comes pre-installed on MacOS, but you might want to install a newer version from the [official Python website](https://www.python.org/downloads/).
   - Install the Tkinter and Cryptography libraries using `pip`.

Installing Dependencies
To ensure you have all the required libraries, you can run the following commands in your terminal or command prompt:

sh
pip install cryptography
pip install watchdog

Tkinter is usually included with standard Python distributions. If you encounter issues with Tkinter, you may need to install it separately:

On Debian-based systems (like Ubuntu): `sudo apt-get install python3-tk`
On Red Hat-based systems (like Fedora): `sudo dnf install python3-tkinter`

Popular IDEs
Besides PyCharm and running it directly in a terminal, here are some other popular IDEs and text editors that you can use to run these Python applications:

1. Visual Studio Code (VS Code):
   - A lightweight, powerful editor that supports Python through extensions.
   - Install the Python extension from the marketplace for syntax highlighting, debugging, and more.
   - [Download VS Code](https://code.visualstudio.com/)

2. Anaconda (with Spyder IDE):
   - Anaconda is a distribution of Python and R for scientific computing and data science. It includes Spyder, a powerful IDE for Python.
   - [Download Anaconda](https://www.anaconda.com/products/distribution)

3. Jupyter Notebook:
   - An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.
   - You can install Jupyter via Anaconda or using `pip install notebook`.
   - [Project Jupyter](https://jupyter.org/)

4. Sublime Text:
   - A sophisticated text editor for code, markup, and prose. It has great support for Python with additional plugins.
   - [Download Sublime Text](https://www.sublimetext.com/)

5. PyDev (for Eclipse):
   - A Python IDE for Eclipse, which may be preferred by developers familiar with the Eclipse environment.
   - [PyDev](http://www.pydev.org/)

6. Thonny:
   - An IDE designed specifically for beginners. It’s simple yet powerful enough for advanced users.
   - [Download Thonny](https://thonny.org/)

Running the Application
1. Open your IDE or terminal.
2. Navigate to the directory containing your Python script.
3. Run the script:
sh
   python key_generator.py  # For the key generator
   python labyrinth.py      # For the Labyrinth tool

By ensuring you have the correct versions of Python and the necessary libraries installed, you should be able to run the applications smoothly on any of the listed operating systems and IDEs.

If you have any emergency issues call me please remember I live in the UK, so if you phone from half the world away depending on direction your 1pm may be my 3am.
Blu Corbel +447576285686 
I can attempt to decrypt you remotely or try walk you through it as these keys are unique per generation.
my links are on my profile page
email address: themadhattersplayground@gmail.com
