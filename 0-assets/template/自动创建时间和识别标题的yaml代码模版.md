---
due: <% tp.date.now("yyyy-MM-DD") %> 
<%* let title = tp.file.title 
if (title.startsWith("Untitled")){ title = await tp.system.prompt("Title"); await tp.file.rename(title); } %>
title: <% title%>
tags: 
---


