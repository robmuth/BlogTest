# BlogTest
The only purpose of this repo is to test github pages.

It will be deleted soon :-)

I wonder if it can display formulas like $2^{256}-1$ ?


<h1>Latest Post</h1>
{% for post in site.posts limit:1 %}
... Show the first post all big ...
{% endfor %}
<h1>Recent Posts</h1>
{% for post in site.posts offset:1 limit:2 %}
... Show the next two posts ...
{% endfor %}
