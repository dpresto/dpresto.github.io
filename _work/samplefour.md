---
layout: post
title: "Fourth Sample"
author: "DP"
type: mainproject
published: true
post_image: /assets/interview_setup.png
post_cap: Image courtesy of Nicolas Coia
alt_post_image: A photo of a home office reconfigured for a remote interview
proj_description: This is a 4th sample of what else could be included.
client: "Internal"
duration: "3 months"
delivered_season: "Summer 2017"
roles: "project lead, product manager, UX designer, facilitator"
live_site_name: dominicp.com
live_site_url: "http://dominicp.com"
---
<div>
  <div class="col4">
  <h4>Client:</h4> <p>{{ page.client }}</p>
  <h4>Delivered: </h4> <p>{{ page.delivered_season }}</p>
  <h4>Duration:</h4> <p>{{ page.duration }}</p>
  <h4>Roles:</h4> <p>{{ page.roles }}</p>
  <h4>Live Site:</h4> <p><a href="{{ page.live_site_url }}" alt="{{ page.live_site_name }}">{{ page.live_site_name }}</a></p>
  </div>

  <div class="col34">
  <p>This is a 4th sample of what else could be included. You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.</p>
  <p>To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.</p>
  </div>
</div>
<hr>
<br>
<img src="{{ page.post_image | prepend: site.url }}" alt="{{ page.alt_post_image }}" style="width: 100%;">
