# AzoDecrypt
This script is able to decrypt POST requests which are sent to AzoRult Server. One way to save those requests is with Burp Suite with which you are able to save out the requests to file:

Rightclick > Copy to file

The use azo_decrypt.py <inputfile> <output_file> to decrypt the request. Please note, that a normal C2-Traffic contains of two POST-Requests. One short "Check-In" and afterwards a bigger request with the Credentials, Cookies etc.
  
![alt text](https://github.com/hariomenkel/AzoDecrypt/raw/master/screenshot.PNG)

This should give you a file like this:

![alt text](https://github.com/hariomenkel/AzoDecrypt/raw/master/screenshot2.PNG)

This file can then be used as input which should produce the decrypted output saved as file:

![alt text](https://github.com/hariomenkel/AzoDecrypt/raw/master/screenshot3.PNG)

  

  


