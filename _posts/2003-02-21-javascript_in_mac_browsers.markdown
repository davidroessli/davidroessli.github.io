---
layout: post
title: Javascript in Mac Browsers
date: '2003-02-21 22:11:18 +0100'
excerpt: |-
  <b>How well do Mac browser handle Javascript?</b> A <a href="http://developer.apple.com/internet/javascript/jstests.html">recent ADC article</a> examines this question in details.

  The article presents seven scripts that test crucial bits of Javascript functionality, ranging from form field manipulation to advanced W3C DOM scripting.
mt_id: 410
blog_id: 11
post_id: 410
basename: javascript_in_mac_browsers
categories:
- daily
---
<b>How well do Mac browser handle Javascript?</b> A <a href="http://developer.apple.com/internet/javascript/jstests.html">recent ADC article</a> examines this question in details.

The article presents seven scripts that test crucial bits of Javascript functionality, ranging from form field manipulation to advanced W3C DOM scripting. The main Mac browsers are tested, Safari included.

Tests include manipulation of form field values, opening and communicate with pop-up windows, register event handlers to links, moving DHTML layers, change the display style of an element, generating form fields using the W3C DOM, and importing XML documents and showing their contents.

Mozilla executed every script with a minor bug in the DHTML test. Its unique in its ability to import XML files. Safari didn't support XML import, but succeeded in all the other tests, and appears as a strong contender.

This should be of interest to any web designer.
