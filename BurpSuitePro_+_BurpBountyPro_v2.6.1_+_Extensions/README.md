# Activated BurpSuit Professional LATEST for Linux/ Kali Linux

Prequisites
------------

#### Download Linux (64-bit) / JAR file from:

- [BurpSuit Professional / Community 2023.*](https://portswigger.net/burp/releases#professional)


Execution and Activation
------------
	
**1. Installation**

```
cd Downloads
sh burpsuite_pro_linux_v2023_7.sh

Install in /opt/BurpSuitePro/
```

**2. Place all files in the installation folder ()**
```
┌──(kali㉿gteksd)-[~/Downloads/BurpSuitePro-1.7.37-and-2022.8.5-Cracked/BurpSuitePro_+_BurpBountyPro_v2.6.1_+_Extensions/BurpSuitePro-Crack]
└─$ cp Config.Dr-FarFar Dr-FarFar.jar /opt/BurpSuitePro/
└─$ ../
└─$ cp -r  Burp-Bounty-Pro /opt/BurpSuitePro 	
```
	
**3. Open terminal in the installation directory**
```
┌──(kali㉿gteksd)--[~/opt/BurpSuitePro]
└─$ sudo java -jar Dr-FarFar.jar 
```
	
**4. Activation BurpSuitePro.**
```
After opening drfarfar
1. Click on RUN
2. Copy [license Key] (Ctrl + A) >>>> (Ctrl + C) paste it into (Ctrl + V) BurpSuitePro
3. Click Next
4. Click on Manual Activalion
5. Copy Request paste it into drfarfar [Activation Request]
6. Copy [Activation Responce] click on Paste response in BurpSuitePro
7. Next
Finish

```
	
**5. Fix Start Menu Shortcut and making script**

```
Copy the Loader command from drfarfar
┌──(kali㉿gteksd)--[~/opt/BurpSuitePro]
└─$ sudo mousepad BhurpSuthPhro
```
paste the copied command and add #!/bin/sh and save it (Ctrl + S)

#!/bin/sh

"/opt/BurpSuitePro/jre/bin/java" "--add-opens=java.desktop/javax.swing=ALL-UNNAMED" "--add-opens=java.base/java.lang=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED" `"-javaagent:/opt/BurpSuitePro/Dr-FarFar.jar"` "-noverify" "-jar" "/opt/BurpSuitePro/burpsuite_pro.jar" 

_Note: Updte Dr-FarFar.jar path_
```
└─$ sudo chmod 777 BhurpSuthPhro
```
Click START (Applications) search Burp
Right click on Burp Suite Professional
Click Edit Application...

Edit Command to ` /opt/BurpSuitePro/BhurpSuthPhro `
Save

**5. Activate Burp Suite Pro**
- 1. Modify License String like "license to GTekSD"
- 2. Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
- 3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
- 4. Copy License Request from BurpSuite_Pro and paste in keygen.jar
- 5. Copy license response from keygen.jar and paste in BurpSuite_Pro, and next and Done
	
**6. Open BurpSuit-Launcher.sh with mousepad.**
- Edit burpsuit launcher cmd as per your file path as shown in 4.2
	
**6.1 For Launching Burp in Linux, run BurpSuit-Launcher.sh file.**
```
mousepad BurpSuit-Launcher.sh
```
Paste this:
```java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:"/home/kali/BurpSuitePro/loader.jar" -noverify -jar "/home/kali/BurpSuitePro/burpsuite_pro.jar"```
Save

Run: `sh BurpSuit-Launcher.sh`
