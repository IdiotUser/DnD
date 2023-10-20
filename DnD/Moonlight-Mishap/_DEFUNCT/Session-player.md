---
type: session
world: <% tp.user.getThisWorld(tp) %>
campaign: <% tp.file.folder(false) %>
sessionNum: <% tp.getThisGameNum(tp) %>
location:
date: <% tp.date.now("YYYY-MM-DD") %>
fc-calender: <% tp.file.folder(false) %>
fc-date:
	year: <% tp.user.getThisDate(tp) [0] %>
	month: <% tp.user.getThisDate(tp) [1] %>
	day: <% tp.user.getThisDate(tp) [2] %>
fc-category: Sessions
long_rest: false
short_rest: false
summary " "
tags: inbox
---
# <% TP.FILE.TITLE %>
## Session Summary
> <% tp.file.title %>
> 
# Recap of Last Session

# Log
