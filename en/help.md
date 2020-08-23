# We invite you to join the python tutorial writing team!

> We invite you to join the python tutorial writing team!

This project, initiated by me, is dedicated to writing tutorials for people who have no experience in Python writing, so as to provide reference for developers who need to learn Python tutorials in China.  
As the project is relatively large, we hope that like-minded friends will work together with us.  
See below for the method of addition.  
As this project uses GitHub for code hosting and version management, you need to use git tools to keep up with us.  
If you do not have git client installed, please go to git website to download and install official git client.  
If you don't have a GitHub account, please go to GitHub's official website to register one.  
Please send me an email（ 2841306779@qq.com ）, which indicates your GitHub account name.  
After reading, I will reply to you and send cooperation application on GitHub. Please check.  
You can continue with the following steps while waiting for the results.  
Find a convenient folder to store all the files of the website. You will start offline here.  
The folder doesn't have to be empty, because the data will be stored in subfolders.  
Go to this folder, open the right-click menu and select git bash here.  
A command line window will pop up. Wait for the program initialization to complete and type a line ending with $in the window, enter the following command.  
Press enter after copying and pasting each instruction.  
```git clone https://github.com/jonathanqwq/python-class.git```  
Due to the large amount of data, please wait a moment. It may take a while.  
After completion,execute ```git remote -v```, and confirm that the text is echoed. If automatic addition is normal, it should be displayed as follows:  
```origin https://github.com/jonathanqwq/python-class.git  (fetch)```  
```origin https://github.com/jonathanqwq/python-class.git  (push)```  
If not, you need to add the remote site manually. Execute the following instructions.  
```git remote add origin https://github.com/jonathanqwq/python-class.git``` 
```git init``` 
After that, execute ```git remote -v``` again, and the normal remote site information display should appear.  
OK, the setup is complete. Contact has been established with the remote code base.  
Next, enter the following three instructions. Press enter after copying and pasting each instruction.  
```git config --global  user.email  "Change to your registered email, do not remove the quotation marks" ``` 
```git config --global  user.name  "Change to your registered user name, do not remove the quotation marks"```  
Go to the python class folder, open the right-click menu and select git GUI here.  
To facilitate our later operations, please select Tools > add in the top menu and fill in the following contents in the dialog box. The name column is optional. Then click Add.  
Select Edit > Options in the top menu, click the two buttons shown in the figure, and select Unicode (utf8) in the pop-up drop-down box. This will solve the problem of garbled Chinese.  
Use your preferred web page editing software to modify it directly. No networking is required.  
When editing, please pay attention to save as UTF-8 text coding format without BOM.  
Please note that this tutorial is written in docsify and you need to go first https://docsify.js.org/#/ Learn more about docsify.  
When using ```npm i docsify-cli -g```, please install node.js 。  
You must accept the cooperation invitation before you can upload it. If not, please wait.  
After writing, enter the python class folder, open the right-click menu and select git GUI here.  
As shown in the figure, first click rescan to search for the changed file. You can see that the changed file appears in the upper left corner. Then click the state changed flag to change the state and you can see them move to the lower left corner. Next, write a line of submission information in the large text box (i.e. what you did, start with the verb directly, without the past tense words such as "Le"), then click commit to submit the change, and push to upload the change.  
When you click push, the push branches dialog box will pop up. Regardless of the user, click push again in the lower right corner.  
You may log in to GitHub and log in directly.  
Sometimes when you click push, it will fail, and a dialog box will pop up with the word "fast forward".  
This is because after your last submission and before this submission, other members have also modified the online documents, making your local code and online code out of sync. In this case, click the list item you added in step 7 in the tools menu to pull the online code update to local. Then you can click push again.  
In fact, we recommend that you perform a pull-down operation every day before starting work to keep you in sync.  
In the worst case, an error will also be reported when you click pull. The error will contain the word conflict, which indicates that you and another person have "collided" - translating the same document in different directions at the same time. After clicking OK, the software will automatically display the conflicting documents and the modified contents in different modification directions.  
You can compare these contents and select use remote version (according to the remote version), or use local version (according to your local version), or open the file and manually modify it to write a version with the advantages of both versions, and then select use local version. After all modification, press commit and push to correct the error.  
Due to network reasons, there may be some other errors. For other error messages, you can try again several times. If you can't do anything, please contact other members  