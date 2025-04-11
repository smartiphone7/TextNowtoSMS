# TextNowtoSMS

# What does this guide do?
This guide will help you export your TextNow messages (Text messages, images, videos, voice messages and voicemails) and add them to your native Android messaging app.

# Exporting text messages from TextNow
To export your messages from Textnow, you'll have to open the TextNow app, go to a message thread, click the three dots in the top right corner, and click "Export Conversation". Unfortunately there's no way to export all your message threads together, so you'll have to do this manually for each conversation you have and then transfer all the exports to your PC. 

Note: Only export threads where you got a reply. Message threads where the recipient(s) did not respond will not work due to how TextNow formats its exported files.

![image](https://github.com/user-attachments/assets/37a2f5df-0b77-4557-829e-f026a62a0ea5)

What I did to transfer everything to my PC was shared each export to my "Saved Messages" in the Telegram app, while I also had Telegram Desktop open on my PC, which was set up to auto-download each message it recieved and put it in my Downloads folder. Feel free to use this method or any other method. 

After you have all the exported .html files on your PC, make a new folder on the PC and put the files in it. 

# Converting the exports
Now we will change the exports into a format the app "SMS Backup & Restore" can read. This is so we can import the files into the native Android SMS app. 

Download this github repo as a zip file. Unzip the folder, and right click the .exe file.

![image](https://github.com/user-attachments/assets/90e586c6-fdd7-4246-8865-6a51d5670b7d)

Select properties, and then click on unblock. Double click the .exe file to run the program. (You may need to [disable real time protection on Windows Defender](https://support.microsoft.com/en-us/windows/virus-and-threat-protection-in-the-windows-security-app-1362f4cd-d71a-b52a-0b66-c2820032b65e) for the program to run correctly)

![image](https://github.com/user-attachments/assets/a8e30cf4-0cc9-4125-b5ac-ee6f4deb8f5a)

In the first box, click on "Browse" and select the Input Folder Path. This is the folder we made earlier with all the TextNow exports.
In the second box, enter your phone number in the format "+1XXXXXXXXXX" (replace the X's with your actual number.)
In the third box, click "Browse" and select the Output File Path. This will be the folder you want to export the file with your text messages to.
After filling in the info, click "Convert" to run the converter. This might take a while. 

Note: If the exports fail to complete, try splitting the Input Folder so that they only have 100 files per folder.

# Importing the exported file 
After the converter finishes, send the file(s) from your PC back to your phone (I used Telegram for this but any file transfer method should work). Now we will need to download an app called [SMS Backup & Restore](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore).

Once you install the app, click "Get Started" and allow the permissions it asks for. Then, click the hamburger menu in the top left corner and click "Restore".
![image](https://github.com/user-attachments/assets/5a637a4f-2327-47dd-ad38-c1db6e4b52f2)

After that, click "Local Backup Location". 

![image](https://github.com/user-attachments/assets/16d6cad6-0e96-48b3-a606-317bfa357982)

It should automatically find the file. If not, manually select it. Don't change any options on this screen and click "Restore". 

![image](https://github.com/user-attachments/assets/9308e3f1-5750-45e3-abde-ddc44c35a6aa)

It should ask you to change the default SMS app so that it can restore the files. Click "OK" and change the default SMS app to "SMS Backup & Restore".

![image](https://github.com/user-attachments/assets/6c581575-2f4c-415b-ac31-710250303850)

After it finishes restoring the files, open your default SMS app (I use Google Messages). It should prompt you to switch your SMS app. Click "Set as default" and you should be done! Your messages might take a while to load but they are now in your Android filesystem!

![image](https://github.com/user-attachments/assets/c24f5abf-aeb2-4945-88f0-35ebcaea284d)

# Known Issues

While group chats will import, they won't show up as a group chat. TextNow assigns a random phone number to group chats so all recieved messages will be shown as they came from that number.

# What if I use an iPhone?

You can get an old Android phone or tablet for pretty cheap. If you install the TextNow app on it all your messages should sync, and then you could follow this guide normally. Unfortunately TextNow doesn't offer an option to export chats directly on iPhone. 

# Credits

Guide written by smartiphone7
TextNow to SMS program developed by Hamad Saquib (WhatsApp: +92 317 2772704)

If you need any help or support you can either send a message to me at +1 (415) 500-0385 or send a Reddit DM to u/smartiphone7.

