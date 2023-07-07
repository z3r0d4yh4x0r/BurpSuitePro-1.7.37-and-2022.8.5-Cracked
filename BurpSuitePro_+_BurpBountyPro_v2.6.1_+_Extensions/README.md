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
Next>Next>Next>Next
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
1. Click on 'RUN'
2. Copy '[license Key] (Ctrl + A) >>>> (Ctrl + C)' paste it into (Ctrl + V) BurpSuitePro
3. Click 'Next'
4. Click on 'Manual Activalion'
5. 'Copy Request' paste it into drfarfar '[Activation Request]'
6. Copy '[Activation Responce]' click on 'Paste response' in BurpSuitePro
7. 'Next'
Finish

```
	
**5. Making script**
```
Copy the 'Loader command' from drfarfar
┌──(kali㉿gteksd)--[~/opt/BurpSuitePro]
└─$ sudo mousepad BhurpSuthPhro

paste the copied command and add '#!/bin/sh' and save it (Ctrl + S)

#!/bin/sh

"/opt/BurpSuitePro/jre/bin/java" "--add-opens=java.desktop/javax.swing=ALL-UNNAMED" "--add-opens=java.base/java.lang=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED" `"-javaagent:/opt/BurpSuitePro/Dr-FarFar.jar"` "-noverify" "-jar" "/opt/BurpSuitePro/burpsuite_pro.jar" 

_Note: Updte -javaagent:Dr-FarFar.jar path_
```

**6. Fix Start Menu Shortcut**
```
└─$ sudo chmod 777 BhurpSuthPhro

1. Click START (Applications) search 'Burp'
2. Right click on 'Burp Suite Professional'
3. Click 'Edit Application...'

Edit 'Command:' to ` /opt/BurpSuitePro/BhurpSuthPhro `
'Save'
```

**DONE**
