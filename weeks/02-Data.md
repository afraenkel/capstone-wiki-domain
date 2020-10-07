---
layout: week
title: Week 00
doodle: /doodle.png
---

# Wikipedia Edit Data

## WikiDump Data

This week's assignments will guide you through the following topics:
* Quantitative explorations into collaboration on Wikipedia.
* Understand the contents/schema of wiki-dump data
* Processing large XML files
* Background in 'wisdom of the crowds'

## Reading

- How is information and bias related to what drives wikipedia as a
  platform? How are these related to conflict/collaboration? Note how
  **bias** is measured in Shane Greenstein and Feng Zhu. "Do Experts
  or Crowd-based Models Produce More Bias? Evidence from Encyclopædia
  Britannica and Wikipedia"
  [[Link]](https://pdfs.semanticscholar.org/5a1d/58d90143969b33a9a9d4ad4124c15033c745.pdf)
- Note how **quality** and **coordination** are measured in Aniket
  Kittur and Robert E. Kraut. "Harnessing the Wisdom of Crowds in
  Wikipedia: Quality Through Coordination." CSCW
  '08. [[Link]](https://dl.acm.org/doi/10.1145/1460563.1460572)
  
- Browse the Wikimedia Data Dumps
  Page, which describes the main data source for this
  domain. [[Link]](https://meta.wikimedia.org/wiki/Data_dumps).
  
  
## Tasks

Complete the following tasks:
* Download some edit data from the Wikimedia Data Archives
  [[Link]](https://dumps.wikimedia.org/backup-index.html). Your data
  should come from a file with 'All pages with complete page edit
  history'. These files are large, so try to find a smaller file.
  
* Pick a few fields and try to run a preliminary EDA on the file.

*Note:* This task will require you to unzip and parse XML. You can
either unzip using the commandline or python libraries. Parsing XML
in memory can be done using `beautifulsoup`. You may also find the
tools [here](https://meta.wikimedia.org/wiki/Data_dumps/Other_tools)
and [here](https://meta.wikimedia.org/wiki/Data_dumps/Download_tools)
useful.

When doing this task, think about building a library of functions that
will process this type of data *without manual intervention* and *with
a small memory footprint*, as the complete dataset may contain dozens
of multi-GB files!

## Weekly Questions

Answer the following questions:

- What are some ways to measure quality in Wikipedia data?
- What are some ways to measure bias in articles in Wikipedia data?
- What fields did you perform an EDA on? What is one interesting
  observation you have from your EDA?



