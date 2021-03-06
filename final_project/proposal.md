# Final Project Proposal Template

## Project Title

**p5.js Spanish website translation tracking and development of a guide for new translations**

*This project consist in a collaboration with the internationalization of p5.js, which has been driven by many collaborations in terms of framework development and translations writing. A tracking and fixing of the former Spanish translation will be developed. A guide document will also be written for new translations from the existing translation documentation in the p5.js repo. This project will be focused on first-time contributors to the project and non-English speakers.*

<!-- _Write an abstract -- describe your idea in a short paragraph, 250 words maximum._ -->

## Team Members

[Guillermo Montecinos](https://github.com/guillemontecinos)

## Define the problem.

The [internationalization](https://p5js.org/es/) of p5.js through it's website has been a great decision in terms of spreading p5.js' ideals and making programming easier to non-English speaking users. This process has meant a great effort in order to designing a flexible website structure and keeping track of the changes made in the English. Currently there are two official translation: Spanish and Chinese. The Spanish version hasn't been thoroughly checked by other people and there are also some missing translations due to the ever-evolving nature of the website, with new additions to the reference, examples and tutorials.

In terms of structure, p5.js website has [two](https://github.com/processing/p5.js-website#internationalization-i18n-and-structure) ways of building. The Reference pages are entirely written in English and swapped out using JavaScript. On the other hand, the non-reference pages are developed in HTML using handlers which display the text contents in the language the page is to be rendered, which are stored in .yml files.

All the information for the website translation can be found in the [README](https://github.com/processing/p5.js-website) file of the website repo, but it can be still improved, so that it can be wrapped in a separated file with examples and a more detailed explanation as it's said in the [issue #23](https://github.com/Open-Source-Studio-at-ITP/Final-Projects/issues/23) of the Final Projects repo.

The final audience of this project are non-English speaking first-time p5.js contributors and users -this includes coders, educators and students-, and collaborators interested in develop and contribute in new translations of the website.

<!-- _What is the current state of things? What issue do you wish to solve and why? Who is the audience?_ -->

## Address Greater Landscape

p5.js is an open source community-driven project created by Lauren McCarthy and the [Processing Foundation](https://processingfoundation.org) as a web re-interpretation of Processing. Technically, p5.js is a set of functions for JavaScript that allows the user to create visual and sound interactive applications on the browser, with a easy-to-use syntax.

As a part of the Processing Foundation, p5.js was intended as a vehicle for spreading coding literacy between the non-programmer community, specially the under-represented and discriminated ones. Furthermore, p5.js is a [Free Libre Open Source Software (FLOSS)](https://medium.com/processing-foundation/processing-and-floss-d35aa4607f4c) and therefore an alternative to corporate and exclusive softwares.

<!-- _Please address how the open source project you are creating or contributing to fits into a greater field or tech landscape. Who has done similar work before? How are you building off this, and how? What sets your project apart from your colleagues?_ -->

## Deliverables

This collaboration will be split in two parts: (1) the track, correction and translation of non translated contents of Spanish website in order to solve the gaps between the last translation done by @montoyamoraga and the last modifications an adds on p5.js reference and examples, and (2) the development of a TRANSLATION.md document in which all the guidelines and examples for future translations of the website are wrapped, with a focus on first-time contributors to the project and non-English speakers.

1. Track, translation and correction of Spanish p5.js website
2. Track, translation and correction of Spanish p5.js reference
3. Track, translation and correction of Spanish p5.js examples
4. Write TRANSLATION.md

<!-- _Propose a clear list of deliverables._ -->

## Implementation

This project won't require particular technical skills besides Git, Github, basic JS and basic HTML. The implementation of this collaboration will consist in the modification of HTML, JS and .yml files where the translation content is stored, and the creation of a Markdown file.

<!-- _Describe the technical details about your implementation and development process._ -->

## Timeline

This project will be completed over 5 weeks (Nov 6 - Dec 11). Describe a timeline in detail below.

### Week 1

* Track, translation and correction of Spanish p5.js website
* Track, translation and correction of Spanish p5.js reference (1/2)

### Week 2

* Track, translation and correction of Spanish p5.js reference (2/2)

### Week 3

* Track, translation and correction of Spanish p5.js examples (1/2)

### Week 4

* Track, translation and correction of Spanish p5.js examples (2/2)
* Write TRANSLATION.md (1/2)

### Week 5

* Write TRANSLATION.md (2/2)
* Final documentation

## Documentation

I will document this project in my own [OSS repo](https://github.com/guillemontecinos/itp_fall_2018_open_source_studio) through posts published in the Final Project folder. Additionally, the project progress will be tracked on issues I'll post in the p5.js repo and the final pull requests I'll commit when the project is finished. I'll make an effort to cross-reference post and issues/PRs.

<!-- _Describe your plan for documentation. Will you keep a blog? Make videos? Some project management tool? Track everything on GitHub as issues?_ -->

## Accessibility
TODO
<!-- _What challenges are there related to your project in terms of Web Content Accessibility Requirements: [see the Accessibility assignment as a reference](https://github.com/Open-Source-Studio-at-ITP/Syllabus/blob/source/accessibility-assignment.md#instructions)._ -->

## Mentoring

For this project a mentor guide will be needed mostly for organizing and structuring the output guide/wrapping file. I propose the following highly experienced people for this:

* Lauren McCarthy
* Aarón Montoya-Moraga
* Kenneth Lim

<!-- _List some possible mentors for this project. Describe what kinds of help you need (technical, conceptual, outreach, etc.)_ -->

## More about you

I'm interested in the weird space where technology and art intersects and can describe myself as a technologist and a musician.

I am also an educator and co-founder of a media arts school in Chile called [Coded Escuela](http://codedescuela.cl), where a group of artists and tech people teach creative code and FLOSS tools to creative people. With Coded we have contributed with the internationalization of Processing in Spanish by teaching creative coding with p5.js and with the translation of the website and book which was leaded by [Aarón Montoya-Moraga](http://montoyamoraga.io/) and supported by us.

This project is framed within my previous work in the field of FLOSS education and with the Processing Foundation (on 2017 I [spoke](https://www.youtube.com/watch?v=Ix5RTKRJW0A&index=6&list=PLMVpERuYgvujgdaBluS0_LLLn8T83laaa) in the Processing Community Day @ MIT Media Lab).

You can check my work on [Github](https://github.com/guillemontecinos) or visiting my [Portfolio](http://guillemontecinos.cl/).

<!-- _What are your interests and experience? Have you contributed to other open source projects? What barriers or concerns have kept you from contributing to free and open source software? If you have an online portfolio, github account, or other relevant documentation of your work, please include links. If the project is a collaboration, a section should be included for each collaborator._ -->

## References

This proposal template was created with material and advice from:

- [How to write a proposal for GSoC](http://teom.org/blog/kde/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/)
- [Processing Foundation GSoC application template](https://docs.google.com/document/d/1UFcWh2IWqhICh4YIFNwtKUaWWXifaBB67rjPxbYzjbE/edit)
- [Getting into Summer of Code programs](http://exploreshaifali.github.io/2015/06/08/getting-into-summer-of-code-programs/)
