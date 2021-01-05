---
title: Intro
weight: -21
---
#### In this documentation I will explain how to build a full website from Zero to Hero 
#### this is exciting totourial because we won't use any complicated codes such as (html , Css , bootstrab ,....etc), instad we will use mark down , we will go throw gitlab and show what is meaning by getlab and the diffrences between Get and Getlab 
#### also we will go throw two ways of building website , the standerd way , and the way i discovered 
#### before i get start let's take a breif on what is static generator website 

## What is a static site generator?

#### As websites grew to deliver more and more content, the web development industry found new ways to make the process of maintaining and updating sites more efficient. Years ago, we saw a move away from creating large numbers of individual files by hand, to a system where repeated sections of code could be included and repeated more easily. Web servers would perform that task on demand whenever a request for a resource was received. They’d faithfully combine templates and content, apply loops and logic, and return a page view whenever one was requested. And we’d have to ensure that they had enough horsepower to keep up with demand, fearing the times that our site became popular!

#### Static site generators (SSG) do much the same thing. They apply data and content to templates, and generate a view of a page which can be served to the visitors of a site.

#### The greatest difference between a static site generator and a traditional web application stack, is that instead of waiting until a page is requested and then generating its view on demand each time, a static site generator does this in advance so that the view is ready to serve ahead of time. And it does so for every possible view of a site at build time.

```

Think of a static site generator as a script which takes in data, 

content and templates, processes them, and outputs 

a folder full of all the resultant pages and assets.
```

### This has a number of valuable effects, but most important is that it shifts this work away from “request time” (when users ask for the view) to “build time” which is unrelated to when users ask for the view of a page. This “decoupled” architecture breaks the relationship between the number of visits to a site and the overhead of generating the views to service all of those visits.

[![Example file-tree menu](/media/ssg-host-flow.png)](/media/ssg-host-flow.png)

## What are you building?

#### At the heart of choosing the right tool is considering the job you need to do with it. Ensuring the the output of the site generator delivers the best possible experience for the users of your site is important to consider.

#### Are you building….

#### A site whose primary function is to deliver content? If so, a tool which priorities generating pages and URLs while giving you straightforward control over exactly what is output might be your best choice. Tools like Jekyll, Hugo, Nuxt and Eleventy do this very well indeed.

#### A site with a more complex application-like function? Some sites are less about “viewing” and more about “doing”. And while most SSGs can be used as the basis for a web application, others come with more advanced, client-side features ready-to-go. GatsbyJS, NextJS and SapperJS might provide some useful capabilities.
#### A large site with many thousands of pages? Static site generators are achieving faster and faster build speeds. But that can still take a little time. If you have very many pages to generate you’ll need to consider this. Some tools have incredibly impressive generation times. Hugo is particularly impressive. As is Eleventy and the recent updates to Jekyll.



