### 3. Basic Commands
One of the biggest differences between Windows and Linux is the way in which you interact with your files. Windows relies mostly on graphical interfaces and using the file explorer to interact with the system, but Linux uses the command line/terminal for quicker control of your system. Once you have downloaded Linux Ubuntu, there are a multitude of commands that you must learn in order to operate and interact with your system. 


#### 3.1 Figuring out file and directory information

<h4><code>pwd</code> - Print Working Directory </h4>

<h6>This command effectively shows the path to the directory you are currently in. </h6>

Ex. - When you are in your Desktop, if you ran the _pwd_ command, the terminal would output "/home/<your-username>/Desktop"

---

<h4><code>ls</code> - List All Files </h4>

<h6>This command lists all the files that are in the directory you are currently in.</h6>

Ex. - If you are in a directory named _**animals**_ in your Downloads (path would be _**/home/<your-username>/Downloads/animals**_) that contains _**dog.txt**_, _**cat.txt**_, and _**bird.txt**_, running:

`ls`

lists out all of those files to the terminal. 

---
#### 3.2 Navigating directories

<h4><code>cd &ltpath-to-directory&gt</code> - Navigate to a directory</h4>

<h6>This command moves you to the directory you specify.</h6>

Ex. - If you are in a the root directory and want to move down to a directory at path /animals/cats, you would run the command `cd /animals/cats` and you would be moved into the cats directory

---

<h4><code>cd ..</code> – Go “Up” a Directory </h4>

<h6>This command moves you up one level in the directory structure. </h6>

Ex. – If you are in `/home/<your-username>/Downloads/animals` and run:

`cd ..`

You would move **up** to `/home/<your-username>/Downloads`

---
#### 3.3 Altering files and directories

<h4><code>mkdir &ltdirectory-name&gt</code> – Make a Directory</h4>

<h6>This command creates a new folder/directory in the location you are currently in. </h6>

Ex. – To create a folder named _**projects**_, type:

`mkdir projects`

Now a new folder named `projects` will appear in your current directory.

---

<h4><code>rmdir &ltdirectory-name&gt</code> – Remove a Directory &lt</h4>

<h6>This command deletes an **empty** directory. </h6>

Ex. – If you want to delete an empty folder named `old_files`, type:

`rmdir old_files`

---

<h4><code>touch &ltfilename&gt</code> – Create a New File </h4>

<h6>This command creates a new, empty file. </h6>

Ex. – To make a new text file named `notes.txt`, type

`touch notes.txt`


You can then open it later with any text editor of your choosing.

---

<h4><code>cp &ltsource&gt &ltdestination&gt</code> – Copy Files or Directories </h4>

<h6>This command copies a file or folder from one location to another. </h6>

Ex. – To copy `notes.txt` into the **Documents** folder:

`cp notes.txt ~/Documents`


---

<h4> <code>mv &ltsource&gt &ltdestination&gt</code> – Move or Rename Files </h4>

<h6>This command moves a file or renames it. </h6>

Ex. – To rename `notes.txt` to `summary.txt`:

`mv notes.txt summary.txt`


Or to move it into another folder:

`mv summary.txt ~/Documents`



---

<h4> <code>rm &ltfilename&gt</code> – Delete a File </h4>



!!! warning
    - This command **permanently** deletes a file, there is NO RECYCLING BIN to restore it


Ex. – To delete the file `notes.txt`, type:

`rm notes.txt`

Additionally, you can do:
<h4><code>rm -r &ltdirectory-name&gt</code> - removes a directory and ALL files inside it </h4>

If you have a directory named `animals` with `cat.txt` and `dog.txt` inside it, running:

`rm -r animals`

Will effectively remove `animals` along with `dog.txt` and `cat.txt`
