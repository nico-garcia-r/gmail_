# Gmail
  
Module to perform actions in Gmail  

*Read this in other languages: [English](README.md), [Portugues](README.pr.md), [Español](README.es.md).*

## How to install this module
  
__Download__ and __install__ the content in 'modules' folder in Rocketbot path  


## How to use this module
To use this module we will have to make the following configuration in our Gmail account:
1. Go to the "Manage your Google Account" section.
2. Then we will go to the section of "Security" that is in the left panel.
3. Activate two-step verification
4. In the "Access to Google" option, access Application passwords.
5. In "Select application" we place 'Other' and assign it a name to identify it.
6. We click on the Generate button and copy the generated application password.
7. In the gmail_ module we place the chosen email and as password we use the generated application password.


## Overview


1. Server Configuration  
With this command we enable the execution of other commands, configuring the server with our mail and password.

2. Send Email  
Send email, before you must configurate the server

3. List all emails  
List all email, you can specify a filter

4. List unread emails  
List all unread emails, you can specify a filter

5. Read email for ID  
Reads an email by ID and gets all email data, the message body and its attachments

6. Reply email for ID  
Reply to an email by its ID, having the possibility to add a message body and attachments.

7. Create Label  
Create a label in Gmail, where we can move our mails having the behavior of a folder.

8. Move email to label  
Move an email to a label. We must take into account the ID of the email to move and the name of the label.

9. Mark email as unread  
Mark email as unread indicating its ID

10. Close Server  
Close server connection

11. Forward email for ID  
Forward email by ID. We indicate the recipient(s) to whom to forward the email and the possibility to change the subject.

12. Download attachments for ID  
Downloads email attachments and saves them in a folder  



### Changes
Wed Feb 17 13:47:47 2021  Merge branch master of https://github.com/rocketbot-cl/gmail_

Wed Sep 2 10:43:37 2020  Merge branch master of https://github.com/rocketbot-cl/gmail_

Fri Nov 15 15:36:49 2019  Merge branch master of https://github.com/rocketbot-cl/Gmail

Tue Nov 5 14:32:16 2019  Merge branch master of https://github.com/rocketbot-cl/Gmail

----
### OS

- windows
- mac
- linux
- docker

### Dependencies
- [**mail-parser**](https://pypi.org/project/mail-parser/)
### License
  
![MIT](https://camo.githubusercontent.com/107590fac8cbd65071396bb4d04040f76cde5bde/687474703a2f2f696d672e736869656c64732e696f2f3a6c6963656e73652d6d69742d626c75652e7376673f7374796c653d666c61742d737175617265)  
[MIT](http://opensource.org/licenses/mit-license.ph)