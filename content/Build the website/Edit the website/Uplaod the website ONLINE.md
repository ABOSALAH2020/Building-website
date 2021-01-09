---
title: Uplaod the website ONLINE
weight: -10
---
### If you apply my method of making the website 
(https://abdelrahman_salah1.gitlab.io/Build-the-website/My-Way/setup-your-website-locally/)

### then this totorial for you ,but if you are apply the standerd method then congratulation you finshed you website already , and you can go throw the Errors Page to see if there is any mistake you had made or solving a problem you had faced

{{< expand "Creat project on gitlab" "..." >}}
## creating blank project in git lab
to upload your website in gitlab hosted server you need to 
creat a new project in gitlab and build your own repository 
go to gitlab and choose creat project and name it with any name you want 

[![HC-primary Color Scheme](/media/1-htui.png)](/media/1-htui.png)
 
{{< /expand >}}


{{< expand "Attatch it to your computer" "..." >}}
## Use source tree

In order to make edits on your website, you have to make a clone on your PC. To do so you will
 need a software called sourcetree which is a gui tool for git. We will use sourcetree to make a
 clone of your website, commit and push the changes to gitlab. Please follow the following steps
 to setup sourcetree and configure it with your gitlab account.


<!-- spellchecker-disable -->
{{< toc >}}
<!-- spellchecker-enable -->

### Install sourcetree
● Install sourcetree (git gui for windows). https://www.sourcetreeapp.com/
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/sourceTree.png)](/media/sourceTree.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}


### Use sourcetree
Use sourcetree (Tools->launch ssh agent) to create ssh key
1. To generate an SSH Key, select Tools > Create or Import SSH Keys. This window should pop up:
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/ssh1.png)](/media/ssh1.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}



2. Click Generate, and move the mouse randomly until a key is generated:
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/ssh2.png)](/media/ssh2.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}


3. A public key and a private key should appear. Save them both by clicking Save public key (save as .pub filetype),
and Save private key (save as .ppk filetype):
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/ssh3.png)](/media/ssh3.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}


4. This is how the .pub and the .ppk files should appear in your .ssh folder, along side with some other files:
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/ssh5.png)](/media/ssh5.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

SourceTree might prompt you to load the private key. Simply load the .ppk file.

5. Add your public key in your remote server (eg. Bitbucket).
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/ssh4.png)](/media/ssh4.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}


### Add the ssh key
To set up your SSH key, perform the following steps.


1️⃣ Open GitLab and go to your account settings.
[![Example file-tree menu](/media/ssh6.jpg)](/media/ssh6.jpg)

2️⃣ Click on SSH.

3️⃣ Click on Add SSH Key.
[![Example file-tree menu](/media/ssh7.jpg)](/media/ssh7.jpg)

4️⃣ To get information about your SSH key, enter the following command in your terminal. If you're using Windows, go to step 7:
```
$ cat ~/.ssh/id_rsa.pub
```
5️⃣ You should copy the entire content of the output in step 4, as shown in the following screenshot:
[![Example file-tree menu](/media/ssh8.jpg)](/media/ssh8.jpg)

6️⃣ If you're not using Windows, you can move to step 11.

7️⃣ Open the Windows explorer and move to C:\Users\your_username\.ssh.

8️⃣ Right-click on id_rsa.pub and click on Open.

9️⃣ When asked for the program you want to use, select Notepad.

🔟Select the entire content of the file that contains the SSH key.
[![Example file-tree menu](/media/ssh9.jpg)](/media/ssh9.jpg)


11 We now paste the content of the SSH key into the form in your GitLab instance. You can name the SSH key anything you want. It is recommended that you name it after the computer it came from. This way, it will be easier to know which key belongs to which machine. If you leave the name field empty, GitLab will generate a name for you.

12 Now, click on Add Key.


Now you can put all the files you have about your website (locally) and push it to the website online.

[![Example file-tree menu](/media/3-htui.png)](/media/htui.png)

{{< /expand >}}

{{< expand "Making public link" "..." >}}
## change your base URL 
in order to have the public link you should follow the nect steps 

### 1- go to your config.yaml and change the base URl to ```https://user_name.gitlab.io```

[![Example file-tree menu](/media/5-htui.png)](/media/5-htui.png)

### 2-push the change to your website 

[![Example file-tree menu](/media/6-htui.png)](/media/6-htui.png)

### 3- go to gitlab sittings >> Change path
### and change the exsist with  ```https://user_name.gitlab.io``` 
{{< columns >}}
[![Example file-tree menu](/media/7-htui.png)](/media/7-htui.png)
<--->
[![Example file-tree menu](/media/8-htui.png)](/media/8-htui.png)
{{< /columns >}}
### 4- take the link ```https://user_name.gitlab.io``` and paste it in your browser 

[![Example file-tree menu](/media/9-htui.png)](/media/9-htui.png)
{{< /expand >}}