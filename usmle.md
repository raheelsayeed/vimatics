 <ul class="posts">
    {% for post in site.usmle %}

      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>

       <p>{{ post.excerpt }}</p>
      </li>

    {% endfor %}
  </ul>
