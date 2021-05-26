---
layout: home
title: macOS Containers Initiative
---

{::nomarkdown}
<p class="logo"><img src="{{ "/" | relative_url }}assets/images/favicon.svg" alt="macOS Containers logo"></p>
{:/}

# macOS Containers

Containers have fundamentally changed the way that modern software is developed and deployed. Containers are supported by a wide range of operating systems including FreeBSD, Solaris, Linux and even Windows, but are not natively supported by macOS. **Until now.**

The open source developer community is working together to implement support for native containers on macOS. The first step is to add low-level components in [containerd](https://containerd.io/), the underlying runtime used by both Docker and Kubernetes. This foundational work will pave the way for adoption of macOS containers throughout the container tooling ecosystem. **You can help by upvoting or commenting on the feature proposal:**

{::nomarkdown}
<p class="button-wrapper">
	<a class="btn btn-primary btn-lg" href="https://github.com/containerd/containerd/discussions/5525" role="button">View the proposal on GitHub</a>
</p>

<ul class="social">
{% for link in site.data.nav.social %}
	<li><a href="{{ link.url | uri_escape }}"><span class="icon {{ link.icon }}" alt="{{ link.name | escape }}" title="{{ link.name | escape }}"></span></a></li>
{% endfor %}
</ul>

<div class="footer">
	<p>Mac and macOS are trademarks of Apple Inc., registered in the U.S. and other countries and regions.</p>
	<p>This website is an independent community initiative and has not been authorised, sponsored, or otherwise approved by Apple Inc.</p>
</div>
{:/}
