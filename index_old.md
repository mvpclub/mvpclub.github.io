## Welcome to James Cook University's MVP Club

You can follow the club activities and events from the [JCU MVP Club on facebook](https://www.facebook.com/groups/jcumvpclub/).
Sign up and get notification about the events we have at JCUS.

We would like to invite students from all JCU campuses to join this Club.

# Signup with [JCU MVP Club slack channel](https://join.slack.com/t/jcumvpclub/shared_invite/enQtNDczNDU2NTYzODkxLWVkYzk3NDRiMTAyOGFjMDI3Y2ZkZjYyY2NlZGY5MWRlOGRjNWZlNDYyOGNlMTA5NDRkOWMwMzVjOWU1MjQ4NjM)

You will learn about MVP development, which is minimum viable product development.
You will get an understanding about cloud computing, DevOps, Software development languages used in the industry.

_Key words: git, Ansible, AWS, AI, javascript, Arduino, Raspberry PI, C/C++, Java, mobile development, Web development, Design Thinking, Entrepreneurship_


### MVP Club sessions
{% for item in site.mvp_collection %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}
