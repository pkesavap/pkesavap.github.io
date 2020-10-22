---
layout: project
type: project
image: images/micromouse.jpg
title: Decentralized && Distributed Storage Cluster
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-09-01
labels:
  - Blockchain
  - Software Defined Storage
  - 
summary: 
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

A Distributed storage system which allow users to club their storage disks in a network to provide secured storage .In this talk, you will see how (new DHT) blockchain is used to enhance the functionality. In a network of 5 nodes , if a user decides to upload a document , the document gets encrypted and sharded across the nearby nodes (based on geo-location) , during retrieval process , the encrypted files across the network gets verified and downloaded to the users node and then it is constructed together as one file.This infrastructure makes use of kademlia algorithm where the data after getting split will be put across the nodes by taking location as an argument, thus storing the data to nearby nodes and making retrieval process easy.The verification method to check whether data still exists in the chain is done by a request/response feature which will help in checking whether nodes contain the data or not. If the node does not contain the data, data regeneration will be initiated.


```js
```

