# Lab Report 1



__Welcome to CSE 15l__

This is a guide which includes how to install VS Code, remotely connect to your account login into your course specific accouunt on ieng6 and try some commands. 



__Installing VS Code__

In order to install VS Code go to [here](https://code.visualstudio.com) and install the version of the program that is appropriate 
to your specific device. 

After you download VS Code, open it up and it should look something like this 

<img width="1396" alt="Screen Shot 2023-01-12 at 11 04 27 AM" src="https://user-images.githubusercontent.com/122564032/212807722-086afe79-82af-4357-9ddb-095798375162.png">

Then when you click on your account name there will be a link that should allow you to change your password.

After which you can open up VS Code and proceed to open terminal. You can locate terminal using finder/explorer on your device.



__Remote Access__

The first step is to find your specific account login which can be found [here](https://sdacs.ucsd.edu/~icc/index.php).
You can locate your login using your UCSD Username and PID or your Last Name as seen down below.

<img width="1299" alt="Screen Shot 2023-01-28 at 3 48 24 PM" src="https://user-images.githubusercontent.com/122564032/215296356-0904bc9d-c4c2-499e-98e8-d46c39ad8224.png">

Enter the following in the terminal: ssh cs15lwi23___@ieng6.ucsd.edu 
Replace the dashes with characters unique to your specific login

After logging in to the remote server you should you see something similar 

<img width="626" alt="Screen Shot 2023-01-12 at 10 46 41 AM" src="https://user-images.githubusercontent.com/122564032/212808908-26dc7ca7-2e08-4521-9295-95cdf212a2d1.png">



__Testing Commands__

There are a few commands you should explore after succesfully accessing the remote servers.

For example using the command ls- lat will return the following 

This is because ls- lat shows a list of files sorted by date

<img width="667" alt="Screen Shot 2023-01-16 at 8 40 59 PM" src="https://user-images.githubusercontent.com/122564032/212811621-64f5f876-a296-443d-a44c-3833812261ea.png">



Another command you may want to try is ls -a, it returns the following 

This is because ls -a displays hidden files not listed using the ls command

<img width="628" alt="Screen Shot 2023-01-16 at 8 39 05 PM" src="https://user-images.githubusercontent.com/122564032/212811401-1aa829f1-2ed8-409f-99af-8e00c751e1d6.png">

Another command you can use is mkdir. This allows you to make a directory. 

<img width="551" alt="Screen Shot 2023-01-28 at 4 03 56 PM" src="https://user-images.githubusercontent.com/122564032/215296781-32f5a132-787c-4ae8-a3c0-ac1f38b02654.png">

You can then change your current working directory to the directory you created by using the command cd. 
And then use the command pwd to print your current working directory.

<img width="390" alt="Screen Shot 2023-01-28 at 4 06 58 PM" src="https://user-images.githubusercontent.com/122564032/215296853-d21a7cb6-f867-4090-a947-9d341235dd13.png">





