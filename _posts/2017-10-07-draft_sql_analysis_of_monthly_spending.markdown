---
layout: post
title:      "NodeJS + NoSQL with Couchbase"
date:       2017-10-07 14:26:40 -0400
permalink:  draft_sql_analysis_of_monthly_spending
---

Post inspired by [Matthew Groves'](https://twitter.com/mgroves?lang=en) session at

[![](https://www.exitevent.com/wp-content/uploads/2017/08/All-Things-Open-logo-red-300x168.png)](https://allthingsopen.org/)

_________________________

I just started learning SQL and getting really excited about it.  So why NoSQL?! 
* cloud-friendly
* fast
* cheap

But remember...
* NoSQL is NOT a relational database

[Couchbase](https://www.couchbase.com/) is a document-oriented database solution (document being a JSON string), and is an alternative to MongoDB and ORMs.  

Ricky Ho [explains](https://dzone.com/articles/couchbase-architecture-deep):
"Couchbase is the merge of two popular NOSQL technologies:  
* Membase, which provides persistence, replication, sharding to the high performance memcached technology
* CouchDB, which pioneers the document oriented model based on JSON"

Sample apps using NodeJS:
https://github.com/couchbaselabs/try-cb-nodejs
https://github.com/couchbaselabs/restful-angularjs-nodejs

N1QL is a query language that extends SQL for JSON.
[N1QL Tutorial](https://query-tutorial.couchbase.com/tutorial/#1)

Why would you want to do this instead of using ORMs?  I don't know yet.  If you have an example use case, please share!

