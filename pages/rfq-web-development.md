---
layout: page-fullwidth
title: "Request for Quotation (RFQ) - Website Development for The Carpentries"
permalink: /rfq-web-development/
---

[This page is also available as a PDF file.](/files/pdf/RFQ-Website-Development-Carpentries.pdf)

## About The Carpentries
[The Carpentries](https://carpentries.org/) is an organisation building capacity in essential data and computational skills for conducting efficient, open, and reproducible research. Our community comprises Instructors, Trainers, Maintainers, Member Organisations, and more from institutions around the world who share our [mission](https://carpentries.org/about/) and [core values](https://carpentries.org/values/). The Carpentries is a fiscally sponsored project of [Community Initiatives](https://communityin.org/), a registered 501(c)3 non-profit organisation.

The Carpentries website and accompanying handbook provide content about The Carpentries program. Our website sees an average 7K views / month. The Carpentries utilises a static site hosted on GitHub in alignment with The Carpentries’ values of transparency (all contributions are publicly tracked) and community collaboration (anyone can open issues for discussion or submit PRs towards content, navigation, etc.).

## Project Overview
The Carpentries is looking for a developer to build a theme for our website using the [Hugo static site generator](https://gohugo.io/). We previously received funding to improve the accessibility and the information structure of our website and handbooks. We have been working toward this goal, beginning with contracting a web designer to evaluate the information architecture and design of our website. The contractor worked with our team and community to outline mockup designs for an updated website and provided recommendations for our handbooks. We are now in need of further support to complete the development for our website.

## Project Details
We are looking for a developer to build a theme using the [Hugo static site generator](https://gohugo.io/). The Carpentries will provide stylistic and aesthetic direction to the project.

### Deliverables / Desired Outcomes:
- Modular Hugo Theme
  - The provider will use [existing designs](https://www.figma.com/file/nMw86vRMV54cU6beIPlleF/The-Carpentries--%7C--Website-Redesign?type=design&node-id=0-1&mode=design) provided by the Carpentries as a guide for a static site theme using [Hugo](https://gohugo.io/).
  - The provider will develop reusable modular layouts to form a template that can be used across all desired website pages.
  - The Carpentries will provide example and existing Markdown and JSON content for the provider to use to demonstrate the developed theme.
  
### Functionality Considerations:
- Site Generator
  - [Hugo static site generator](https://gohugo.io/)
- Modular Page layouts
  -Templated layouts built from reusable components (header, footer, navbar, main page content, etc.) to facilitate the following page types:
    - Home page ([example](https://beta.carpentries.org/))
    - Page with sidebar content ([example](https://beta.carpentries.org/about-us/))
      - Used to generate program information pages
    - Catalog page with search/filter/sort options ([example 1](https://beta.carpentries.org/workshops/upcoming-workshops/), [example 2](https://beta.carpentries.org/blog/))
      - Used to generate lists of workshops, curricula, etc.
    - Profile pages ([example 1](https://carpentries.org/team/), [example 2](https://carpentries.org/instructors/))
      - Used to generate Person profiles for our various community segments 
    - Page without sidebar content
      - Used to generate general information pages 
  - Layouts should use includes/shortcode blocks to make use of modular content and sub-sections
  - Similarly, sidebars should use includes/shortcode blocks to make use of modular content
- Rendering Data Feeds
  - The Carpentries has existing examples of JSON from API responses to act as content for inclusion into the proposed Hugo theme.
  - The provider would not need to work on the mechanism to get the feed data itself but would work on including the supplied examples into the template, e.g. we provide a list of workshops as JSON which would then need to be rendered by the theme.
- Searching and Filtering of Site and Data Content
  - The provider will include site-wide search using Google embedded widgets.
  - The provider will develop searching and filtering capability of lists of catalogued content from data feeds, e.g. lists of workshops, lists of blog posts, with the ability to select and deselect tagged list elements
- Hosting and Deployment Processes
  - The Carpentries already has a deployment pipeline based on GitHub, Netlify, and Amazon Web Services. The developed solution will need to fit into this existing framework. The Carpentries Technology Team will work with the provider as development progresses to ensure this works smoothly.
- Plugins
  - We would prefer a minimal reliance on external plugins to reduce maintenance overhead.
- Accessibility
  - We expect any template to comply with WCAG 2.2 AA standards
  - If possible, the provider may demonstrate previous sites they have developed that include accessibility elements, e.g. contrast colour palettes, accommodation of screen readers 

### Existing Resources:
- [Current Website](https://carpentries.org/)
- [Current Code Repository](https://github.com/carpentries/carpentries.org/)
- [Phase 1- Mock Up](https://www.figma.com/file/nMw86vRMV54cU6beIPlleF/The-Carpentries--%7C--Website-Redesign?type=design&node-id=208-808&mode=design)
- [Phase 1- Code Repository](https://github.com/carpentries/beta.carpentries.org)

### Contractual Relationship:
The organisation selected to support this project will be contracted via an Independent Contractor or Service Agreement with our fiscal sponsor Community Initiatives on behalf of The Carpentries.

## Selection Criteria
- Evidenced ability to meet project goals
- Organisation’s approach to meeting the project goals
- Experience designing static websites
- Experience working with open-source, community-driven projects 
- Experience managing projects on GitHub
- Experience developing websites compatible with accessibility standards (e.g. WCAG 2.1 AA, Section 508, EN 301 549)
- Cost-Benefit Evaluation
- A minimum of $1M General/Professional Liability Insurance coverage

## Timeline
- Project Kick-off Target Date: To be determined with contractor
- Project Completion Target Date: To be determined with contractor

## Budget
- $10,000 - $25,000 USD

## Submission Instructions
Submit your organisation for consideration by emailing the following to [team@carpentries.org](mailto:team@carpentries.org):
- Overview of your organisation’s experience and approach
- Drafted statement of work (including deliverables and a proposed timeline from kickoff to completion)
- Share portfolio of 2-3 static site projects
- Itemized price quotation (including currency)

_Deadline: Submissions will be accepted until a contractor has been selected._

## Questions
Please send any questions concerning the RFQ to [team@carpentries.org](mailto:team@carpentries.org)


[This page is also available as a PDF file.](/files/pdf/RFQ-Website-Development-Carpentries.pdf)
