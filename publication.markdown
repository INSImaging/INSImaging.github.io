---
layout: pubs
title: Publications
description: Journal papers, Conference proceedings
---


<!-- &ensp; <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path fill-rule="evenodd" clip-rule="evenodd" d="M12.026 2c-5.509 0-9.974 4.465-9.974 9.974c0 4.406 2.857 8.145 6.821 9.465c.499.09.679-.217.679-.481c0-.237-.008-.865-.011-1.696c-2.775.602-3.361-1.338-3.361-1.338c-.452-1.152-1.107-1.459-1.107-1.459c-.905-.619.069-.605.069-.605c1.002.07 1.527 1.028 1.527 1.028c.89 1.524 2.336 1.084 2.902.829c.091-.645.351-1.085.635-1.334c-2.214-.251-4.542-1.107-4.542-4.93c0-1.087.389-1.979 1.024-2.675c-.101-.253-.446-1.268.099-2.64c0 0 .837-.269 2.742 1.021a9.582 9.582 0 0 1 2.496-.336a9.554 9.554 0 0 1 2.496.336c1.906-1.291 2.742-1.021 2.742-1.021c.545 1.372.203 2.387.099 2.64c.64.696 1.024 1.587 1.024 2.675c0 3.833-2.33 4.675-4.552 4.922c.355.308.675.916.675 1.846c0 1.334-.012 2.41-.012 2.737c0 .267.178.577.687.479C19.146 20.115 22 16.379 22 11.974C22 6.465 17.535 2 12.026 2z" fill="#626262"/></svg> [Github repositories](https://github.com/jliang993?tab=repositories)  -->


#### Preprints 

<ol reversed="reversed" id="pub">  
  {% for item in site.data.year_pfive.toc[0].papers %}
      <li>
		{{ item.authors }}: 
        <a href="{{ item.url }}">{{ item.title }}</a> {% if item.venue %} , {{ item.venue }}. {% endif %} {% if item.misc %} ({{ item.misc }}) {% endif %}
      </li>
  {% endfor %}
</ol>



#### Year 2022

<ol reversed="reversed" id="pub">  
{% for item in site.data.year_pfive.toc[1].papers %}
    <li>
	  {{ item.authors }},  <a href="{{ item.url }}">{{ item.title }}</a>: <i>{{ item.venue }}</i>, {{ item.volpge }}, {{ item.year }}. {% if item.misc %} ({{ item.misc }}) {% endif %}
    </li>
{% endfor %}
</ol>



#### Year 2021

<ol reversed="reversed" id="pub">  
{% for item in site.data.year_pfive.toc[2].papers %}
    <li>
	  {{ item.authors }},  <a href="{{ item.url }}">{{ item.title }}</a>: <i>{{ item.venue }}</i>, {{ item.volpge }}, {{ item.year }}. {% if item.misc %} ({{ item.misc }}) {% endif %}
    </li>
{% endfor %}
</ol>

#### Year 2020

<ol reversed="reversed" id="pub">  
{% for item in site.data.year_pfive.toc[3].papers %}
    <li>
	  {{ item.authors }},  <a href="{{ item.url }}">{{ item.title }}</a>: <i>{{ item.venue }}</i>, {{ item.volpge }}, {{ item.year }}. {% if item.misc %} ({{ item.misc }}) {% endif %}
    </li>
{% endfor %}
</ol>

#### Year 2019

<ol reversed="reversed" id="pub">  
{% for item in site.data.year_pfive.toc[4].papers %}
    <li>
	  {{ item.authors }},  <a href="{{ item.url }}">{{ item.title }}</a>: <i>{{ item.venue }}</i>, {{ item.volpge }}, {{ item.year }}. {% if item.misc %} ({{ item.misc }}) {% endif %}
    </li>
{% endfor %}
</ol>

#### Year 2018

<ol reversed="reversed" id="pub">  
{% for item in site.data.year_pfive.toc[5].papers %}
    <li>
	  {{ item.authors }},  <a href="{{ item.url }}">{{ item.title }}</a>: <i>{{ item.venue }}</i>, {{ item.volpge }}, {{ item.year }}. {% if item.misc %} ({{ item.misc }}) {% endif %}
    </li>
{% endfor %}
</ol>




#### Prior 2017