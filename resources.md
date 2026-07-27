---
layout: page
title: Resources
permalink: /resources/
---

# English Learning Resources

A curated collection of tools, websites, and materials to support your learning.

## Helpful Resources

{% for post in site.resources %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: '%B %d, %Y' }}
{% endfor %}

## Recommended Tools & Websites

- **Dictionary & Thesaurus** - Oxford, Merriam-Webster, Cambridge
- **Grammar Checkers** - Grammarly, QuillBot
- **Pronunciation** - Forvo, Google Translate
- **Speaking Practice** - Speaky, ConversationExchange
- **Listening Practice** - BBC Learning English, TED-Ed
- **Writing Practice** - Medium, Dev.to
- **Language Apps** - Duolingo, Babbel, Rosetta Stone

---

*Use these resources to accelerate your learning journey!*