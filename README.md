# End-to-End-Medical-Chatbot

1. Open Git repository
    -- Add readme file
    -- Add .gitignore template as Python
    -- Choose License as MIT License
    -- Copy the repository link which finds under Code HTTPS -- https://github.com/Vinay7083/End-to-End-Medical-Chatbot.git

2. Then go to local machine and make one folder and go inside that folder
3. Then open terminal and type git clone https://github.com/Vinay7083/End-to-End-Medical-Chatbot.git
4. After successfully cloning go to the folder for ex. End-to-End-Medical-Chatbot by using cd End-to-End-Medical-Chatbot
5. After that Make one Conda Environment so that we can easily work.
6. Command for making conda environment is
    -- conda create -n medibot python=3.10 -y
    then activate this environment
    -- conda activate medibot
7. After successfully activated environment install required libraries, for this make one requirements.txt file and inside that file mentioned all the required libraries
8. Again go to the terminal and hit this command, pip install -r requirements.txt
9. Then we created folder structure for our project, Here we've used Modular Approach for creating folder where we write one code in template file such that it will create a list of folders and files which we needed
10. We've used OS, Path, Logging libraries so that we can crate our project folder strcture.
11. Instead of creating one single single time as per needed we created it as in modular way for this __init__.py file plays an important role so we need to create that file too.
12. After that we have created setup for our project inside setup.py file we've created our own package for that we need to add one command in requirements.txt file as -e . this command 
13. Then packages= find_packages(), this line in setup.py file will checking for __init__.py file and it will automatically created our own packge in system.
14. 