 👋Hi I am Watson!
 
 Cybersecurity Proffessional
- 👀 I’m interested in Cybersecurity Analyst roles
- 🌱 I’m currently learning CompTIA Security+ and completed Google Cybersecurity Certificate
 
- 💞️ I’m looking to collaborate on:
 
•	Drafting a professional statement

•	Conducting a security audit

• Mantaining a strong security posture
 (employ NIST Frameworks, Controls and CIA Triad)
 
•	Analyzing network structure and security

•	Using Linux commands to navigate directories & files

/home/analyst
analyst@0691f6bfd0a3:~$ ls
logs  projects  reports  temp
analyst@0691f6bfd0a3:~$ cd reports
analyst@0691f6bfd0a3:~/reports$ cd /home/analyst/reports
analyst@0691f6bfd0a3:~/reports$ ls
users
analyst@0691f6bfd0a3:~/reports$ cd /home/analyst/reports/users
analyst@0691f6bfd0a3:~/reports/users$ ls
Q1_added_users.txt  Q1_deleted_users.txt
analyst@0691f6bfd0a3:~/reports/users$ cat Q1_added_users.txt
employee_id  username  department
1001         bmoreno   Marketing
1026         apatel    Human Resources
1041         cgriffin  Sales
1104         mreed     Information Technology
1177         aezra     Human Resources
1188         noshiro   Finance
analyst@0691f6bfd0a3:~/reports/users$ cd /home/analyst/logs
analyst@0691f6bfd0a3:~/logs$ ls
server_logs.txt
analyst@0691f6bfd0a3:~/logs$ ls
server_logs.txt
analyst@0691f6bfd0a3:~/logs$ head server_logs.txt
2022-09-28 13:55:55 info    User logged on successfully
2022-09-28 13:56:22 error   The password is incorrect
2022-09-28 13:56:48 warning The file storage is 75% full
2022-09-28 15:55:55 info    User logged on successfully
2022-09-28 15:56:22 error   The username is incorrect
2022-09-28 15:56:48 warning The file storage is 90% full
2022-09-28 16:55:55 info    User navigated to settings page
2022-09-28 16:56:22 error   The password is incorrect
2022-09-28 16:56:48 warning The current user’s password expires in 15 days
2022-09-29 13:55:55 info    User logged on successfully
analyst@0691f6bfd0a3:~/log

• Using Linux commands to manage file permissions
Task 1. Create a new directory
First, you must create a dedicated subdirectory called logs, which will be used to store all future log files.

Create a new subdirectory called logs in the /home/analyst directory.
The command to complete this step:

mkdir logs
Copied!
List the contents of the /home/analyst directory to confirm that you’ve successfully created the new logs subdirectory.
The command to complete this step:

ls
Copied!
The output should list the original three directories and the new logs subdirectory:

logs notes reports temp

Create a new directory
Task 2. Remove a directory
Next, you must remove the temp directory, as you’ll no longer be placing items in it.

Remove the /home/analyst/temp directory.
The command to complete this step:

rmdir temp
Copied!
List the contents of the /home/analyst directory to confirm that you have removed the temp subdirectory.
The command to complete this step:

ls 
Copied!
The temp directory should no longer be listed:

logs notes reports

Remove a directory
Task 3. Move a file
The Q3patches.txt file contains notes taken on third-quarter patches and is now in the correct reporting format.

You must move the  Q3patches.txt file from the notes directory to the reports directory.

Navigate to the /home/analyst/notes directory.
The command to complete this step:

cd /home/analyst/notes
Copied!
The previous command used the absolute path, you could use the relative path as follows:

cd notes
Copied!
Move the Q3patches.txt file from the /home/analyst/notes directory to the /home/analyst/reports directory.
The command to complete this step:

mv Q3patches.txt /home/analyst/reports/
Copied!
List the contents of the /home/analyst/reports directory to confirm that you have moved the file successfully.
The command to complete this step:

ls /home/analyst/reports
Copied!
When you list the contents of the reports directory, it should show that three quarterly report files are now in the reports directory:

Q1patches.txt Q2patches.txt Q3patches.txt 

Move a file
Task 4. Remove a file
Next, you must delete an unused file called tempnotes.txt from the /home/analyst/notes directory.

Remove the tempnotes.txt file from the /home/analyst/notes directory.
The command to complete this step:

rm tempnotes.txt
Copied!
List the contents of the /home/analyst/notes directory to confirm that you’ve removed the file successfully.
The command to complete this step:

ls
Copied!
No files should be listed in the notes directory.


Remove a file
Task 5. Create a new file
Now, you must create a file named tasks.txt in the /home/analyst/notes directory that you’ll use to document completed tasks.

Use the touch command to create an empty file called tasks.txt in the /home/analyst/notes directory.
The command to complete this step:

touch tasks.txt
Copied!
List the contents of the /home/analyst/notes directory to confirm that you have created a new file.
The command to complete this step:

ls
Copied!
A file called tasks.txt should now exist in the notes directory:

tasks.txt


Create a new file
Task 6. Edit a file
Finally, you must use the nano text editor to edit the tasks.txt file and add a note describing the tasks you’ve completed.

Using the nano text editor, open the tasks.txt file that is located in the /home/analyst/notes directory.
The command to complete this step:

nano tasks.txt
Copied!
Note: This action changes the shell from the normal Bash interface to the nano text editor interface.
Copy and paste the following text into the text input area of the nano editor:
  Completed tasks
  1. Managed file structure in /home/analyst
Copied!
Press CTRL+X to exit the nano text editor.
This triggers a prompt asking Save modified bufferer?

Press Y to confirm that you want to save the new data to your file. (Answering "no" will discard changes.)

Press ENTER to confirm that File Name to Write is tasks.txt.

Note: The recommended sequence of commands for saving a file with the nano text editor is to use CTRL+O to tell nano to save the file and then use CTRL+X to exit immediately.
In this web-based lab environment, the CTRL+O command is intercepted by your web browser and is interpreted as a request to save the web page. The sequence used here is a commonly used alternative that achieves the same end result.

Use the clear command to clear the Bash shell window and remove any traces of the nano text input area.

The command to complete this step:

clear
Copied!
Note: Most Bash shells typically handle the screen cleanup after you exit nano. In this lab environment, nano sometimes leaves some text clutter around the edges of the screen that the clear command cleans up for you.
Display the contents of the tasks.txt file to confirm that it contains the updated task details.
cat tasks.txt
Copied!
This file should now contain the contents of the tasks.txt file that you added and saved in previous steps:

  Completed tasks
  1. Managed file structure in /home/analyst
•	Applying filters to SQL queries

•	Identifying vulnerabilities, threats and risks

• incident response and recovery using NIST CSF 

•	Documenting incidents with an incident handler’s journal 

•	Importing and parsing a text file in a security-related scenario

•	Automate Cybersecurity Tasks with Python

- 📫 You can contact me on: Email wattienk@gmail.com
 
                            Phone: +2783 724 8693
  
                            linkedin.com/in/watson-nkomo-188216a6
  

<!---
Watty-1/Watty-1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
