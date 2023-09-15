# The blogg



hello **welcome** to my blog. This is where the jokes will be and the factual stuff.
 

## recent posts
<ul>
{% for post in site.posts %}
<li>
<a href="/blog{{post.url}}">{{post.title}}</a>
</li>
{ % endfor %}
</ul>
