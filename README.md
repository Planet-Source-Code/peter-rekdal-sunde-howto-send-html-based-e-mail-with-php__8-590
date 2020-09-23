<div align="center">

## Howto send html based E\-mail with php


</div>

### Description

Teaches you howto send html based E-mail with php
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Peter Rekdal Sunde](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/peter-rekdal-sunde.md)
**Level**          |Beginner
**User Rating**    |4.2 (25 globes from 6 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__8-9.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/peter-rekdal-sunde-howto-send-html-based-e-mail-with-php__8-590/archive/master.zip)





### Source Code

<html><head>
<p><b>How to send mime enchased content (html) by E-mail. (Windows/Linux/UNIX).</b><br>
<br>
<b>Pretext:</b><br>
<font face=verdana size=1>This howto covers how you can send html based E-mail(s) by using php.<br>
When I started out with php, one of the first things I wanted to learn was how<br>
to send html based (E-mail) to my friends. I’m not going to bother you with<br>
my life experience with php, so let’s start.<br></font>
<br>
<b>Content: (what this howto covers).</b><br>
<br>
Pretext<br>
Setup<br>
Examples<br>
FAQ<br>
<br>
<br>
<b>Setup:</b><br>
<font face=verdana size=1>When I first started programming php, I thought you needed to have many packages/software
installed on your computer to run all features that comes with php.<br>
Well you don’t, all you need is, php3, apache and a mysql engine (optional).<br>
If you already have php and apache installed, then you can scroll down to read
the rest of this howto. If you don’t got the software/packages mentioned above,
then you need to install them.<br></font>
<br>
<b>Examples:</b><br>
<font face=verdana size=1>I’ll skip the boring part, and I’m assuming you have some php knowledge.<br>
<br>
You can download this <a href="http://www.zargate.org/example.zip">file</a> as an example.
</b>
<br>
After you've downloaded this file, you extract it into your htdocs/ folder or whatever folder you may use as your default webcontent excutable folder.
<br>
</font><b>FAQ:</b><br>
<b>1.</b><font face=verdana size=1>Does my friends/users E-mail client accept all html code?<br>
Unfortunately, not all E-mail clients can view html code.<br>
Ie, Microsoft Outlook 6.0 can’t view Macromedia Flash code.<br>
But that’s another thing.<br></b>
<br>
<b>2.</b> <font face=verdana size=1>Can I put all kinds of html inside the body tag?<br>
Yes, you can but remember not to have any “” (quotes) inside the $body tag.<br>
If you’re html contains “” (quotes) you need to replace them.<br>
Ie, $body = “"my link.php" this is my link</a>”; <br>
That will generate an error in the php engine.<br>
But if you replace it with $body = “\my link.php\ this is my
link</a>”; then php engine will accept it. The current function is called (“stripslashes”);<br></font>
<br>
<b>This bad howto was written by Peter Rekdal Sunde aka Exion.<br>
I created this howto within an 30 minutes.<br>
I realize that it is full of “bad spellings” but I don’t care because you can
still learn from it.</b></p>

