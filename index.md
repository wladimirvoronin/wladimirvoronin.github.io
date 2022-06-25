<div>
    {% for post in site.posts %}
        <div>
            <a href=".{{ post.url }}">{{ post.title }}</a>
        </div>
    {% endfor %}
</div>
