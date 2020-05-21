---
title: "Carpentries Style Lesson Development"
date: 2020-05-21
author: "Tim Dennis"
---

This is a compilation of some resources for teaching Carpentries style.

When you are preparing to teach, having a pedagogically sound framework to guide lesson development is very helpful. The Carpentries was created to teach data and coding skills to researchers using evidence-based approaches for teaching computing. Since the resources and guides for doing this has evolved over time, it can sometimes be daunting to find these resources.

## Lesson Design

Resources for how to develop a lesson:

* [Preparing to Teach](https://carpentries.github.io/instructor-training/15-lesson-study/index.html) - An episode from the Carpentries instructor training materials and goes over how we develop lessons (ideally) using learner profiles, backward design, learning objectives and formative assessments.
* [Carpentries Curriculum Development Handbook](https://carpentries.github.io/curriculum-development/) - a workin in progress, but outlines how to develop a lesson using the above principles.
* [Teaching Tech Together - Lesson Development Process](https://teachtogether.tech/#s:process) - A chapter from Greg Wilson, et. al., about how to develop a lesson. Many of the above topics are covered. Greg along with a collaborator, started Software Carpentry - the original carpentry.

Takeaways:
* Use backward desgin,
* Know your audience and spend time writing personas,
* Brainstorm content you want to cover (use a tool like concept maps to externalize your tacit knowledge of the subject),
* Formulate assessments (formative and summative),
* Then write the lesson to get from one assessment to another.

## Presenting and hosting your lessons

Once we have a sense of who and what we are teaching, we need a way to present, iterate on and maintain our lesson. An emerging pattern is to do this via static website using markdown, GitHub (or GitLab) and a static site generator, like Jekyll or Hugo. The Carpentries use a lesson template built in Jekyll to structure it's lessons. It's designed to give us ways to chunk up our lesson into episodes, add formative assessments to the lesson and build ot html using gh-pages in github. The barrier to entry is knowing GitHub, markdown and how the template system Jekyll works.

More about the technology of hosting the lessons:

* [Curriculum Development](https://carpentries.github.io/curriculum-development/technological-introductions.html) - how all the tech works together.
* [Lesson Example](https://carpentries.github.io/lesson-example/) - information on how to use the lesson template and the organization and styling information.

The benefits of the Carpentries template is multiple. It's open, so you can fork it for your own purposes. It is designed to implement the pedagogy we teach with:
* chunking content to reduce cognitive load,
*  formative assessments and
*  content that is styled that we can used to deliver.

All of it is knitted together in a well thought out website. Another benefit is that the Carpentries has a [lesson incubation process](https://carpentries.github.io/curriculum-development/the-lesson-life-cycle.html), so if we use this template we can possibly graduate it into a full lesson. 

The Carpentries lesson template isn't the only way to do things. If you are familiar with R Markdown you can use `bookdown` to stitch together multiple R Markdown files into a single page book with chapters, see: <https://afam188.netlify.app/> or the [Curriculum Development](https://carpentries.github.io/curriculum-development/technological-introductions.html). Both are in Bookdown.
