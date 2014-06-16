ST4WA - Stream Twitter 4 WhatsApp
=====

Getting tagged twitter hashtags via whatsapp.

## Requirements ##

* python-tweepy
* python-dateutil
* python-argparse

### How to use ###

Register your application as a developer on Twitter to get the necessary keys to enter the application. 
Also register your account on Whatsapp to get the password to enter the script. 

How to get the password for Whatsapp can be seen here: 
http://unknownsec.wordpress.com/2014/06/16/monitorar-hashtags-e-palavras-do-twitter-via-whatsapp/

---

##### Keys Twitter #####

Keys to enter your Twitter, edit the file from line 14 to 17 in st4wa.py
```
consumer_key = ''                                          
consumer_secret = '' 
access_token_key = ''
access_token_secret = '' 
```

##### Login Whatsapp #####

To enter the login Whatsapp, edit the file from line 25 to 28 in st4wa.py

```
password = ""                                           
password = base64.b64decode(bytes(password.encode('utf-8')))
username = ''                                               
keepAlive= False                                            
```

### Where it was created ###

Debian GNU/Linux 7 3.2.0-4amd64
