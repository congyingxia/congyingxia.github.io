---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />

　　<p align="justify"> Hi, my name is Congying Xia. I am a 4th-year Ph.D. student in the Department of Computer Science at University of Illinois at Chicago. I am fortunate to be advised by Professor Philip S. Yu. Prior to that, I received B.S. and M.S. from University of Science and Technology, Beijing.</p>
  
  <p align="justify"> My primary research interest lies in Natural Language Processing, like named entity reconition and intent detection. In particular, I am interested in understanding natural language in low-resource senarios such as zero-shot learning and few-shot learning. I interned at Salesforce Research, Google AI and Tecent Medical AI lab during the PHD period.</p>


Publications
----------
<div>
  <table>
  {% for post in site.conferences_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 


Preprints
----------
<div>
  <table>
  {% for post in site.preprints reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

