# ACT-CREATION-TOOL
This tool is used to create bulk accounts in Active Directory. The user will be prompted to import data from a csv, the user details from the CSV file will be used to set AD attributes for the new user. 

## Goal of the application
My goal for this project is to create a tool to create multiple users quickly in AD without having to use the GUI. The target user is a user who is not comfortable with PowerShell or the command line, but is responsible for provisioning accounts. 

## Dependencies
- ActiveDirectory module
- The config file to set the default parameters of the script. 
- The group list file will provide the options for initial group memberships for the users being created 
- The domains list file will provide the list of OU options for where the user will be created
- The dictionary file will contain a list of preset dictionary words used to generate a temporary password for a user. 

## To use
- 1. Download the CSV template. Fill in the user information on each line. 
- 2. Make sure all of the dependencies are in the same directory as the ACT Creation tool exe.
- 3. Use the dropdown to select the location where you would like to create the users (This will be dependent on how the configuration file is set up).
- 4. Browse to and select the CSV file where the user details are listed.
- 5. Click start and verify that you want to create the users. 
- 6. After the script completes, a results file will launch with the results of the program.

