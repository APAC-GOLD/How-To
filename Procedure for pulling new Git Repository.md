## Standard Operating Procedure (SOP) for Pulling New Git Repository
![alt text](<Procedure for pulling new Git Repository -1.png>)
### Purpose
These steps are for individuals who want to pull code from GitHub to a local repository and then push their changes back to GitHub to share with a tutor or a peer.

### Prerequisites
- Ensure you have Git installed on your local machine.
- Have access to a GitHub account.
- Visual Studio Code or another terminal is installed.

### Instructions

#### Step 1: Log in to GitHub
1. Open your browser and log in to your GitHub account.

#### Step 2: Select Repository
1. Navigate to the repository you want to clone.
2. Click on the **Code** button.
3. Copy the HTTPS URL of the repository (you will use this later).
![alt text](<Procedure for pulling new Git Repository -2.png>)
#### Step 3: Open Terminal and Navigate to Desired Local Directory
1. Open Visual Studio Code or another terminal.
2. Navigate to the directory where you want to clone the repository.
    - Use the `cd` command to change directories.
![alt text](<Procedure for pulling new Git Repository -3.png>)
Screenshot showing – this folder is not a a github repository
#### Step 4: Check for Existing Git Repository
1. Ensure the folder is not already linked to a GitHub repository by typing:
    ```bash
    git status
    ```
2. If the folder is not a GitHub repository, proceed to the next step. If it is, you will need to delete the existing repository.

#### Step 5: Clone the Repository
1. Type the following command in your terminal, replacing the URL with the one you copied earlier:
    ```bash
    git clone https://github.com/kris-classes/restart-q4-2023-assignment-amy.git
    ```
![alt text](<Procedure for pulling new Git Repository -3.png>)Screenshot showing - the command & URL
2. This will create a new folder inside your directory with the contents of the repository.
![alt text](<Procedure for pulling new Git Repository -4.png>)
Screenshot showing - command & URL
![alt text](<Procedure for pulling new Git Repository -5.png>)Screenshot showing – that github has created a new folder inside the folder called 
#### Step 6: Verify the Repository
1. Check the status by typing:
    ```bash
    git status
    ```
2. Navigate into the newly created directory to verify that the files are present:
    ```bash
    cd restart-q4-2023-assignment-amy
    ls
    ```
    
![alt text](<Procedure for pulling new Git Repository -6.png>)Screenshot showing - the folder has been downloaded to restart-q4-2023-assignment-amy

![alt text](<Procedure for pulling new Git Repository -7.png>)
Screenshot showing - file directory (cd restart-q4-2023-assignment-amy)

### Making Changes and Pushing to GitHub

#### Step 1: Make Changes
1. Open the files in Visual Studio Code or your preferred editor.
2. Make the necessary changes to the files.
![alt text](<Procedure for pulling new Git Repository -8.png>)
 Screenshot showing -  command & file.
 
#### Step 2: Stage the Changes
1. Type the following command to stage all changes:
    ```bash
    git add .
    ```
![alt text](<Procedure for pulling new Git Repository -9.png>)Screenshot showing - git add . (see terminal section).

#### Step 3: Commit the Changes
1. Commit your changes with a message:
    ```bash
    git commit -m "enter your message here"
    ```
![alt text](<Procedure for pulling new Git Repository -10.png>)Screenshot showing - git commit -m “enter your message here”
#### Step 4: Push the Changes
1. Push the committed changes to GitHub:
    ```bash
    git push
    ```
![alt text](<Procedure for pulling new Git Repository -11.png>) Screenshot showing - git push 

### Conclusion
Your changes have now been committed and pushed to GitHub. You can verify the changes on your GitHub repository page.
![alt text](<Procedure for pulling new Git Repository -12.png>)
Screenshot showing - your changes have been committed 

![alt text](<Procedure for pulling new Git Repository -13.png>)
Screenshot showing - your changes have been committed 
### End
Kicking Goals!