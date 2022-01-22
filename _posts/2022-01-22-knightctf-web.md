---
title: KnightCTF Web Writeups - Part 1
author: gokulap
date: 2022-01-22
categories: [web]
tags: [web, ctf]
---

# Knight CTF Web Writeups



 #### Hello CTF Players !
 Lets See the Web Writeups of KnightCTF 2022
 
 <img src="https://oshi.at/xZhV/all.jpeg"></img>
    
 ## 1. Something you need to look wayback 
<center> 
<img src="https://oshi.at/RYRh/1.1.png"></img>
</center>
 
 Given The Link of the site Let's open it 
 
 <center> 
<img src="https://oshi.at/htLJ/1.2.png"></img>
</center>
 
 This Site Looks like a static site and no links are working in it, Its just a Fake static HTML Page
 , Lets look at that source code of the page
 
<center>
<img src="https://oshi.at/dSAf/1.3.png"></img>
</center>

In the source code we can see the github repo link, Lets open it in new tab, But as usual there is no info here and looked at all the source files in that repo but no Flag here !!
<center>
<img src="https://oshi.at/Uhft/1.4.png"></img>
</center>

Then Remembered the Title of this challenge `Need to look wayback` Suddenly checked the Commit history of that Repo, Yay Flag is in the commit history !

<center>
<img src="https://oshi.at/iGjc/1.5.png"></img>
 </center>
 
 > Flag : KCTF{version_control_is_awesome}

<hr>

## Do Something Special 
 
 
    