---
title: "Task level parallelization"
date: 2021-09-05T12:27:11+06:00
image: "assets/task_parellelization.gif"
# description
description: "This is meta description"
tags: ["databases"]
draft: false
---
Almost all distributed analytic databases offer some level of task parallelization by farming out queries and data to multiple nodes. 
For instance, here the data containing information about daily sales for three stores A, B, C  is split into three. Each partition containing information for just one store is kept on separate nodes in the cluster. 
Now, if we wanted to calculate total sales for each store. We would map the query to each node and execute it in parallel. 
The results from these queries would then be combined to arrive at the final table showing the total sales for each store.


![](assets/task_parellelization.gif)<!-- -->