# BlogTest

<script src="{{ site.baseurl }}/assets/js/katex.js"></script>

The only purpose of this repo is to test github pages.

It will be deleted soon :-)

I wonder if it can display formulas like $2^{256}-1$ ?


<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date }}: <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
