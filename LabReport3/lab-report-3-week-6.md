# Lab Report 3 #

## Option 1 ##

![config](Config.PNG)

config was created and edited using notepad

![scp](scpOption1.PNG)

Here, I copied Markdownparser.java into the ieng6. Then I ssh into ieng6 and ls 
to display and confirm that the Markdownparser copy was made. 

## Option 2 ##

Option 2 required to make an access token using the ssh server. This involved generating a key using `ssh-keygen` on the ieng6 server and adding that public keys contents to Githubs keys. Below is the public githubKey


![publicKeyGithub](publicKeyGithub.PNG)

After making the keys, both public and private keys were stored in a file called .ssh on my ieng6 server. Below is both those private and public keys with the private being called githubKey and the public key called githubKey.pub


![privateKey](privateKey.PNG)

In Lab 6, we produced many changes such as adding makefile and the shell script mdparse. Below I enter the server and add, commit, and push origin main these changes to the github. 


![lab6Change](Lab6Changes.PNG)
![lAb6Change](LAb6Contin.PNG)

below is the link for these changes on the github repo

[Github Changes Link](https://github.com/lithicarus/markdown-parser/commit/633b5e40a21d96cd1b96fa30b4d163ded2a49ca1)




## Option 3 ##

Option 3 has us copy files into our ieng6 server recursively using the command 

`scp -r . cs15lsp22@ieng6.ucsd.edu:~/markdown-parse`

This will copy all the files into a new directory named markdown-parse. Below are the images of this running as well as the running of the Markdown files in the ieng 6 server

![image](SCPOption3.PNG)
![image](Option3Confirm.PNG)

You can conveniently do this in one line as well. Since I'm using windows, I had to delete all the class files and change the conventional javac and java lines. Below is it running on one line. 

![image](OneLine.PNG)


