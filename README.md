# Python workshop

Organized by The Nexus and SJCET Startup Bootcamp.

<table>
  <tr>
    <td>Speaker</td>
    <td>Topic</td>
  </tr>
  <tr>
    <td>Siddharth Prajosh</td>
    <td>Python</td>
  </tr>
</table>

Workshop pre-requisites:

- `python` (_version 3.8 or greater_)
- `Jupyter Notebook` (_python interactive developement web application_)

# Setting up python workspace
Instruction for:
* [Windows](#windows)
* [Linux](#linux) 


## Windows

### 1.0 Downloading latest python
<p>Download the latest python ver. 3.9 from the official <a href="https://www.python.org/downloads/">website</a></p>
<br>
<img src = "images/download_page.png" width = 432px>  

### 2.0 Setup  
<p>Launch the executable setup file you just downloaded, and proceed through the installation</p>
<img src = "images/installation_first.png" width = 432px>

#### 2.1 Add path option checked
<p>Make sure that the <i>Add Python 3.9 to PATH</i> option is checked</p>
<br> 
<img src = "images/installation_first_ensure.png" width = 432px>

#### 2.2 Initiate 
<p>By clicking on the "<b><i>Install Now</i></b>" button initiate installation</p>
<br>
<img src = "images/installation_first_initiate.png" width = 432px>

#### 2.3 Complete installation
<p>Once the installation is completed, close the setup (You might have to restart your PC depending on the version of window and hardware specification)</p>
<br>
<img src = "images/installation_complete.png" width = 432px>

### 3.0 Command prompt setup 
<p>Open windows command prompt by submitting the command "cmd" in the <b>Windows Run</b> dialog box<br>To open Windows Run, use either: </p>  

* **Windows Button + R** Keyboard shortcut 
* **Right-click Windows Button** and select **"Run"**  

<img src = "images/windows_run.png" width = 432px>
<br>

#### 3.1 Check python version
<p>Within the windows Command Prompt, ensure the correct version of python is installed by running <code>python --version</code></p>
<br>
<img src = "images/cmd_python_ver.png" width = 432px>
<br>

<p>Python uses <b>pip</b> package manager which can be used to install various development software, which we will now use to install jupyter notebook</p>

### 4.0 Install Jupyter Notebook
<p>Use the command: <code>pip install notebook</code> to install jupyter notebook<br>This will install jupyter notebook and all it's dependencies, wait for installation to complete.</p>
<br>
<img src = "images/cmd_install_notebook.png" width = 432px>
<br>

### 5.0 Run Jupyter Notebook
<p>After installation is complete, you can start a jupyter notebook webserver by simply running the command <code>jupyter notebook</code> within command prompt window</p>
<br>
<img src = "images/cmd_run_notebook.png" width = 432px>
<br>
<img src = "images/notebook_start.png" width = 432px>
<br>

### 6.0 Creating new notebook for development
<p>Navigate to an appropriate directory/folder and create a new notebook</p>
<br>
<img src = "images/notebook_create_new.png" width = 432px>
<br>
<img src = "images/notebook_created.png" width = 432px>
<br>

## Linux 

Check if python is installed:  

```console  
user@pc:~$ python --version
```  
If python isn't installed, refer [here](https://phoenixnap.com/kb/how-to-install-python-3-ubuntu) to find installation intructions.  

### Installing jupyter notebook

Update and refresh repository list  
```console
user@pc:~$ sudo apt update 
```  

Installing jupyter notebook
```console
user@pc:~$ pip install notebook
```

Run notebook webserver by running the command
```console
user@pc:~$ jupyter notebook
```  

The jupyter notebook webserver will start running on your localhost, refer to <a href="#50-run-jupyter-notebook">notebook session instructions for windows</a> to run notebook session within the webserver instance.

### That's it, you're done setting up your system!
