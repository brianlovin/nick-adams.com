---
layout: default
title: Hudl Design System - Work -
nav_selected: work
header_nav_color: is--on-light
---

<div class="grid--maxwidth grid--outsidegutters">

    <header class="project-cover">
      <div class="project-feature" style="background-image: url(../../assets/img/projects/hudl-designsystem/bg-project-hudl-designsystem-feature.png)"></div>
      <a href="/work/" class="project-feature__backlink">&#8592; All Work</a>
      <h1 class="project-feature__title">Hudl Design System</h1>
    </header>
  
</div>

<div class="grid project-content">

  <div class="grid--maxwidth grid--outsidegutters">
      
    <div class="grid__col--twothirds">

      <p class="project__year">2017</p>
      <h2 class="project__headline">Retrofitting design consistency at a 7 year old company. </h2>
      <p class="project__subheadline">We didn't start out building a design system, but we ended up there.</p>

      <dl class="project__details">
        <div class="details__item">
          <dt>Company</dt>
          <dd><a href="https://www.hudl.com/" class="link">Hudl</a></dd>
        </div>
        <div class="details__item">
          <dt>Timeline</dt>
          <dd>12 Months, '16 to '17 </dd>
        </div>
        <div class="details__item">
          <dt>Status</dt>
          <dd>Under Active Development</dd>
        </div>
        <div class="details__item">
          <dt>View</dt>
          <dd><a href="#" class="link">design.hudl.com</a></dd>
        </div>
      </dl>  

<article class="overview__content" markdown="1">  

## Overview

On a team with 3 other Designers, 1 Developer, and 1 QA, I helped to build the foundations (visually and structurally) of a design system that would allow Hudl to build cohesion across their company and products.

This was my favorite and most personally invested project at Hudl, something that I’d been planting the seeds for since my first few months on the job. It was also the most holistic project and touched almost every corner of the company and product. This kind of systems design is what gets me excited. 

It started with understanding the way that people designed products at Hudl, so in this case the users were not external, but internal — product team itself. With this understanding we ended up building what now seems to be industry de jour: a design system. This consisted of defining design guidelines, building UI components, curating resources, writing extensive documentation, presenting, evangelizing, collaborating, educating, and troubleshooting. We then learned, refined, optimized, and measured (sometimes all at once) how effective the system was for helping our product team design better more cohesive products.

---

</article>
    
    </div>

    <div class="grid__col--onethird project__aside">
      
      <div class="aside__item">
       <h4 class="heading--sm project__subheading">Responsibilities</h4>
        <ul class="list--unordered">
          <li>Product Management</li>
          <li>User Research</li>
          <li>Visual Design</li>
          <li>UI Design</li>
          <li>Front-end Development</li>
          <li>Prototyping</li>
        </ul>
      </div>

    </div>

  </div>

  <div class="grid">

    <div class="grid--maxwidth grid--outsidegutters">

      <div class="grid__row">

<article class="casestudy__content" markdown="1">

# Case Study

***Note****: This is a looong case study, about a 20 min read. There was a lot involved in this project, and any pretty visuals are the least important parts of it (though you can scroll down and see a few of those along the way). The short of this is that design coherence and consistency, on many fronts, was a massive problem at Hudl. I was on a team that set out to solve it.*

## On Design Systems

*Design System* is a very broad (and sometimes flexible) term, I get that. In our case a Design System is really what we’d end up with, not what we set out to build. It was really just the collection of a bunch of resources and efforts to improve the way we designed products — many of which had already been ongoing. But now we had a more focused effort to work on them, under this umbrella effort we called our design system. 

Other organizations have their own implementation of this concept as can be seen with on Medium, but for us a design system was our:

- Design Principles
- Writing & Language Guidelines
- Brand Guidelines and Resources
- Visual Design Language (which we call *Uniform)*
- UI Libraries for web and mobile
- And all the documentation and tools and resources to make using the design system easier (our motto was “Make the right thing easier”).

We also built some pretty extensive technical architecture to make using all of this in our product possible, but that’s outside the real of the main design system. We called that our UI System, and there is a note about that later.

