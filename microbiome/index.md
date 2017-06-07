---
layout: page
title: Microbiome

---

**Note:** I'm working on a major new project to make it easy for normal people to understand their microbiome test results. Meanwhile, if you have test results from uBiome or others, please [contact me](mailto:richardsprague+home@gmail.com) and I'll be happy to help you (if you give me your data!)

<iframe src="https://player.vimeo.com/video/147673343?title=0&byline=0&portrait=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/147673343">Richard Sprague: &quot;Fish Oil Makes Me Smarter&quot;</a> from <a href="https://vimeo.com/qslabs">Quantified Self</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
Following an experiment originally proposed by the late UC Berkeley psychologist and Quantified Self pioneer Seth Roberts, I tested the effect on brain reaction time (BRT) of taking fish oil supplements. Surprisingly, periods of taking fish oil corresponded to significantly higher scores on the test, even when controlling for sleep and other factors such as alcohol consumption. I speculate on why this effect may be real, and suggest how the BRT may be useful in discovering similar effects.
</p>


[Microbiome Hackers Guide]({{ site.url }}/docs/index.html)

<a href="{{ site.url }}/docs/index.html">
<img src="{{ site.url }}/assets/MHGCover.png" width="150"/>
</a>

[How to interpret your uBiome results](http://radar.oreilly.com/2015/07/announcing-biocoder-issue-8.html): My article in O'Reilly's BioCoder.

<a href = "http://radar.oreilly.com/2015/07/announcing-biocoder-issue-8.html">
<img src="http://www.oreilly.com/biocoder/biocoder-2015summer-286x430.png" width="100"/>
</a>

[How does kombucha affect the microbiome](https://github.com/richardsprague/kombucha) My experiment tracking my daily microbiome before/after drinking kombucha.

<a href = "https://github.com/richardsprague/kombucha">
<img src="https://raw.githubusercontent.com/richardsprague/kombucha/master/kombuchaBarChart.jpg" width="200"/>
</a>



[uBiome official Python Utilities](https://github.com/ubiome-opensource/microbiome-tools/blob/master/docs/howto/analyze_your_ubiome_results_in_python.md) Open source Python module for analyzing your uBiome results. 

[Peeking into a Baby Biome](https://www.drgreene.com/perspectives/peeking-into-a-baby-biome/): Investigating a baby and her mother.


# Posts to this site

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
