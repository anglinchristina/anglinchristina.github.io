---
layout: post
title:      "NodeJS + NoSQL with Couchbase"
date:       2017-10-07 14:26:40 -0400
permalink:  draft_sql_analysis_of_monthly_spending
---


The Learn curriculum introduces us to:
* SQLite
* incorporating SQL queries into object-oriented programming with ORMs (specifically using the [SQLite3 gem](http://) which allows us to pass in Ruby variables when we execute SQL)
* ActiveRecord

I'm currently really excited about SQL.  So why NoSQL?! 
* cloud-friendly
* fast
* cheap

But remember...
*NoSQL is NOT a relational database.

Couchbase is a document (JSON string)-oriented database solution, and is an alternative to MongoDB and ORMs.  

Ricky Ho [explains](https://dzone.com/articles/couchbase-architecture-deep):
"Couchbase is the merge of two popular NOSQL technologies:  
* Membase, which provides persistence, replication, sharding to the high performance memcached technology
* CouchDB, which pioneers the document oriented model based on JSON"

N1QL is a query language that extends SQL for JSON.

Sample apps using NodeJS:
https://github.com/couchbaselabs/try-cb-nodejs
https://github.com/couchbaselabs/restful-angularjs-nodejs


Why would you want to do this instead of using ORMs?  I don't know yet.  If you have a good use case, please share!
[N1QL Tutorial](https://query-tutorial.couchbase.com/tutorial/#1)
