# QSL-Setup
This is a tutorial on how to install and setup QSL, a remailer client.  The client is used to send anonymous messages through remailers.  When sending emails through remailers, the sender remains anonymous and there can be no reply from the recipient.  An example why someone would want to use a remailer would be someone who wants to send an anonymous email to a police department, but does not want to become an instant suspect, which will always be the case when people injects themselves into a police investigation.

I. Download QSL here.  The download is on this line: The file you want is: QSLite-1.?.?.exe

II. Click on the QSLite-1.?.?.exe and it will ask where you want it to be unzipped.  This will  
&nbsp;&nbsp;&nbsp;&nbsp;be the folder where QSL then resides. The program will then continue with the Setup.
  
<p align="left">
  <img src="/images/QSLintro.png" width="570" height="395">
</p>
  
III. Follow the instructions on the entropy window.  
  
  <p align="left">
  <img src="/images/QSLenthropy.png" width="570" height="395">
</p>
  
IV. Click 'Create desktop shortcut' and enter anonymous@anonymous.com in the  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Email Address' box.
  
  <p align="left">
  <img src="/images/QSLemail.png" width="570" height="395">
</p>
  
V. In the 'Email Address and SMTP Host' window under 'SMTP Server', enter the free  
&nbsp;&nbsp;&nbsp;&nbsp;host 'snorky.mixmin.net'. Enter 2525 for 'Port' and  selectTLS in the dropdown box.  
  
  <p align="left">
  <img src="/images/QSLsmtpserver.png" width="570" height="395">
</p>
  
VI. Skip the next SMTP Proxy and HTTP Proxy windows and click out the Finish window.
  
VII. The main QSL window will now appear and will contain default message headers.  
To prevent any sent messages from being stored on your computer, delete the top  
'Fcc: outbox' line.  Then save the default message headers by clicking the menu  
'File'/'Save as New Message'.
  
  <p align="left">
  <img src="/images/QSLtoemail.png" width="727" height="252">
</p>
  
VIII. Message formating: There must be a space between a header : and a parameter.  There  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;must be a blank line between the Subject: line and the message that goes below it.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There must be 2 tildes ~~ after the end of the message.  

IX. Next the parameters to use for sending post to news groups is setup and saved as a templete.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Clear the QSL window and type in the headers below without the red text and note at the end.  
  
  <p align="left">
  <img src="/images/QSLnews.png" width="764" height="288">
</p>
  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Then click on menu 'File'/'Save as Templete...', name it 'News' in the box, and click OK.  Now  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;when you want to send to a new group, you can click on the Templates button on the QSL  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;interface and select News, which will bring in those headers.  You can do the reverse and put  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;the regular email parameters in Templates and save News to 'File'/'Save as New Message'.  
