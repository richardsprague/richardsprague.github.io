---
layout: page
title: Microbiome

---

**Note:** I'm working on a major new project to make it easy for normal people to understand their microbiome test results. Meanwhile, if you have test results from uBiome or others, please [contact me](mailto:richardsprague+home@gmail.com) and I'll be happy to help you (if you give me your data!)

[How to interpret your uBiome results](http://radar.oreilly.com/2015/07/announcing-biocoder-issue-8.html): My article in O'Reilly's BioCoder.

[How does kombucha affect the microbiome](https://github.com/richardsprague/kombucha) My experiment tracking my daily microbiome before/after drinking kombucha.

[uBiome official Python Utilities](https://github.com/ubiome-opensource/microbiome-tools/blob/master/docs/howto/analyze_your_ubiome_results_in_python.md) Open source Python module for analyzing your uBiome results. 

[How does kombucha affect the microbiome?](https://github.com/richardsprague/kombucha): My experiment tracking my daily microbiome before/after drinking kombucha.

[Peeking into a Baby Biome](https://www.drgreene.com/perspectives/peeking-into-a-baby-biome/): Investigating a baby and her mother.


#Posts to this site
<ul>
  {% for post in site.posts %}
  {% if post.tags contains "microbiome" or post.tags contains "Biology"  %}
  <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>



# Posts to the uBiome blog

[Experimenting with a gut cleanse](http://www.ubiomeblog.com/experimenting-with-a-gut-cleanse-by-richard-sprague/): before/during/after results from a one-month experiment.

[Hacking my sleep with uBiome](http://www.ubiomeblog.com/hacking-sleep/) and [an update](http://www.ubiomeblog.com/my-ubiome-sleep-hacking-update/).

<p><a href="http://www.ubiomeblog.com/looking-mouth-microbiome/">Looking into my mouth microbiome</a>: testing myself at the dentist.</p>

<p><a href="http://www.ubiomeblog.com/one-week-change-in-my-microbiome/">One week change in my microbiome</a>: a before/after test with detailed food tracking.</p>

<p><a href="http://www.ubiomeblog.com/my-microbiome-in-the-jungle/">My microbiome in the jungle</a>: how my gut biome changed during a trip to Central America.</p>

# Technical uBiome posts

<p><a href="http://www.ubiomeblog.com/what-do-i-do-with-my-raw-data/">What do I do with my raw data?</a></p>

<p><a href="http://www.ubiomeblog.com/invitation-to-join-the-ubiome-github-repository/">Invitation to the uBiome open source repository</a></p>

<p><a href="http://www.ubiomeblog.com/all-my-ubiome-results-in-a-single-table/">How to make a single table of your uBiome results</a></p>

<p><a href="http://blog.richardsprague.com/2015/01/how-to-analyze-ubiome-sample-in-excel.html">How to analyze a uBiome sample in Excel</a></p>
