---
layout: post
title: Swordfish FAQ
created: 1279007822
categories:
- techteam
- tech team
---
<p>&nbsp;This will be the FAQ Document. I'm starting collecting things here:</p>
<h4>I want to change my Hostname (IRCOPS only)?</h4>
<p>This is now handled via HostServe, try <span style="font-family: 'Courier New'; ">/msg HostServ HELP&nbsp;</span>for more information about it.</p>
<h4>Where can i change my operator password (IRCOP only)</h4>
<p>Go to&nbsp;<a href="http://sco.scoutlink.net/sco/">http://sco.scoutlink.net/sco/</a>&nbsp;and login there with your current password.</p>
<p>You can change your password then on &quot;Profile&quot;. Please note: The password is changed immediately on the wbeinterface but it may take up to 24 hours till it is changed on all servers, so you maybe need to use your old one for that time.</p>
<h4>The stats X command is no more availlable</h4>
<p>This is no more needed as the new Network relinks automatically. Anyway it is no more supported by the ircd.</p>
<p>
<meta http-equiv="content-type" content="text/html; charset=utf-8">
<meta http-equiv="content-type" content="text/html; charset=utf-8">       </meta>
</meta>
</p>
<h4>&nbsp;The stats O command is no more availlable</h4>
<p>This exposes the the allowed Hosts for ircops. There is now an SNOMASK Parameter that let's you see why an opering attempt failed. These are +s oO</p>
<h4>Every change on Channel Flags is promoted to the whole channel by ChanServ</h4>
<p>You can change this if you are channel admin:</p>
<p><span style="font-family: 'Courier New'; ">/msg chanserv help set verbose</span></p>
<p>gives you detailled info about it. You can also set only ops get notified.</p>
<h4>Is there any documentation?</h4>
<p>Yes. For our services you can find it at:&nbsp;<a href="http://www.stack.nl/~jilles/irc/atheme-help/">http://www.stack.nl/~jilles/irc/atheme-help/</a></p>
<p>For our ircd have a look at:&nbsp;<a href="http://wiki.inspircd.org/Introduction">http://wiki.inspircd.org/Introduction</a></p>
<p>Please note: Not all functions described there are also availlable on ScoutLink or may require special privileges. Also HATT is working on an updated documentation especially for ScoutLink</p>
<h4>My nick is not availlable i can't use it. It is hold by NickServ Enforcer</h4>
<p>This is a security function to prevent other users from using your nick. If your nick is currently secured by the enforce use <span style="font-family: 'Courier New'; ">/msg nickserv RELEASE &lt;nick&gt; [password]</span>&nbsp; to release.<br />
We will change the default behaviour in future. So the enforce flag is disabled by default and you can enable it if you want it. You can get more info about it with&nbsp;<span style="font-family: 'Courier New'; ">&nbsp;/msg nickserv help set enforce</span>&nbsp;</p>
<h4>What happened to the /ircops command</h4>
<p>This is no more availlable. But there is now a Website where you can see which operators are currently online:&nbsp;<a href="http://scoutlink.net/node/343">http://scoutlink.net/node/343</a></p>
<p>
<meta http-equiv="content-type" content="text/html; charset=utf-8" /></p>
