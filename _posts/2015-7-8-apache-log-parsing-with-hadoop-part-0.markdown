---
layout: post
title:  "Apache Log Parsing with Hadoop Hive - Part 0"
date:   2015-7-8
published: true
---

<p class="intro"><span class="dropcap">T</span>his is going to be my first new mini-series of posts regarding my current tasks at work: parsing an Apache logfile with Hadoop Hive. During this mini-series, we will talk about on how to import logfiles into hive using simple unix commands and a hive import file table and how to extract specific kinds of information.</p>

I plan to write this series of blog posts in a tutorial style manner. So if you want to follow along the path and get your hands dirty, I recommend downloading the [Hortonworks HDP Sandbox][hdp download]. It is a fully fledged, preinstalled hadoop distribution, which comes in an easy to integrate imagefile using the freely available [virtualbox][virtualbox] virtualization enviroment. Also you can find many more tutorials regarding the HDP Sandbox [here][HDP Tutorials].

I will split my little tutorial into multiple posts:

1. Part 1 will describe how to easyly get data into your hdfs environment
2. Part 2 will cover the actual data layout
3. In part 3 I will talk about supported user defined functions (UDFs) that come integrated with hive
4. And last but not least we will extend the preinstalled UDFs with some of our own
5. After that, we will be able to fully parse the logfile and group, extract or reorganize the data to our liking

I hope to have awakened your interest! If not, at least I got a plan on what to write next for myself.

Cya, Simon

[hdp download]: http://hortonworks.com/hdp/downloads/
[virtualbox]: https://www.virtualbox.org/wiki/Downloads
[HDP Tutorials]: http://hortonworks.com/tutorials/