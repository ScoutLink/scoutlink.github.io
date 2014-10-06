---
layout: post
title: HowTo redirector module
created: 1287053839
categories:
- techteam
- tech team
- joti 2010
---
<p>&nbsp;This is a short how to how the redirector works. Please don't bother us about wrong grammar, it is so short before JOTI. Thanks for megalive for writing it.</p>
<p>&nbsp;</p>
<p>The script basicly has two segments which you have too look at</p>
<p>
<meta content="text/html; charset=utf-8" http-equiv="content-type">  </meta>
</p>
<p>1 the main channel<br />
2 the channels people get placed in</p>
<p>1 the main channel</p>
<p>In the mail channel you have too set with +L two digit number.&nbsp;<br />
ie /mode #english +L 60.<br />
This will create 60 sub channels. every non ircop user which tries too join #english will get forwarded too a good sub channel.</p>
<p>2 Sub channels</p>
<p>A channel looks like #english##. #english01 is the first channel. #english02 is the second channel.<br />
A sub channel, where users should be able too join, has no key or invite only set but just +l number.<br />
when you join the main channel the script tries too put you in the first free subchannel. A free channel means there are more then 10 places free in the channel.&nbsp;<br />
if you set a channel +l 60 the script will fill it till 50 and then go the nex avaible channel.<br />
If a channel which is keyed or invite only it is not available, this means it will not get users in it.</p>
<p>A channel which get fille can have set the following modes /mode #english01 +ntl 60&nbsp;<br />
A channel that does not get filles have set the following modes /mode #english +ntlk 60 keyd or /mode #english +ntli 60</p>
<h2 style="font-family: 'Trebuchet MS',Verdana,sans-serif; font-size: 16px; padding: 2px 10px 1px 0px; margin: 0px 0px 10px; border-bottom: 1px solid rgb(187, 187, 187); color: rgb(68, 68, 68);" id="how-too-use-it-in-short">how too use it in short</h2>
<p>Set on the main channel mode +L and the amount of subchannels</p>
<p>Create the amount of the subchannels and places there a mode +sntli 60 on them.</p>
<br />
<p>when  you want too use a sub channel remove the &quot;si&quot; modes. Now channel gets  50 users in it when those users try too join the main channel</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
