---
layout: page
title: contact
nav: true
nav_order: 20
permalink: /contact/
---

<div class="contact-content">
  <div class="contact-cards">
    {% if site.data.socials.email %}
    <div class="contact-card">
      <a href="mailto:{{ site.data.socials.email }}">
        <i class="fa-solid fa-envelope"></i>
        <div class="card-label">Email</div>
        <div class="card-value">{{ site.data.socials.email }}</div>
      </a>
    </div>
    {% endif %}
    {% if site.data.socials.linkedin_username %}
    <div class="contact-card">
      <a href="https://linkedin.com/in/{{ site.data.socials.linkedin_username }}">
        <i class="fa-brands fa-linkedin"></i>
        <div class="card-label">LinkedIn</div>
        <div class="card-value">{{ site.data.socials.linkedin_username }}</div>
      </a>
    </div>
    {% endif %}
  </div>

</div>
