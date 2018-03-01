---
title: Python with turtle
layout: post
author: joel.chiappetti
permalink: /python-with-turtle/
source-id: 1FPrQ_Nt-0DJzb_Do9-is3klPgWLQ18lKPCPfpaB8E4Q
published: true
---
In today's lesson we started work on python with turtle. We used repl.it and clicked on python (with turtle). We made a piece of code which will draw all the regular shapes one after the other. You could change two things, the length of the sides and the number of sides which it stopped at.

*import turtle*

*turtle.shape("turtle")*

*turtle.speed(100)*

*def draw_shape(sides,length):*

*  for i in range(sides):*

*    turtle.forward(length)*

*    turtle.right(360/sides)*

*    *

*    *

*for f in range(3,15):*

*  draw_shape(f,10)*

