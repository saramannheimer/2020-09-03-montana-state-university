---
layout: workshop     
venue: "Montana State University"      
address: "Online"     
country: "us"     
language: "en"    
humandate: "Sep 3, Sep 10, Sep 24, Oct 15, and Nov 5, 2020"   
humantime: "3:00 pm - 5:00 pm"    
startdate: 2020-09-03     
enddate: 2020-11-05       
instructor: ["Mark Greenwood", "Greta Linse", "Sara Mannheimer"] 
helper: ["SCRS Graduate Research Assistants"]    
email: ["greenwood@montana.edu","sara.mannheimer@montana.edu"]   

---

<h2 id="general">General Information</h2>

INTRODUCTION

R workshops hosted by the Montana State University Library, Department of Mathematical Sciences, and Statistical Consulting and Research Services.



LOCATION

<p id="where">
  <strong>Where:</strong> This training will take place online.
  The instructors will provide you with the information you will need to connect to this meeting.
</p>


CONTACT EMAIL ADDRESS

<p id="contact">
  <strong>Contact:</strong>
  Please email
  {% if page.email %}
  {% for email in page.email %}
  {% if forloop.last and page.email.size > 1 %}
  or
  {% else %}
  {% unless forloop.first %}
  ,
  {% endunless %}
  {% endif %}
  <a href='mailto:{{email}}'>{{email}}</a>
  {% endfor %}
  {% else %}
  to-be-announced
  {% endif %}
  for more information.
</p>


<h2 id="code-of-conduct">Code of Conduct</h2>

<p>
Everyone who participates in Carpentries activities is required to conform to the <a href="https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html">Code of Conduct</a>. This document also outlines how to report an incident if needed.
</p>

<p class="text-center">
  <a href="https://goo.gl/forms/KoUfO53Za3apOuOK2">
    <button type="button" class="btn btn-info">Report a Code of Conduct Incident</button>
  </a>
</p>
<hr/>



{% comment %}
SURVEYS - DO NOT EDIT SURVEY LINKS
{% endcomment %}
<h2 id="surveys">Surveys</h2>
<p>Please be sure to complete these surveys before and after the workshop.</p>
<p><a href="{{ site.pre_survey }}{{ site.github.project_title }}">Pre-workshop Survey</a></p>
<p><a href="{{ site.post_survey }}{{ site.github.project_title }}">Post-workshop Survey</a></p>

<hr/>


{% comment %}
SCHEDULE

https://calendar.lib.montana.edu/calendar/workshops/?cid=707&t=d&d=0000-00-00&cal=707&ct=43429&inc=0
<hr/>
