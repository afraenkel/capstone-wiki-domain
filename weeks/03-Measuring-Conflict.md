---
layout: week
title: Week 00
doodle: /doodle.png
---

# Measuring Conflict on Wikipedia

## Topics

This week's assignments will guide you through the following topics:
* An introduction to edit wars on Wikipedia
* Using edits to measure of participation on Wikipedia

## Reading

Please read the following:
* [Edit Wars on Wikipedia](https://arxiv.org/abs/1107.3689), Sections
  I and II.
* [Wikipedia Policy on Edit
  Wars](https://en.wikipedia.org/wiki/Wikipedia:Edit_warring)
* Quartz. "Wiki Wars: Inside the increasingly nasty battle for
  Wikipedia's soul."
  [[Link](https://qz.com/347227/wiki-wars-inside-the-increasingly-nasty-battle-for-wikipedias-soul/)]

### Optional Reading

On the topic of edit session data, you may find this article's careful
usage of this data type interesting:

* R. Stuart Geiger and Aaron Halfaker. "Using Edit Sessions to Measure
  Participation in Wikipedia."
  CSCW 2013. [[Link]](http://stuartgeiger.com/cscw-sessions.pdf)

## Tasks

Complete the following tasks:
* Read the companion webpage for the Edit Wars paper and
  download/analyze the following contents:
  [WikiWarMonitor](http://wwm.phy.bme.hu/). Pay careful attention to:
  - 'Light-dump' data, the intermediate data the authors use to
    identify edit wars.
  - The script that transforms wikipedia dump data to light dump data.
  - The script that computes the M-Statistic.
* There are two articles contained in two files in the location
  `/teams/DSC180A_FA20_A00/b03onlinecommunities/testdata`. One of the
  files is the wikipedia edit dump format, while the other is in
  light-dump format. Look at the contents and identify the reversions
  in the light-dump data with the actual change in text in the
  XML (you may find it useful to look at the articles in the browser,
  as well). Write code that translates wikipedia edit data into light dump
  data. *Hint:* you can use *hashing* to tell if contents of two
  articles are exactly the same.


## Weekly Questions

Answer the following questions:
* How to the authors of Edit Wars define 'contraversiality' in
  wikipedia edits? Give two answers:
  1. an answer that is understandable to a general audience,
  2. an answer that is precise enough to translate into code.
* Give an obvservation you found interesting in the wikipedia policy
  on edit wars. Try to give an observation relevant to the Edit Wars
  paper.
* In the test data, how often does a reversion (as defined in the
  light-dump data) have the word 'revert' in the 'comment' field of
  the XML?
