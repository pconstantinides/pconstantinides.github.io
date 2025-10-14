---
layout: home
title: "Home"
featured_projects:
  - project-example
  - project-alpha
  - project-beta
author_profile: true
hero_image: /assets/images/hero-bg.jpg
---

## Hello — I'm Your Name
Senior Software Engineer specializing in web and API systems. I build resilient services, create developer tools, and publish open-source libraries used in production.

**What I do**
- Architect and implement scalable backend systems (microservices, message-driven systems)
- Build modern web apps (React / Next.js, accessible and performant)
- Mentor engineering teams and lead technical design reviews

### Featured projects
{% for project in site.projects | where_exp:"p","p.slug" %}
<!-- Minimal Mistakes automatically handles display; featured list above controls which appear -->
{% endfor %}

### Key facts
- 10+ years in software engineering
- 35 open-source contributions (libraries & tooling)
- Deployed services used by 500k+ weekly active users

[View all Projects](/projects/) • [Read my blog](/blog/) • [Download Resume](/assets/resume.pdf)
