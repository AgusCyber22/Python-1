
<h1> Python - File Access Algorithm</h1>


<h2>Description</h2>
This project consist of building an algorithm to remove some ip addresses with no longer access to restricted information and updating the access only for permitted ip address. Currently, all the allowed ip addresses are stored in “allow_list.txt”.

<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Linux</b> (VM)

<h2>Project walk-through:</h2>

<p align="center">
Open the file that contains the allowed list: <br/>
<br /> 
<img src="https://i.imgur.com/NGvZnC5.png" height="80%" width="80%" alt="Retrieve after-hours failed login attempts"/>
<br /> 
<br />
with open () => Open the file || “r” => Read file (header) || as => Create an alias for the file
<br />
<br />
<br />
Read the file contents :  <br/>
<br />
<img src="https://i.imgur.com/HY6V9WK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
# .read () => read file. <br />
<br />
Convert the string into a list : <br/>
<br />
<img src="https://i.imgur.com/RwZ96gw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
# .split => convert string to list. <br />
<br />
Iterate through the remove list :  <br/>
<br /> 
<img src="https://i.imgur.com/rVkEzBP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
for => apply specific code to a sequence || in => iterate through sequence <br />
<br />
Remove IP addresses that are on the remove list :  <br/>
<br />
<img src="https://i.imgur.com/9w0mUIn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
# .remove => remove argument <br /> 
<br />
Update the file with the revised list of IP addresses:  <br/>
<br />
<img src="https://i.imgur.com/WAGyCrQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> <br />
<br />
“\n” => new line separator || .join => convert list to string || “w” => write file (header) || .write = write file.<br />
<br/>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
