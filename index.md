---
layout: default
title: Home
---

[Home](index.html) | [My Books](books.html) | [Gallery](gallery.html) | [Future Projects](future-projects.html) | [Contact](contact.html)

## Recent Posts

{% assign recent_posts = site.posts | slice: 0, 5 %}
{% if recent_posts == empty %}
No posts yet. Visit the [Blog](/blog/) for updates.
{% else %}
{% for post in recent_posts %}
### <a href="{{ post.url }}">{{ post.title }}</a>
<p><small>{{ post.date | date: "%B %-d, %Y" }}</small></p>
{{ post.excerpt }}
<p><a href="{{ post.url }}">Read more →</a></p>
{% endfor %}
{% endif %}

# Anusha Sridharan
**Author | Poet | Dreamer**

Welcome! I am a writer who finds magic in the mundane. Whether it’s the quiet observation of bird watching or the deep introspection of a poem, my work is a reflection of the "Lazy Conundrums" we all face.

---

## 📚 My Published Works
*Explore my collection of poetry and prose.*

<div style="background: #f0f4f8; padding: 20px; border-left: 5px solid #6c5ce7; border-radius: 8px; margin: 20px 0;">
    <h3>✨ Current Feature: The Journey Towards Calm</h3>
    <p>In a world of noise, finding silence is an art. Read the latest excerpt from my collection exploring the path to inner peace.</p>
    <a href="books.html" style="color: #6c5ce7; font-weight: bold;">Learn More →</a>
</div>

### Featured Release: Sprouted Up Heart
**"A journey of resilience and growth."**
[Buy on Flipkart](https://www.flipkart.com/sprouted-up-heart/p/itma5dff51e3f6b6) | [View on Amazon](https://www.amazon.in/Sprouted-Up-Heart-Anusha-Sridharan/dp/B0C9D9V7R1)

#### The Complete Collection:
* **Sky Album:** Lyrical reflections on the heavens and nature.
* **Conversations with Coherent Worlds:** Exploring the dialogue between self and space.
* **Picturesque Aromas of Thought Alleys:** Sensory poetry and memory.
* **Tutu & Jo:** A charming exploration of companionship.
* **The Journey Towards Calm:** Perspectives on finding peace.
* **Quilted Layers of Questions:** Deep dives into the inquisitive mind.

---

## ✍️ From the Blog
I regularly share new thoughts, "piece of irony" moments, and writing updates over at my main blog:
👉 [**Visit Lazy Conundrums**](https://lazyconundrums.wordpress.com/)

---

## 🎨 About Me
I believe that poetry is a soul sister. Aside from writing, I am an avid bird watcher and star gazer. My work is often inspired by the visual stories captured through my camera lens.

**Let's Connect:**
[Twitter/X](https://twitter.com/piece_of_irony) | [Instagram](https://instagram.com/piece_of_irony)