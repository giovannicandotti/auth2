# auth2

TOTP second factor made easy, with just a browser on desktop.

Nothing to be installed.

Really.


**TL;DR;**

An implementation for browser, ideally for desktop only, of 6-digits second factor approach.


**Key features**:
  * just drag&drop or copy&paste QR code image, nothing to type.
  * save locally the secret, in an AES256 salted encrypted format, via a 'Master Password'.
  * use a popup to avoid browser storage of Master Password.
  * choose between cookie and local storage.


**ToDo list**
 * Set your own salt, or implement a method to retrieve from a server to add a security or control layer.
 * Increase the 'iterations' to a decent value (e.g. 600.000) instead of current 6.000 (set to avoid waiting whilst showing how to do).
 * 'Vectorialize' the two variables which stores _Issuer_ and _Secret_ to save more than (current) one touple.
 * Setup a minimum complexity check for Master Password.


**Usage**

Download the 'auth' folder and related files to a web server.

Use 'auth2/img/myOldTotp.png' as example picture for Case 4.

![alt text](https://github.com/giovannicandotti/auth2/blob/main/demo.png?raw=true)

