---
title: setup your website locally
weight: -14
---
#### we will go through steps some I will explain in details  and Some I will leave you Documentaion to understand from it 

### 1- install Hugo 
-to begin you should install Hugo you shoulf see this totourial at frist before you continue with me 
https://gohugo.io/getting-started/installing/

- choose the best download way you prefere 

- choose the latest version of Hugo

{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/1-wowl.png)](/media/1-wowl.png)
<---> <!-- magic sparator, between columns -->
[![Example file-tree menu](/media/2-wowl.png)](/media/2-wowl.png)
<---> <!-- magic sparator, between columns -->
[![Example file-tree menu](/media/4-wowl.png)](/media/4-wowl.png)
{{< /columns >}}

### 3- prepare your environment 
- to prepare your environment you should see the link that I mentioned up but any wayI will explain 

- open windows start menue > search on "Edit the system environment Variables"

{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/5-wowl.png)](/media/5-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- choose Advanced and click on Environment Variables Button" 
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/6-wowl.png)](/media/6-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- Click on path and Click Edit 
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/7-wowl.png)](/media/7-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- click on new and type "C:Hugo\bin
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/8-wowl.png)](/media/8-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

{{< hint info >}}
**note**\
you should build a folder in C called "hugo" and another one in it called "bin"
and uncompress the Hugo files if you downloaded like i Did
{{< /hint >}}

### 4- Follow the fowllowing totourial 
https://gohugo.io/getting-started/quick-start/

{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/9-wowl.png)](/media/9-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- open your prompt and creat folder to your site (name it any thing)
By the following code ```hugo new site (the name)```
 {{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/10-wowl.png)](/media/10-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- you will see that the folder created in C:\Users\User\(name of your folder)
 {{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/11-wowl.png)](/media/11-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- you should download a theme and put it in theme directory
 {{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/12-wowl.png)](/media/12-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- for me I download a theme from hugo site
https://gitlab.com/pages/hugo/-/tree/master/themes
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/13-wowl.png)](/media/13-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}


{{< hint info >}}
**note**\
these not the themes I made in my project but you can
use any theme you like
{{< /hint >}}

### 5-Build the local website 
- after you finish all the steps you should open your 
prompt and type the following code ```cd (name of the folder)```

{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/13-wowl.png)](/media/13-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

- then you can build your website now on your computer by the following
command on prompt ```hugo server -D```
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/16-wowl.png)](/media/16-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

{{< hint danger >}}
**look out!**\
if you didn't put a theme in the folder it will appear 
a blanck website
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/17-wowl.png)](/media/17-wowl.png)
<---> <!-- magic sparator, between columns -->
{{< /columns >}}

{{< /hint >}}

### 6- the website is done 
- now every thing is good after you press the command ```hugo server -D``` you can 
access to your website locally deo
{{< columns >}} <!-- begin columns block -->
[![Example file-tree menu](/media/18-wowl.png)](/media/18-wowl.png)
<---> <!-- magic sparator, between columns -->
[![Example file-tree menu](/media/19-wowl.png)](/media/19-wowl.png)
{{< /columns >}}
