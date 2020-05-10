---
layout: default
---

# About Me

I'm a Senior Engineering Student, graduating my Master degree in [Communication Systems](https://www.insa-lyon.fr/fr/formation/telecommunications-services-usages) in September, 2020.
I've been working with Cloud technologies as a full-stack software engineer at the [IBM Garage](https://www.ibm.com/cloud/architecture/careers) as part of my 3-year apprenticeship.    
Many projects are stuck because they lack a product vision. I put my creativity, cross-functional knowledge and my problem solving skills gained from my engineering background to work. I eventually give leadership and obtain great results, with the best school grade or a happy client!    
Do you need a [Product Manager](https://www.quora.com/Why-do-engineers-become-product-managers/answer/Fareed-Mosavat?ch=3&share=5287df25&srid=3XLCB) that can bring your product to the next step? Reach me out.

<!-- I'm looking for the Product Manager job that will put my creativity, leadership and engineering to work. -->

<!-- 
3 main qualities:
1. My Leadership. I usually have strong opinions, particularly when it comes to group project. Being able to influence the group to follow them, giving arguments, facts and demonstrating analytical abilities is important to me. In almost every group project I participate in, I tend to become the main leader.

2. My Creativity. That's where I am the most comfortable: having ideas and elaborating them to solve problems. They might be a bit crazy sometimes... But I've recently learned that even the dumbest idea might transform to a great product and that one to create something is always better than one to only have ideas. While creating, the ideas not only won't stop coming but are even more! I apply this strength on every project and on daily-basis.

3. My Engineering (+ Curiosity). This should be my main strength if you only look at my cursus... and it is actually really powerful. Thanks to that, I feel confident designing and building concrete and technical solutions to a problem. I have a wide knowledge of available technologies and how to implement them. I demonstrated this strength during my whole cursus and on a daily basis during my internship at IBM as software engineer.


3 Negative qualities/default: 
- Time Management -- If time management is your weakness, then you can say that you’re controlling it by using reminders, alarms and calendars on digital devices you have.
- Getting Stressed Around Deadlines -- While it’s reasonable to worry a bit because of an approaching deadline, getting too worked up about them can be seen as a negative. You can say that you’re battling this issue by setting reasonable deadlines instead of ambitious ones like you used to.
- Being Too Critical of Yourself -- Maybe you’ve been too critical of yourself, especially in the beginning of your professional career — generating too much negativity can definitely be seen as a weakness. But today, you choose to actively pause and celebrate your accomplishments, which helps with self-esteem

My worst idea?
"So many, but it always learn you something." : find one
They might be a bit crazy sometimes... but even the dumbest idea might turn into a great product. I've recently learned that one who creates something is always better than one who only has ideas.
 -->

## Bio
[See my full resume on LinkedIn]({{ site.linkedin }})

I've always wanted to be an inventor. Since I was a child, I wanted to solve all the problems with my ideas -- often causing my parents and sisters to yell at me, until they eventually told me: "Valentin, you need to be an engineer". Was that the word for an inventor? Without any doubt, I joined the top-ranked INSA de Lyon engineering school right after graduating from High School.

| <img src="/assets/img/logo-insa.png" alt="INSA Lyon" width="40"/> | **INSA Lyon** | Communications Systems | 2015-2020 | [details]({{ site.linkedin }}) |

Learning how to code for some side-projects, I quickly realized it was the perfect way to bring all my inventions to life. More than that, programming isn't related to only one field and neither were my ideas.

As I couldn't wait any longer, I started to send applications to different companies to join the Master of IT and Communication Systems in apprenticeship!

| <img src="/assets/img/logo-ibm.png" alt="IBM" width="40"/> | **IBM** | Full-stack Software Engineer | 2017-2020 | [details]({{ site.linkedin }}) |

That's how I joined IBM in 2017 for my apprenticeship as a full-stack engineer.
Working there I realized two main things:
- not only IT is part of any business, but it's disrupting all of them
- design, and most importantly user-centred design, is core to innovation and building new ideas

| <img src="/assets/img/logo-epfl.png" alt="EPFL" width="40"/> | **EPFL** | Exchange student | 2019-2020 | [details]({{ site.linkedin }}) |

I needed to leave my engineer bubble. I spent one semester at the [EPFL](https://www.epfl.ch/schools/ic/communication-systems-msc/) with two goals: understanding user experience and acquiring knowledge about analytics and data science. Not only did I succeed in both while leading creative projects, but also came back with a new mindset: entrepreneur is the right word for inventor!

All in all, I'm sure about my next step: I want to be a product manager – the CEO of the product. If you're looking for an inventor who's passionate, curious and motivated to learn; not only a thinker but a maker... let's chat and see how we are going to improve our world together!

> "Willing to think, Curious to learn, Enthusiastic about making" is my motto.

## Portfolio

This section is about some projects I lead and played a great part in.
Wether it's side or school projects, I'd be happy to discuss them with you!

<!-- First one is the most recent active one.
Some of them link to a more detailed README, some are just a title and a short description... There's no ground rule! -->

{% for project in site.data.projects %}
{% unless project.hide %}
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
Some books I've read, liked and would recommend.

<!-- I will also try to put there with my opinion about them and a link to goodbooks.io. -->

{% for book in site.data.books %}
#### {{ book.title }} <span class="author">By {{ book.author }}</span>  {% for tag in book.tags %}<span class="tag {{ tag.class }}">{{ tag.text }}</span>{% endfor %}

<a href="{{ book.link }}" target="_blank">
<img class="book" src="/assets/img/books/{{ book.image }}" alt="{{ book.title }}" />
</a>
{% endfor %}
