<!-- testimonials.md -->
---
layout: page
title: "Blog & News & Testimonial"
permalink: /testimonials/
---

## Berita & Postingan

<ul class="list-disc list-inside mb-8">
  {% for post in site.posts %}
  <li><a href="{{ post.url }}" class="text-secondary hover:text-accent">{{ post.title }}</a> &ndash; {{ post.date | date: "%e %B %Y" }}</li>
  {% endfor %}
</ul>

## Testimoni Pelanggan

<p>Testimoni pelanggan akan dikemas kini di sini tidak lama lagi. Sementara itu, ikuti kami di media sosial untuk maklum balas & ulasan pelanggan.</p>