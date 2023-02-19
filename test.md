---
layout: page
title: Home
---

<div class="img-crop">
  <img src="{{ site.baseurl }}/assets/avatar.jpg"/>
</div>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ligula quam, bibendum vitae ligula eget, rhoncus volutpat mi. Phasellus eget sollicitudin sem, sit amet molestie ante. Aliquam convallis tellus nec turpis dictum, non bibendum orci dictum. Sed porta aliquam hendrerit. Pellentesque sollicitudin purus a arcu efficitur, at rutrum velit pellentesque. Suspendisse auctor egestas augue ac congue. Nam eu sem non augue dapibus mollis. Pellentesque tellus eros, vestibulum eget imperdiet vitae, tristique eu nunc. Phasellus eu erat quis lacus molestie tristique pellentesque porta nisi. Mauris scelerisque nisl libero, eu posuere orci fermentum at.

<iframe width="100%" height="600" src="https://www.google.com/maps/d/embed?mid=1VApo0sXmnDnX0xY8WkzZYU65ySk50e5-&ehbc=2E312F"></iframe>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

