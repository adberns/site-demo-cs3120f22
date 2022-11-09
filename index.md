---
---
This is a __Markdown__ file.  It can be *formatted* easily.

Links are [easy to place](https://uni.blackboard.com).

Edits should appear automatically.

## Projects
{% for project in site.data.projects %}
  __Title:__ _{{ project.title }}_

  Project description: {{ project.description }}
{% endfor %}
