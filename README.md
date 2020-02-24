# BlogTest

<script src="{{ base.url | prepend: site.url }}/assets/js/katex.js"></script>

{% include head.html %}

The only purpose of this repo is to test github pages.

It will be deleted soon :-)

I wonder if it can display formulas like $2^{256}-1$ ?


<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date }}: <a href="{{ base.url | prepend: post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
