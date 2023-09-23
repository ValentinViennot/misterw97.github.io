---
layout: default
mask_hidden: true
---

# About Me

> “A great product manager has the brain of an engineer, the heart of a designer, and the speech of a diplomat.” - Deep Nishar

As an insatiably curious problem-solver, I transform the complexity of the world into innovation. My passion for transforming ideas into viable market solutions is rooted in a robust technical background in communication systems and computer science, fortified by T-shaped knowledge that spans a spectrum of modern tech topics and beyond.

My expertise revolves around dissecting complex systems, strategising impactful changes, and leading high-performing teams towards crafting valuable, influential solutions. I'm an ardent advocate for open-source models and values and am driven by a mission to augment individual and collective intelligence.

In my role as an executive [product manager](https://www.quora.com/Why-do-engineers-become-product-managers/answer/Fareed-Mosavat?ch=3&share=5287df25&srid=3XLCB) for Canonical, I've pioneered initiatives to position Ubuntu at the forefront of container images. Most notably, the cutting-edge Distroless-type Ubuntu containers: chiselled Ubuntu images.

Hand me a problem, and I'll deliver a solution. For better or worse, I persist until the job is not just done, but done right. I'm always on the lookout for audacious challenges that stretch my entrepreneurial spirit.

If you're searching for a partner who turns the intricate into the accessible, ignites change, and elevates collective intelligence, let's connect. You can reach me via [email]({{ site.email }}) or [Twitter]({{ site.twitter }}).

## Bio

[See my full resume on LinkedIn]({{ site.linkedin }})

> "The best way to predict the future is to invent it." - Alan Kay

I’ve always wanted to be an inventor. Since I was a child, I wanted to solve all the problems with my ideas – often causing my parents and sisters to yell at me, until they eventually told me: “Valentin, you need to be an engineer”. Was that the word for an inventor? Without a doubt, I joined the top-ranked INSA de Lyon engineering school right after graduating from High School.

| <img src="/assets/img/logo-insa.png" alt="INSA Lyon" width="40"/> | **INSA Lyon** | Communications Systems | 2015-2020 | [details]({{ site.linkedin }}) |

At INSA de Lyon, I sought to develop a broad range of skills and knowledge, and to learn how to communicate complex ideas and concepts with other smart people. I also learned how to code for some side-projects, and I quickly realized that programming was the perfect way to bring my inventions to life.

| <img src="/assets/img/logo-ibm.png" alt="IBM" width="40"/> | **IBM** | Full-stack Software Engineer | 2017-2020 | [details]({{ site.linkedin }}) |

Looking for a new challenge, I applied for an apprenticeship with IBM and the [IBM Garage](https://www.ibm.com/cloud/architecture/careers), where I worked as a full-stack engineer. My time at IBM taught me two important lessons: first, that IT is at the heart of every business and is driving disruption in every industry; and second, that user-centered design is essential for innovation and the development of new ideas.

| <img src="/assets/img/logo-epfl.png" alt="EPFL" width="40"/> | **EPFL** | Exchange student | 2019-2020 | [details]({{ site.linkedin }}) |

Seeking to further develop my skills in user experience and data science, I spent one semester at the EPFL. This experience helped me gain a better understanding of these fields, and it also increased my self-awareness – I realized that I am an entrepreneur at heart.

| <img src="/assets/img/logo-ubuntu.png" alt="Canonical" width="40"/> | **Canonical** | Executive Product Manager | 2020 | [details]({{ site.linkedin }}) |

Faced with the decision to start my own business [or](https://productcoalition.com/you-are-not-the-ceo-9f665d0e4a46) become a product manager, I first decided to pursue the latter, with a focus on open source software and to join Canonical as a Product Manager.

Canonical's mission is to bring free software to the widest audience. One of the biggest barriers to adopting open source software is security and supply chain vulnerabilities, particularly with cloud-native software packaged as container images. Rather than shipping Ubuntu IN container images, we re-thought everything from the bottom-up and built Chiselled Ubuntu in order to distribute Ubuntu AS container images. I launched Chiselled Ubuntu as a completely new product offering inspired by Distroless but with the advantages of a Linux distro.

As a Product Manager for Canonical, I worked every day to improve Open Source and make it sustainable, while also gaining valuable product management skills and contributing to the broader goal of increasing human intelligence.

I am now taking it a step further.

In October 2023, I joined Entrepreneur First as a Founder in Residence in order to find a solution to funding Open Source!


<!-- > "What's the best thing you could be working on? and, why aren't you?". — [Paul Graham](http://paulgraham.com/procrastination.html) -->

<!--
Minified version:
I've always wanted to be an inventor. Since I was a child, I wanted to solve all the problems with my ideas. Without any doubt, I joined the top-ranked INSA de Lyon engineering school right after graduating from High School.
Learning how to code for some side-projects, I quickly realized it was the perfect way to bring all my inventions to life. More than that, programming isn't related to only one field and neither were my ideas.
Willing to learn from the real world as soon as possible, I joined IBM in 2017 for a 3-year apprenticeship as a Full-Stack Software Engineer -- currently working in the IBM Garage for Cloud division.
After spending a semester at the EPFL studying user experience and data science, I came back with a new mindset: entrepreneur is the right word for inventor!
I'm determined about my next move: If you're looking for a Product Manager who's passionate, curious and motivated to learn; not only a thinker but a maker... let's chat and see how we are going to improve our world together!
-->

## Projects and Contributions

> "The most valuable thing you can make is a mistake - you can't learn anything from being perfect." - Adam Osbourne

Welcome to my portfolio of projects and contributions! In this section, you'll find a selection of my most significant and noteworthy work. From side projects to school assignments, each of these projects showcases my passion for innovation, problem-solving, and making a real impact in the world. Whether you're looking for inspiration, guidance, or simply want to learn more about my work: Let's talk!

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

> "It's not about ideas. It's about making ideas happen." - Scott Belsky

> "Success is not final, failure is not fatal: it is the courage to continue that counts." - Winston Churchill

> "Design is not just what it looks like and feels like. Design is how it works." - Steve Jobs

Work in progress... Coming soon! -->

## Books I've Read and Recommend

> "The only limit to our realization of tomorrow will be our doubts of today." - Franklin D. Roosevelt

I've included a list of some of the books that have had the biggest impact on me, and that I would recommend to others.

{% for book in site.data.books %}
#### {{ book.title }} <span class="author">By {{ book.author }}</span>  {% for tag in book.tags %}<span class="tag {{ tag.class }}">{{ tag.text }}</span>{% endfor %}

<a href="{{ book.link }}" target="_blank">
<img class="book" src="/assets/img/books/{{ book.image }}" alt="{{ book.title }}" />
</a>
{% endfor %}
