---
layout: post
title: "Daily Plog - December 21, 2024"
date: 2024-12-21 12:00:00 +0000
categories: [daily, plog]
tags: [update, thoughts]
---

Welcome to my first **LM experiment**!  
I’m so excited to dive into this and share what I’ve learned so far. This is all about understanding how **Large Language Models (LLMs)** work and how we can start using them effectively. If some of this feels familiar, great! If not, don’t worry—it’ll all make sense soon enough.

---

<nav aria-label="Breadcrumb" class="breadcrumb">
  <ul>
    <li><a href="{{ site.baseurl }}/">Home</a></li>
    <li><a href="{{ site.baseurl }}/posts/">Blog Posts</a></li>
    <li>{{ page.title }}</li>
  </ul>
</nav>

## Getting Started with Prompts

Understanding how **LLMs interpret instructions** is essential. There are two key types of prompts:

### 1. System Prompt
The system prompt sets the stage for the model. It defines the **context of the conversation**, the **task to be performed**, and even the **tone** of the interaction. 

> Example: In this experiment, the system prompt instructs the model to act as an assistant that analyzes websites and summarizes their content.

Experimenting with different system prompts reveals how they can significantly influence the model’s behavior and responses.

### 2. User Prompt
The user prompt provides **specific instructions** or poses a question, acting as the conversation starter. 

> Example: Here, the user prompt asks the model to summarize a website’s content.

These prompts work together to guide the model, ensuring its responses are **relevant**, **structured**, and aligned with the task.

---

### Conclusion

Stay tuned for more insights as I dive deeper into the fascinating world of LLMs and **prompt engineering**!

---

<section>
  <h3>Related Posts</h3>
  <ul>
    {% for post in site.posts limit:3 %}
    {% if post.url != page.url %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endif %}
    {% endfor %}
  </ul>
</section>

<div class="social-sharing">
  <p>Share this post:</p>
  <a href="https://twitter.com/intent/tweet?text={{ page.title }}&url={{ site.url }}{{ page.url }}" target="_blank">Share on Twitter</a> |
  <a href="https://www.linkedin.com/shareArticle?mini=true&url={{ site.url }}{{ page.url }}&title={{ page.title }}" target="_blank">Share on LinkedIn</a>
</div>
