# Remote Aceses

## Installing VS Code
* Follow the [Link to Visual Studio Code](https://code.visualstudio.com/)
* Then click the download button. 
![Image](Screenshot1.png)


## Remotely Connecting
* On Visual Studio Code, open a new terminal by clicking on Terminal on the top menu and then click New Terminal.
* Type in ssh cs15lsp22alf@ieng6.ucsd.edu on the newly opened terminal 
* You have now connected to the remote computer. Your terminal should look to the screenshot provided below. 
![Image](Screenshot2.png)


## Trying Some Commands
* Type in pwd on the terminal. The pwd command prints the working directory on the terminal.
* Type in ls on the terminal. The ls command list files. 
* Type in ls -a on the terminal. The ls -a command list all the files including the hidden ones. 
* Type Type in ls -a on the terminal. The ls -a command list can be used to diplay the contents of a file. 
![Image](Screenshot3.png)


## Moving Files with scp
* To move files from one computer to another, we can use the scp command on the client computer to help us do so. Type scp << file name >>  cse15lalf@ieng6.ucsd.edu:~/  in the terminal from the directory where your desired file is in on the client computer.
* If prompted type in your password, and type in ssh cs15lsp22alf@ieng6.ucsd.edu to log into the  ieng6  remote server
* Once you are remotely connected to the ieng6 computers you should be able to see the file when you type ls on the terminal of your remote server. 
![Image](Screenshot4.png)





