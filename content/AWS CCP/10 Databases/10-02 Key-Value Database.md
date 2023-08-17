---
title: 10-02 Key-Value Database
date: 07/10/23
---

A **key-value database** is a type of non-relational database (NoSQL) that uses a simple key-value method to store data. 

|Key|Value|
|---|-----|
|Data|{species:android, rank:'lt commander'}|
|Worf|{species:klingon, rank:'lt commander'}|
|Ro Laren|{species:bajoran, affiliation:'maquis'}|

* Key-values are <mark style="background: #FF5582A6;">dumb and fast</mark>
* They generally lack features like:
  * relationships
  * indexes
  * aggregation

A simple key-value store will interpret data resembling a dictionary (aka Associative arrays or hash)

|Key (Name)|Species|Rank|Affiliation|
|----------|-------|----|-----------|
|Data|android|lt commander||
|Worf|klingon|lt commander||
|Ro Laren|bajoren||maquis|

* A key-value store *can* resemble tabular data BUT it does not necessarily have consistent columns per row (hence its schema-less)
* Due to their simple design they can scale well beyond a relational database
