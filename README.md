# cj-app
Dotnet 3.1 - C# 8

IMPORTANT NOTES:

    1. Make sure you follow the steps mentioned under "PROJECT START STEPS" and ensure that the steps execute successfully. 

PROJECT START STEPS:

    Pre-requisites:
    1. dotnet to be installed in your system.


    Steps:
    1. To run this application, do the following:
        1.a. Go to the project root directory.
        1.b. Run the following commands to install dependencies of the app:
        	- dotnet build
        1.c. Run the following command(s) in the terminal/command line to run the app:    
            - dotnet run dotnet-in-docker.csproj
  
    
    CLOUD-IDE SETUP STEPS(follow the below steps in case you are using the Cloud IDE instead of your Local IDE):
	1. Please run the below commands from the project root to setup MySQL and MongoDB in this workspace:
	    - chmod 0755 ./database-setup.sh
	    - sh ./database-setup.sh
