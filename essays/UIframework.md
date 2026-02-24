---
layout: essay
type: essay
title: "Chaotic Structure or Structured Chaos: A look into UI Frameworks"
# All dates must be YYYY-MM-DD format!
date: 2026-02-24
published: true
labels:
  - Engineering
---

<img width="200px" class="rounded float-start pe-4" src="../img/Framework/headache.png"> <br>

## This is another language. Right?

When I heard about Bootstrap 5 during a lecture, I was amazed: I thought, “Hey, I can pull from something that’s already been created? That’ll speed things up!” Then, I decided to open the documentation for it, and my excitement was cut short. I didn't feel like I was learning a styling library; it felt more like the first time I tried using C, when my only experience was with Java: “Another programming language, great.” There were class names everywhere (many of which I was still getting used to), and instead of writing CSS rules, I was copying and pasting various predefined labels to HTML elements. It was structured, systematic – sure – but it was also overwhelming, and slightly chaotic.

That brought me to a key question: if UI frameworks are this complicated, why use them instead of just hard-coding HTML and CSS? However, after working with Bootstrap 5 across multiple assignments and seeing first-hand how they operate and what they do, I have come to see UI frameworks not as a separate entity from HTML or CSS, but a complement to them: Bootstrap 5 and other UI frameworks are meant to help the user organize their code.

## I came to be an engineer, but now I feel like a stylist

Raw HTML and CSS offer freedom. You can design anything from scratch, define every margin, every color, every breakpoint. That level of control is powerful, and while it’s familiar enough to manage, that control is also equally as overwhelming. I constantly find myself nitpicking every little detail.

Should this margin be 16px or 20px?

How much space between the letters do I need?

How do I ensure this navbar behaves correctly?

These questions culminate in an exhausting mess, which usually ends in me having a headache rather than being pleased with how the product looks. And that’s even before I make one final edit that messes everything up.

I’ve found that this is where Bootstrap 5 comes in to save the day. Initially, yes, it was more cumbersome than just dealing with the HTML and CSS files because I was unfamiliar with it, and reading up some of the documentation took extra time away from editing a file, and it felt like a restriction on the coding process. Over time, I’ve come to view Bootstrap more as a line setter, something that gives rough guidelines rather than takes away tools. The grid system, spacing utilities, responsive breakpoints, and prebuilt components are solutions to common interface problems, usually found by someone struggling with the same issues I was with the raw HTML file.

Instead of writing custom lines for every change I want to make, I can describe intent directly in the markup:

```html
<nav class="navbar navbar-expand-lg coop-nav">
```

That single line communicates how the layout behaves across screen sizes and ensures that it is responsive. Now, instead of thinking “in the weeds” of pixel perfection, I can divert my attention to things like the overarching design layout. And it’s that adjustment in the way I think about it that further highlights the idea of it being a complement rather than a replacement.

## Usability: Designing for Humans, Not Just Developers

<img width="200px" class="rounded float-start pe-4" src="../img/Framework/diagram-success.png">

When comparing Bootstrap to raw HTML and CSS, most of the discussion tends to focus on developer efficiency, preferences, and what it does or doesn’t do for the developer of the webpage. But an equally important question is: what does this do for the end-user? And usability of the end-product is where the difference becomes most visible.

When building with raw HTML and CSS, usability depends entirely on the developer’s design decisions and their ability to understand both what makes for a good product for a user and how to implement said design. Navigation spacing, button contrast, font hierarchy, form feedback, hover states, mobile viewing, and other aspects of a webpage all require implementation by a developer. If any of these qualities are overlooked, the user experience is negatively affected.

Bootstrap approaches usability differently. It assumes that users interact with websites across devices, input types, and ability levels, and it is designed with that already in mind.

During some of our course exercises, I have had to manually test how changes made in one section affect another. There were scenarios where I was sure that everything was coded properly, but the moment I changed the screen size, everything looked “off”; columns were sized weirdly, the layout didn’t match the example, and some of the menus weren’t properly implemented. With Bootstrap, responsiveness is directly written in the layout system itself. That alone improves usability because no two users are guaranteed to have the same setup for viewing.

However, just like handing someone a fishing rod does not guarantee they will catch a fish, frameworks do not guarantee good usability; as a tool, it provides default solutions, not necessarily a solution to a specific need. A poorly structured page can still have low usability even if it uses Bootstrap components correctly. I can quickly go and put together a bunch of navbars, sections and containers with a footer, but that doesn’t guarantee that the product will make sense to the end-user.

Usability still requires the developer to understanding user needs, and implementation of bootstrap – it just takes some of the load off the decision-making stack. And as such, Bootstrap does not replace good design thinking, it supports it. It reduces the likelihood of accidental usability mistakes and encourages consistency across pages.

## So Why Bother?

UI frameworks are not necessary for small, personal projects. They are not required to build functional websites. Raw HTML and CSS remain powerful tools. However, in collaborative environments, under time constraints, and within scalable systems, frameworks provide the ability to reduce decisions, enforce consistency across multiple users, and allow users to share structure when everyone is using it.

In other words, they change design implementation from one-off styling methods to organized engineering. The investment of time and frustration pays off not because Bootstrap makes things easier immediately, but because it makes the resulting product more predictable over time. This can lead to better products for engineers to work with, better user experiences, and more time to expand the project or start on the next big thing.

## Note on AI usage:

I used ChatGPT and Grammarly AI to help refine structure, clarity, and flow in this essay. The ideas, opinions, and reflections are my own and based on my experience working with Bootstrap 5 this semester.
