# auth2
TOTP second factor made easy, with just a browser on desktop.<br>
Nothing to be installed.<br>
Really.<br>
<br>
<b>TL;DR;</b><br>
An implementation for browser, ideally for desktop only, of 6-digits second factor approach.<br>
Key features:<br>
  just drag&drop or copy&paste QR code image, nothing to type.<br>
  save locally the secret, in an AES256 salted format, via a 'Master Password'.<br>
  choose between cookie and local storage, as you prefer.<br>
<br>
<b>ToDo list</b><br>
Set your own salt, or implement a method to retrieve from a server to add a security layer.<br>
Increase the 'iterations' to a decent value (e.g. 600.000 instead of current 6.000)<br>
'vectorialize' the variables which stores <i>Issuer</i> and <i>Secret</i> to save more than (current) one touple.<br>
<br>
<br>
<b>Usage</b><br>
Download the 'auth' folder and related files to a web server.<br>
Use '/auth/img/myOldTotp.png' as example picture for Case 4.<br>
<br>
![alt text](https://github.com/giovannicandotti/auth2/blob/main/demo.png?raw=true)

