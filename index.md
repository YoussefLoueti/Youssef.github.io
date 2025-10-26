# 🚀 My Development Journey

Welcome to my project portfolio! Here I document my coding adventures, challenges, and solutions.

## 📂 Projects

### [E-Commerce Dashboard](./projects/ecommerce-dashboard.md)
- **Tech**: React, Node.js, MongoDB
- **Status**: In progress
- **Last Updated**: 2024-11-20

### [Mobile Game AI](./projects/game-ai.md)  
- **Tech**: Python, TensorFlow
- **Status**: Completed
- **Last Updated**: 2024-10-15

---

## 📝 Latest Updates
{% for post in site.posts limit:3 %}
- **[{{ post.date | date: "%Y-%m-%d" }}]** {{ post.title }}
{% endfor %}
