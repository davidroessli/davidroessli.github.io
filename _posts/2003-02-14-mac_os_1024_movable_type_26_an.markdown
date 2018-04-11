---
layout: post
title: Mac OS 10.2.4, Movable Type 2.6 and Kung-Log 1.3
date: '2003-02-14 09:34:17 +0100'
excerpt: Happy Valentine's! Woke up to discover that SW offered <a href="http://docs.info.apple.com/article.html?artnum=107362">Mac
  OS 10.2.4 update</a>, and that <a href="http://www.movabletype.org/download.shtml">Movable
  Type 2.6</a> had been released together with <a href="http://www.kung-foo.tv/kunglog.php">Kung-Log
  1.3</a> (requires MT 2.6).
mt_id: 399
blog_id: 11
post_id: 399
basename: mac_os_1024_movable_type_26_an
categories:
- daily
---
Happy Valentine's! Woke up to discover that SW offered <a href="http://docs.info.apple.com/article.html?artnum=107362">Mac OS 10.2.4 update</a>, and that <a href="http://www.movabletype.org/download.shtml">Movable Type 2.6</a> had been released together with <a href="http://www.kung-foo.tv/kunglog.php">Kung-Log 1.3</a> (requires MT 2.6).

<b>15h20 CET update</b>: well, all went smoothly. I was actually updating MT while the SW Update was downloading and optimising 10.2.4 in the background.
I haven't dived into all the new features of MT 2.6 yet, because <b>Kung-Log 1.3</b> withheld all my attention. This program is really a gem. I believe I can do over 95% of my weblogging directly from Mac OS X now.

The <b>image upload</b> function and the <b>ping box</b> are really cool.

The <b>e-mail notification</b> puzzled me for a while as the outgoing mail was sent through .Mac's smtp server, but not with my .Mac address - so it failed each time. Adriaan shed some light on the outgoing server setting: it is simply taken from the Internet -> e-mail pane (mine was still set to my .Mac account). Nevertheless, the <i>From</i> address is the first account setup in Mail.app. If you take a look at Kung-Log's preferences (~/Library/Preferences/kungfoo.tv.kung-log.plist) you'll notice that the first section "Mail Account" contains all the mail accounts you've setup. Apparently, the OS inserts that info. IMHO. the glitch is that (1) you can't choose you outgoing personnality (my weblogs have different ones), (2) the SMTP server global setting is taken into account, but not the e-mail address.
Nothing to really worry about.
