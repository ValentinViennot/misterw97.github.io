---
layout: default
mask_hidden: true
---

# About Me

> “A great product manager has the brain of an engineer, the heart of a designer, and the speech of a diplomat.” - Deep Nishar

Driven by a mission to contribute to individual and collective intelligence, I am convinced technology will positively and durably change our society. After applying Design Thinking in different contexts, I believe that focusing on the source of the problem and the *user experience* is the key. Don’t fall in love with the solution but your users' pain.

I’m a young executive [product manager](https://www.quora.com/Why-do-engineers-become-product-managers/answer/Fareed-Mosavat?ch=3&share=5287df25&srid=3XLCB) for Canonical, the open-source company behind Ubuntu. I graduated with my [engineering degree](https://www.insa-lyon.fr/fr/formation/telecommunications-services-usages) in Communication Systems and Computer Science with honors - already having experience as a software engineer at [IBM Garage](https://www.ibm.com/cloud/architecture/careers)’s best-practiced division. Although my background is highly technical, my passions are product design, business, and society. I’m a detail-oriented person, strongly qualified in problem-solving, and with a deep sense of leadership.

Open source isn’t only an opportunity to share our knowledge, moving faster and better together; it is a strategic and powerful culture to drive positive change, durably. Improving the open source world is a first step in my contribution to individual and collective intelligence. On a personal level, I look for expressing and developing my creativity, sharing my technical expertise and leadership, and endless learning.

Do you want to discuss interests overlap, opportunities, project ideas, or say hello? [Reach out]({{ site.email }}).

## Bio
[See my full resume on LinkedIn]({{ site.linkedin }})

I've always wanted to be an inventor. Since I was a child, I wanted to solve all the problems with my ideas -- often causing my parents and sisters to yell at me, until they eventually told me: "Valentin, you need to be an engineer". Was that the word for an inventor? Without a doubt, I joined the top-ranked INSA de Lyon engineering school right after graduating from High School.

| <img src="/assets/img/logo-insa.png" alt="INSA Lyon" width="40"/> | **INSA Lyon** | Communications Systems | 2015-2020 | [details]({{ site.linkedin }}) |

Learning how to code for some side-projects, I quickly realized it was the perfect way to bring all my inventions to life. More than that, programming isn't related to only one field and neither were my ideas.

As I couldn't wait any longer, I started to send applications to different companies to join the Master of IT and Communication Systems in apprenticeship.

| <img src="/assets/img/logo-ibm.png" alt="IBM" width="40"/> | **IBM** | Full-stack Software Engineer | 2017-2020 | [details]({{ site.linkedin }}) |

That's how, in 2017, I joined IBM beginning my apprenticeship as a full-stack engineer.
Working there I realized mainly two things:
- not only IT is part of any business, but it's disrupting all of them;
- design, and most importantly user-centered design, is core to innovation and building new ideas.

| <img src="/assets/img/logo-epfl.png" alt="EPFL" width="40"/> | **EPFL** | Exchange student | 2019-2020 | [details]({{ site.linkedin }}) |

Feeling restrained, I had the need to leave my bubble. I spent one semester at the [EPFL](https://www.epfl.ch/schools/ic/communication-systems-msc/) with two goals: understanding user experience and acquiring knowledge about analytics and data science. Working hard, leading creative projects, I achieved both these goals. Most importantly, it greatly increased my self-awareness. I am an entrepreneur.

| <img src="/assets/img/logo-ubuntu.png" alt="Canonical" width="40"/> | **Canonical** | Executive Product Manager | 2020 | [details]({{ site.linkedin }}) |

At this point, it became clear to me that I only had two options: either start my own business, or become [Product Manager](https://productcoalition.com/you-are-not-the-ceo-9f665d0e4a46).

Then came [*the* question](http://paulgraham.com/procrastination.html), "What's the best thing you could be working on? And, why aren't you?". 

On a mission to contribute to individual and collective intelligence, I decided to put my creativity, cross-functional knowledge, and technical skills gained from my engineering background to work and to contribute to Open Source.

As a Product Manager for Canonical, I work every day to improve Open Source with the help of a precise and passionate community, following strong ethics and principles.

> "Willing to think, Curious to learn, Enthusiastic about making" is my motto.

<!--
Minified version:
I've always wanted to be an inventor. Since I was a child, I wanted to solve all the problems with my ideas. Without any doubt, I joined the top-ranked INSA de Lyon engineering school right after graduating from High School.
Learning how to code for some side-projects, I quickly realized it was the perfect way to bring all my inventions to life. More than that, programming isn't related to only one field and neither were my ideas.
Willing to learn from the real world as soon as possible, I joined IBM in 2017 for a 3-year apprenticeship as a Full-Stack Software Engineer -- currently working in the IBM Garage for Cloud division.
After spending a semester at the EPFL studying user experience and data science, I came back with a new mindset: entrepreneur is the right word for inventor!
I'm determined about my next move: If you're looking for a Product Manager who's passionate, curious and motivated to learn; not only a thinker but a maker... let's chat and see how we are going to improve our world together!
-->

## Portfolio

This section is about some projects I led and have done a significant part.
Whether it’s side or school projects, I’d be happy to discuss them with you!

<!-- First one is the most recent active one.
Some of them link to a more detailed README, some are just a title and a short description... There's no ground rule! -->

{% for project in site.data.projects %}
{% unless project.hide and page.mask_hidden %}
### {{ project.name }} {% for tag in project.tags %}<span class="tag {{ tag.class }}">{{ tag.text }}</span>{% endfor %}

{% if project.image %}
![{{ project.image }}](/assets/img/projects/{{project.image}})
{% endif %}

{{ project.description }}

{% for link in project.links %} - [{{ link.name }}]({{ link.path }})
{% endfor %}

{% endunless %}
{% endfor %}


<!-- ## Ideas
Some project ideas I had but I haven't done (yet). 

Work in progress... Coming soon! -->

## Books
Some books I've read, liked, and would recommend.

{% for book in site.data.books %}
#### {{ book.title }} <span class="author">By {{ book.author }}</span>  {% for tag in book.tags %}<span class="tag {{ tag.class }}">{{ tag.text }}</span>{% endfor %}

<a href="{{ book.link }}" target="_blank">
<img class="book" src="/assets/img/books/{{ book.image }}" alt="{{ book.title }}" />
</a>
{% endfor %}
