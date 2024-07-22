{!README.md!}

This is an open source tool to detect ringed seal barks in passive acoustic monitoring (PAM) recordings. Specifically, this tool indicates the start and end time of potential ringed seal vocalizations within PAM data. The detector was trained on data from the Western Canadian Arctic, and focuses on the detection of barks as they were theorized to have the highest amplitude out of the most commonly described vocalization types (barks, yelps, and growls). The detector has a very high recall but low precision, meaning that it misses very few vocalizations but has a large number of false positives. Sound sources with similar frequency signatures, such as water sounds, knocking sounds, and scratching sounds, account for the majority of false positives. 

The detector was written in Python, and requires Anaconda (or Miniconda) to run. The detector uses the [Ketos](https://docs.meridian.cs.dal.ca/ketos/introduction.html) Python package extensively.

Please see the [Set Up](SetUp.md) page to get started.

<video width="700"  controls>
  <source src="main-page.mp4" type="video/mp4">
</video>

[TOC]


