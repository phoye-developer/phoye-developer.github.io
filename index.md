# Patrick's Website

# My Projects
Here is a list of projects I have been working on:
<ul>
  <li><a href="https://github.com/phoye-developer/HelloWorld">HelloWorld</a></li>
  <li><a href="https://github.com/phoye-developer/phoye-developer.github.io">phoye-developer.github.io</a></li>
  <li><a href="https://github.com/phoye-developer/markdown-portfolio">markdown-portfolio</a></li>
  <li><a href="https://github.com/phoye-developer/github-upload">github=upload</a></li>
  <li><a href="https://github.com/phoye-developer/github-slideshow">github-slideshow</a></li>
</ul>

# My Interests
I'm interested in learning coding and software engineering.

# My Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Get in Touch
<ul>
  <li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
  <li><a href="https://linkedin.com/in/{{ site.linkedin_username }}">LinkedIn</a></li>
</ul>
