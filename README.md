# conda-env-cmd-shortcuts
This repo is meant for a quick recap and access to work with windows command prompt, conda environment creation and handling.
#### 1.Check the current directory - cd
![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/caa4f390-9fdd-4391-9f8c-ee8e72ca1f99)
#### 2. Use the cd Command:
Type cd followed by the directory path you want to navigate to. For example:

![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/24a1af27-547f-4df3-b728-22ea93d8b974)

#### 3. Navigating to Different Drives:
If you need to change drives (e.g., from C: to D:), type the drive letter followed by a colon (:) and press Enter first.
![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/604abc5c-2ef0-4d64-9b1a-848c4caa4ae2)

### Special Cases:
#### 4. If the folder name has spaces, enclose the path in quotes, like this:
![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/fd20010b-951c-44b3-92f2-7f38f81df7be)

#### 5. To move up one directory level, use:
![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/85390f0d-3765-4128-9422-14c1cacc200d)

#### 6. To move directly to the root directory of the current drive:
cd \


# Conda environment

- Install anaconda in the system
- Add conda to your system's PATH environment variable. It can be done in 3 different ways:
- ### Option 1: Manually Adding Conda to PATH
Find Your Anaconda or Miniconda Installation:
Typically, Anaconda or Miniconda is installed in C:\Users\YourUsername\Anaconda3 for Anaconda or C:\Users\YourUsername\Miniconda3 for Miniconda.
Add Conda to PATH Temporarily:
Open Command Prompt and type:
set PATH=C:\Users\YourUsername\Anaconda3;C:\Users\YourUsername\Anaconda3\Scripts;%PATH%
Replace YourUsername with your actual username, and adjust the path if your Anaconda or Miniconda is installed in a different directory.
Test if Conda is Now Recognized:
In the same Command Prompt window, type:
conda --version
If it shows the Conda version, it's working correctly. Note that this change is temporary; closing the Command Prompt will reset the PATH.
- ### Option 2: Permanently Adding Conda to PATH
Search for 'Environment Variables' in Windows Search:
Click on "Edit the system environment variables" or "Edit environment variables for your account".
Edit the PATH Variable:
In the System Properties window, click on the "Environment Variables..." button.
In the Environment Variables window, scroll to find the "Path" variable under System variables or User variables.
Select "Path" and click "Edit...".
Click "New" and add C:\Users\YourUsername\Anaconda3 and C:\Users\YourUsername\Anaconda3\Scripts to the list. Again, adjust these paths if your installation directory is different.
Click OK to close all dialogs.
Restart Command Prompt:
Close and reopen Command Prompt to load the new PATH settings.
Verify that Conda is Working:
Type conda --version to check if Conda is now recognized.
- ### Option 3: Using Anaconda Prompt
Anaconda and Miniconda installations typically come with "Anaconda Prompt," which is pre-configured with the correct environment settings.
You can find "Anaconda Prompt" in the Start Menu under Anaconda or Miniconda folder.
Use this prompt for all your Conda operations.
Choose the option that best suits your needs. If you plan to use Conda regularly, adding it to your PATH permanently (Option 2) is more convenient.


# Start Working in Conda Env

- #### Activate Conda(if necessary):
- If Conda is not already activated or if it’s not recognized in your command line session, you might need to activate the base environment. Usually, this involves pointing to the activate.bat script in your Anaconda or Miniconda installation.
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/14cb8e7d-880b-4a21-b4c0-8fcaaaebfe3a)

- #### Check whether conda is activated
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/b795ee38-cb18-443f-906a-776b99da1268)

- #### Check list of env present
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/4cad3a2d-5ec7-4451-a29f-aee1f74b8327)

- #### Set a conda env path
- Set the path where the conda env needed to be installed.
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/e42c59d1-84eb-457a-af0c-1cb427b32d32)

- #### Create a conda env in the path
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/3103bd7b-5f48-4e8e-9a2f-aa788ec4dce4)

- #### Activate the conda env
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/ddcc65c9-60cc-4ac5-a760-671f2420fcd9)

- #### Check the newly created conda env
- ![image](https://github.com/smaran24/conda-env-cmd-shortcuts/assets/88144150/5c42ca7b-25d8-4ee5-84c9-41eebe5f5a7c)

