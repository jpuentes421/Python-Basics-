# Python-Basics-

## Objective

 Getting started with Python. Learning how to download python and VScode, also verifying the version number and creating a file. Will also execute a command using Python.


### Skills Learned

- Setting up python
- Verifying python version number
- Creating a file
- Executing the file three different ways

### Tools Used

- VS code
- Python


## Steps
1. Downloaded the latest version of Python on the Python website. On Windows, make sure to check the box that says **"Add Python to PATH"** before clicking "Install Now" This ensures that Python is added to your system's PATH environmenta variable and making it accessible from the command line.
2. Go to the VS Code website and install the latest and suitable version for your OS. Follow default installation to set up.
3. Launch VS Code after installation.
4. Go to the **Extensions** view and search for **Python**
5. Download the Python extension published by Microsoft.
6. We are now going to verify the Python installation. Open a terminal in VS Code by clicking on **Terminal** in the top menu and selecting **New Terminal**
7. Type this command using Git Bash
```bash
py -3 --version
```
8. The output should be the version of Python you installed.
![image](https://github.com/user-attachments/assets/40612762-e2b2-46e1-87e5-919a95518820)
9. We can also run python commands right at the prompt >>> using by typing in **py**. This is the Python **REPL** (read, evaluate, print, loop)
10. Type in
```bash
name = "Jessica"
```
11. Will notice when you hit **Enter** there is not output.
12. Now type in
```bash
name
```
13. The output is now **'Jessica'** we have just assigned a string to a variable called name. When we type in name into the prompt, it will output the string **'Jessica'**
    
![image](https://github.com/user-attachments/assets/ee080c5a-38fc-4bd9-a788-9bd6e2a209b4)

    
15. This is not how you usually provide the commands to the interpreter. Usually do this with files by creating a file with commands that we tell Python to execute.
16. Type to quit the Python REPL.
```bash
quit() 
```
17. Create a new file and type
```bash
greeting = 'Hello World!'
Print (greeting)
```
![image](https://github.com/user-attachments/assets/40bbcd6b-ea73-42c6-bea4-fc705d8c3fe0)

18. Click the **Play** button or **Run Python File**
19. This will open up a terminal window and show where the Python executable is, then a string of where it says Hello.py file (when we saved the file), we also see the output from the file that says **"Hello World!**
![image](https://github.com/user-attachments/assets/287449b5-8496-4458-9ab3-f7cba2e8145f)

20. We can also type in the Python file name, which will allow Python ro run the Hello World file as well.
```bash
py Hello.py
```
![image](https://github.com/user-attachments/assets/49a23318-2824-4955-8ef3-aeb9493553bb)

21. You can also right click on the Hello.py file and select **Run Python File in Terminal** and it runs it again.
    
![image](https://github.com/user-attachments/assets/0553fc7e-c621-40a6-9bc7-04380e73b0cf)
