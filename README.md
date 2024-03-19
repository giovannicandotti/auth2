# auth2
TOTP second factor made easy, browser on desktop only<br>
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