## Background

When I first started at Hudl, it was very much an engineering-driven product where speed of feature development was both the priority and measure of success. There was a gap between our product functionality and the market need, and closing that gap as soon as possible was the key to product-market fit and scalability. 

Over time, that fit was achieved and the product achieved some success, but the team never transitioned from that ship-now refine-later mentality. It had been written into the DNA of the company. While this approach was manageable (and arguably a strength) at a certain team size, once we started to rapidly grow our product team, cracks began to show.

As the company grew, more teams were created to work on more things, attacking different markets, with many different design directions. We worked in autonomous, but siloed groups, and this made cohesion an uphill battle. The design team was always a step behind — the minute we’d pause to create a broader solution, we’d turn around and have even more interfaces (that were designed in isolation) to try to account for. It started to be demoralizing, and we often resigned ourselves to local optimizations over global ones.

There were a few attempts at addressing this problem. The main attempt was a UI Component Library called Kickoff. This was essentially a side project of mine that began a few months after I started (years ago). I defined the rough beta version, and laid the groundwork for how to get it to v1, but could never dedicate more than a small amount of my time to it. So it was passed around to other designers who attempted to make more progress. Unfortunately, it never achieved more than fits and starts of progress. We would define a few UI components (buttons, some type styles, etc), but we struggled to maintain any momentum. Without a dedicated team we could never fully meet the demands of the designers and the rest of the product team. 

We also had a very big implementation problem. Even if we designed the worlds most amazing UI component, getting it usable within our product stack was a massive hurdle. Without solving this implementation problem, the UI Library would never power our product. More on this problem later.

Because of all of this, we ended up with fragmented interfaces and no cohesion within our product. And if that wasn’t enough, we soon had multiple *versions* of our product with the same fragmentation within each. The problem compounded. This greatly compromised our ability to build cohesive products we were proud of, and started to aversely affect the product experience of our customers (and we started to hear about it). 

We needed to recognize this problem and begin to address it before it became larger strategic liability. But we didn’t set out to build a design system, we set out to solve a problem.

## Research & Discovery

Understanding this problem began with our users, our product team. 

**User Interviews**
We talked to as many designers, developers, product managers, and quality analysts as possible. We tried to uncover the deeper problems they faced as they tried to build cohesive products at a rapid pace within our product stack. We watched how they worked, we listened to their frustrations, we examined the collective output of our team.

All of this began to pain a clearer picture of the problems we needed to solve.

**Product Audit**
While user interviews addressed the human side of this problem, there was also an objective quality consideration. Were our products getting better? Was the increase in team sizes and surface area improving the product? Or was the curve upside down. 

We took a holistic view of the entire product, walking through common workflows and user experiences. We looked at interface design, interaction design, copywriting, and on-boarding. We printed out almost our entire product and did group critiques to identify patterns, shortfalls, inconsistencies and fragmentation. 

This research gave us a sense of both the front end and back end of the problem. The situations that led our team to build products the way we did, and the result of that work. From here we could put together a plan to begin to address both.

## Problem Definition

We ultimately defined 3 major problems that would guide our work. We categorized them (in priority order) as:


### 1 -- Distribution
  This problem prevented us from getting any of our work into the actual product. The reason for this deserves another 2000 words, but put simply, our product stack was as fragmented as our interface design. Both the backend and the front end had a lot of legacy tooling, and there were many ways to do similar things — and we actually had 4 different versions of our existing UI library Kickoff. Funny if it wasn’t sad.

  We also recently moved to a micro-services architecture, but never really dealt with universal UI in a micro-services world. This all resulted in a situation where it was almost impossible to create any kind of UI library that was easily implemented into the product, universally distributed across all areas of our product, kept up to date or contributed *back into*, or that scaled with our growing product surface area.

  This was problem 0, let alone problem 1, so it was the first major thing we tackled as a group, even before we worked on any kind of UI design. We could have built the best button in the world, but if no one could use it consistently in our product, what did we really achieve? So we spent the next 6 months and completely rearchitected the way we managed UI in our micro-services infrastructure.

  We called this the Hudl UI System, and it’s something I’m extremely proud of, but like I mentioned it’s dense, so let’s skip past that part of the story…
  
