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

```
	
**3. Open terminal in the installation directory**
- Type cmd in the folder's path and hit ENTER
```
cd /home/kali/BurpSuitePro
```
	
**4. Run This Command in opned CMD Prompt.**
		
**4.1. Use keygen.jar to generate the License key**

```
java -jar keygen.jar
```
	
**4.2. Use BurpSuit**

```
java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:"/home/kali/BurpSuitePro/loader.jar" -noverify -jar "/home/kali/BurpSuitePro/burpsuite_pro.jar"

```

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
