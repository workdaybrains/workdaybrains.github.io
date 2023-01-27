---
layout: post
title: Workday XSLT Generator Chrome Extension
subtitle: A tool will help Workday Integration Developers
# gh-repo: daattali/beautiful-jekyll
# gh-badge: [star, fork, follow]
tags: [workday, XSLT, Generator, tool]
comments: true
---
## Introduction
An essential tool that I created to help Workday Integration Developers. Please go through and comment on this post. 

## Problem Statement
First, let me explain the problem; when you want to create an XSLT from a report and send the data through EIB, we have to spend a lot of time starting the file.

First, we need to create a start-up XSLT file, copy and paste each tag from the report definition, and write loops, functions to format dates; let's say, if there are multiple business objects on the report, then loop inside the for a loop. Ugg!

## Installation

What if a tool that does all for you?

Follow along,

First, you have to install the chrome extension from the chrome marketplace. The link is provided at the end of this post.

Once it is installed, pin the extension to the browser so that it will be handy. For that, right-click on the extension icon and click on the 'pin' option.

Now that you have successfully installed the extension and setup ready!

## How to use it?

Login to the Workday tenant and open any report which is enabled as Webservice. To open the report on the search bar, type `rd: report name`

Refresh the browser tab, and launch the extension.
{: .box-note}
**Note:** Refresh the browser tab; this will ensure the chrome extension knows this is a report definition page.

You will see options. 

* XML
* TEXT
* FIXED-WIDTH

Select one of the options and click on the Generate XSLT button. You will see the result on the extension window, copied to the clipboard.

All you have to do is create a notepad and paste the content and save it as .xslt ❤

Have you wondered Why this is not Workday out-of-box? Probably the developers have huge backlog to clear :D 

**One last important thing**: This tool works only on the report definition page; if you try to launch the extension on any other page, it will not work. The report must be open in read-only, not in edit mode.

You can install browser extension [`from here `](https://chrome.google.com/webstore/detail/workday-utilities/dfplhdepcjbplijcplkpeapjadfepfjh?hl=en-GB&authuser=0)

**Important takeaway: For better performance, use Google Chrome. Although it worked on EDGE, it does not guarantee future updates.**