### 2 -- Cohesion & Coverage
  The next major problem we identified was an obvious one, we didn’t have a consistent design language to guide UI component design, and the components we did have still were too limited to use in production interfaces. Because of this people ended up extending them or bending them to suit their needs, both visually and functionally, so again we get more fragmentation. Pretty soon we’d have 5 versions of a button because the first version wasn’t thoroughly designed. The hole we had to dig out of was now deeper.

  The good news about this problem was that it was fairly straight-forward to solve. We needed a clear design language, and we needed to implement that in a comprehensive and thorough UI library that could be used in our products. The bad news? We needed it yesterday.
  
### 3 -- Documentation
  The last major problem was around communication (an evergreen statement if there ever was one), specifically documentation. We needed to improve the way we explained design decisions, visual language guidelines, and UI library implementation details. So many members of the product team felt they didn’t know where to go to find information. And often when they found it, it was still lacking. This reality results in less people using the design system, a bad state to be in.

  So we ultimately made a point to consider documentation a product itself. To ensure that we put a lot of effort into communicating decisions, facilitating feedback during the design process, giving people ways to surface problems that should impact our priorities, and having a central place that everyone could go to find clear and definitive documentations on the whats, whys and hows of all the pieces of our design system.

With Problem 1 solved by our UI System, we could now move to problems 2 and 3.

## UI Library Architecture

We heard loud and clear that we needed a more comprehensive and thorough UI library for our product team to use, so we set out identifying what that would look like.

[[ screenshots of planning docs ]]

We outlined the high-priority items that we’re must-haves in our product interfaces: Color, Type, Space, Buttons, and the Reset, Utility Classes and Variables. These alone would get us a ton of wins within the product — even a consistent color scheme was something we lacked.

[[ screenshots of outlines ]]

If that would make up a beta release of our UI Library, we also needed a vision for what a 1.0 would look like. We needed to be able to paint a picture of what was coming, both for us to prioritize our work, and for the product team to get excited about, or give feedback on what was coming.

[[ more screenshots of outlines ]]

We felt pretty confident in the architecture of this library, and we began to build it, beginning with those high-priority items. But we soon got a bit stuck in the mud. We were making good progress building the things, but the issue was with the what and why behind the things. Why does it work like this? Why does it look like this? What *should* it look like? What’s our type style? What is our action color? What casing do we use on buttons?

We could make a lot of intelligent choices on some of these, but on the visual design front, we lacked a north start. We needed a design language — otherwise we were repeating the same mistakes all over again.

## Creative Direction

We were a bit lucky in the timing of our road block. The company had been on the search for a Creative Director that could help unify a lot of our branding and marketing, and eventually our product design. We were lucky to find this person: John Henry Mueller. He, being an excellent visual designer, product thinker, and communicator was the deus ex machina we needed to resolve our problem. He probably didn’t realize he’d need to be doing so much on the product side within his first few weeks of being hired, but he stepped up to the task.

He clearly saw the problems with a lack of design coherence in the same way we did, and began working on a way to solve it. Luckily this tied in pretty closely with a lot of the brand and marketing design work he was already working on.

There was a lot of design exploration (led mostly by him, but with some assists from the entire design team) to establish a solid design language and guidelines. 

All of this culminated in our new design north star, the Uniform Design Language.

*This was also the point, now that we had our Design Director, where we officially transition to a team working on a design system. We created a Design Systems group, brought in some help with Copywriting, IA, and User Research, and we were fully focused on building the Hudl Design System, and the Uniform Design Language and Uniform UI Libraries within it.*

## Uniform Design Language


## Uniform UI Libraries


## Before & After


## Measuring Results


## Related Projects

- Documentation
- Hudl UI System
- IA & Navigation
- Hudl Dictionary

</article>

      </div>

    </div>

  </div>

</div>