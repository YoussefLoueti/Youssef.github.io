# 🚀 

Welcome to my project portfolio! Here I document my coding adventures, challenges, and solutions.

## 📂 Projects

### [--](./projects/ecommerce-dashboard.md)
- **Tech**: --
- **Status**: In progress
- **Last Updated**: --

### [--](./projects/game-ai.md)  
- **Tech**: --
- **Status**: --
- **Last Updated**: --

---

## 📝 Latest Updates
{% for post in site.posts limit:3 %}
- **[{{ post.date | date: "%Y-%m-%d" }}]** {{ post.title }}
{% endfor %}
