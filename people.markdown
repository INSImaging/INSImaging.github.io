---
layout: post
title: "Group members"
description: "Welcome to our group-page"
---

<br>

### Faculty

 <table style="width: 45%;">
  <tr>
    <th style="width:33%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:33%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:33%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
  </tr>
  <tr>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
  </tr>
</table> 


### Postdocs


 <table style="width: 30%;">
  <tr>
    <th style="width:50%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:50%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
  </tr>
  <tr>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
  </tr>
</table> 



### PhD students


 <table style="width: 90%;">
  <tr>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
  </tr>
  <tr>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
  </tr>
  <!--  -->
    <tr>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
  </tr>
  <tr>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
  </tr>
</table> 


### Master Students

<table style="width: 90%;">
  <tr>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
  </tr>
  <tr>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
  </tr>
  <!--  -->
    <tr>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
    <th style="width:15%" class="imgcell"><img src="assets/emptyphoto.png" /></th>
  </tr>
  <tr>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
    <td class="namecell">Fistname Lastname</td>
  </tr>
</table> 

### Previous students

<ul id="pub">  <!-- start="26"> -->
  {% for item in site.data.previous_students %}
      <li style="margin-left:0px;">
        {% if item.url %} <a href="{{ item.url }}"> {% endif %} {{ item.name }} {% if item.url %} </a> {% endif %} {{ item.previous }}, {{ item.now }}.
      </li>
  {% endfor %}
</ul>

