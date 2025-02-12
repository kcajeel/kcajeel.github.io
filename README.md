# My Website

I figured I should make a personal website to showcase my work and give a short bio for job applications and because I just want a website. 
This document will cover the website structure and general design ideas I have. 

## Contents

- [Constraints](#constraints)
- [Website Structure](#website-structure)
  - [About Me Section](#about-me-section)
  - [Experience Section](#experience-section)
  - [Projects Section](#projects-section)
  - [Contact Section](#contact-section)
- [Future Work / Ideas](#future-work--ideas)

## Constraints

- My website must load in under 2 seconds. It should be simple and purposeful, with as little JavaScript as possible (ideally none). 

- My website must take under 5MB of bandwidth to load. There is no reason for a simple static website to need more than that. 5MB is an arbitrary number, but I should have no problem loading my site within that limit. 

- My website must have a Chrome Lighthouse Accessibility score >= 90. I don't want my website to be difficult to navigate for users with screen readers and other assistive technologies. 

- My homepage must be homemade. Other parts of the website may be created with some static site generator or other tool, but the homepage needs to be made by me. 

- My website must be navigable on mobile devices (subjective). It should look similar to how it looks on a desktop, with no elements or images out-of-place or covering any content. 

## Website Structure

The website will be split into different sections detailing various aspects of my life and work. Basically, it's like a resume but in a different format and with pictures. 

These are the sections I will have: 

  - About Me

  - Experience

  - Projects

  - Contact

A description of each section is provided below. 

### About Me Section

This section will contain a short description of my interests and career goals. I think I could mention my values and the kind of work I enjoy doing. 

I've seen personal websites where people have an image of the person in this section, but I don't want a picture of me on the open internet. There are probably enough from social media, I don't want to add any. 

### Experience Section

This section will list and describe my work experience. I plan to add images of each company, and maybe of each job location as a background. 

I don't want the user to have to scroll a ton to reach each website section, so I might make each experience section collapsible or have the user rotate through a carousel. I'll figure this out after I add the content I want. 

### Projects Section

This section will list a few selected projects and briefly describe them, with a link to their respective GitHub repositories. 

A few of my projects are commandline-based and written in Rust. I've thought about compiling them to WASM and creating an interactive "shell" on the website so that visitors can actually use the programs I've written. 

I have no experience doing anything like that, so it's probably more difficult than I'm imagining. But, I think it would be very cool. 

### Contact Section

This section will list my contact information (LinkedIn, GitHub, Email) with links to each. 

I'll use speculative loading so that the LinkedIn and GitHub links load faster for my visitors. I don't know what email client they use, so I won't do this for the Email link. 

## Future Work / Ideas

If I think of anything else, I'll add it to this section. Right now, my website skeleton is created, but I still need to finalize the styling and content. 
