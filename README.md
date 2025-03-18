
![GitHub Repo stars](https://img.shields.io/github/stars/harkerbyte/linux-monster?style=plastic&logo=Github)
![GitHub forks](https://img.shields.io/github/forks/harkerbyte/linux-monster?style=plastic)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/harkerbyte/linux-monster?style=plastic&logo=Github)


<a href = "https://facebook.com/harkerbyte" id="socials" >![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=flat&logo=Facebook&logoColor=white)</a>
<a href ="https://youtube.com/@harkerbyte?si=aPSIREosLJlFOmyX" >![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=flat&logo=YouTube&logoColor=white)</a>
<a href="https://whatsapp.com/channel/0029Vb5f98Z90x2p6S1rhT0S">![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)</a>
<a href="https://instagram.com/harkerbyte" >
![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&amp;logo=instagram&amp;logoColor=white) </a>

### What's new? ❄️
* Brute has now been optimised for less resource consumption. ```28, Feb ```
* <a href="#custom-dictionary">Custom dictionary generator</a> ```10, Mar ```

### Disclaimer 
<b>I disclaim responsibility of how this tool is used, users are responsible for ensuring compliance with legal and ethical guidelines. Proceed responsibly.</b>

![1000076397](https://github.com/user-attachments/assets/fbef241d-73b5-4de7-bbc8-ca678e12aa38)
### linux-monster
<b> Ethical Facebook and Gmail </b> password brute force beast... With proxy rotation for every attack based on user preference setup, you can also add your custom password list. 
Got a few more tricks in its arsenal, you should go find out. 

The codes are dynamic, ensuring the software's capability to receive updates in the future as development proceeds. 

<a href="https://youtube.com/@harkerbyte?si=bueGE1-JUuVj2uNW">Community Goal 🗿</a>
### Setup
Get the app from <a title="F-droid termux" href="https://f-droid.org/en/packages/com.termux/" >F-droid</a>

![1000076644](https://github.com/user-attachments/assets/46f61565-bdae-499e-9d93-3effb62ecb0c)

<b>Use the enter key to select.</b>
  Once that has been concluded, proceed with the following commands
  
```  
 apt update
 apt upgrade
 pkg install git
 pkg install python3
 pkg install x11-repo -y
 pkg install tur-repo -y
 pkg install chromium -y
 git clone https://github.com/harkerbyte/linux-monster
 bash setup.sh -f requirements.txt
```

[![SETUP TUTORIAL YT](https://github.com/harkerbyte/linux-monster/blob/06f6a0867368aa5b0ec853f38253da9409e1399a/data/IMG_20250302_182932.png)](https://www.youtube.com/watch?v=cc9UuUCDr4E&feature=youtu.be)
<b>Full YouTube tutorial on how to setup Linux-Monster</b>


<div id="support" >
  <h3>Support</h5>
  For users who have concluded with the installation process...
  <b>Here are the contents of the tool package and how to use it.</b>
  
  
[![Termux brute force tool - working 100%](https://github.com/harkerbyte/linux-monster/blob/06f6a0867368aa5b0ec853f38253da9409e1399a/data/IMG_20250302_183022.png)](https://www.youtube.com/watch?v=wHOM4xd9dsM)

 <p> <b>Main</b> : This is the software's power house, containing every attack job the package could possibly offer. Its interface is made simple for users to navigate. </p>
  <p><b> Global keyword - exit </b></br>
  <b>Every password found is saved in data/temps.txt</b>
  </p>
  

![1000078602](https://github.com/user-attachments/assets/cc4e1f78-0500-48b1-b67f-10cee1751ae4)

  
  <p> <b>Migrate</b> : This should be the next thing you touch, incase you have decided to enable proxy. It interface is also made simple for users to comprehend, consider it a native proxy formatter.
  
  Trust me, only this can refactor your imported proxies to a format that main.py can understand and work with.</p>

![1000078431](https://github.com/user-attachments/assets/35f9900c-f94a-4ce4-b6ba-5314d7d61c36)

  <p> <b>Server (unstable)</b> : This is specifically made for brute force attacks only when proxy is enabled. For the best performance, be sure you have provided migrate with premium proxies. Otherwise, you are likely to face proxy issues</p>
  <kbd>CTRL + C</kbd> To close server when not in use
  <table>
    <tr>
      <th>
        Pros
      </th>
      <th>
        Cons
      </th>
    </tr>
    <tr>
      <td>
        Speed : In this scenario, you're simply running a local proxy server. Which ensures equal speed and privacy, as you can monitor the logs of what requests come in and the responses that are sent out.
      </td>
      <td>
        Heavy : it consumes a massive amount of resources to keep its connections stable and accurate, which could lead to lag for low-end users, or even force quits.
      </td>
    </tr>
    <tr>
      <td>
        Interoperability: a friend of yours who is close by has the server running? You can use his/her server to save yourself a wealth of resources by making sure you both are on the same WiFi network.
      </td>
      <td>
        Heavier : as the server has to run multiple requests, this could result in increased resource usage. This could overall ruin your relationship in case you never informed the other party beforehand.
      </td>
    </tr>
    
  </table>
<p><b>Monster.log</b> : Monster.log: Here are the logs of every error encountered during attack jobs. Please make sure to provide this when reaching out to report an error that is out of scope. Possible: tracebacks. </p>

![1000079316](https://github.com/user-attachments/assets/6c8e0c71-c251-4f28-99d3-5c2a0a72593f)

<p><b>Update</b> : Run this from time to time, to make sure your copy is up to date. </p>

<p id="custom-dictionary" ><b>Generate</b> : This can be used to generate custom dictionary from given Keywords. Passwords are generated off a complex and common pattern, while the number of passwords generated can also vary based on the keywords provided.</p></br>For any dictionary generated, it's saved in the password folder from which <b>main</b> sources it passwords for attacks. </p>
<b>See this <a href="https://youtu.be/ewQfgRUeGU4?si=alPRccErnA-hwwjz" >video</a> for more clarity</b>

</div>
