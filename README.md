# UiPathAssignment
This is the UiPath Assignment from Yujun Zhang

Before testing this script, please locate the `Send Gmail Message` activity and setup with your own SMTP email server and credentials. 

The default server setup is referring Gmail. You could change the `Host.Port` and `Host.Server` value to fit your server settings.

Use `Logon.Email` and `Logon.Password` to login to your desired email account[^1] as sender.

[^1]: Please note that some email service provider might block this login activity due to security reason and/or two-step auth. If you are using gmail, go to your account settings https://myaccount.google.com/lesssecureapps?pli=1&rapt=AEjHL4NRHXRWOvuJ7Kk3-aLaoJh8EJ83eD7joQ2j6ucDpY3DNir9uHJSUFjPvyJF6f7ASQAGbJ7BNwFU-5wdKWUqLKuR8nqf7w to enable "Less Secure App Access". **NEVER DO this on your major email account as this would significantly decrease your account security level!!!**
