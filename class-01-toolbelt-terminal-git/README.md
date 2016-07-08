###Class 1: Introduction to the Tools and Fundamentals of Development

<a id="top"></a>
# Today's Plan: Week 1, Monday Lecture

This first day of class is an all-day session with the students that is mostly lecture.

- [Kickoff! (with slides)](#kickoff) *[60 minutes]*
- [Academic Overview (with slides)](#academic) *[30 minutes]*
- [Verify Student Toolbelts](#toolbelt) *[30-45 minutes]*
- [Unix & Git (with slides)](#ug) *[until lunch]*

*Lunch Break*

- [Set up a JavaScript linter](#linter) *[15 minutes after Unix/Git is finished]*
- [Go over the assigned readings](#readings) *[90 minutes]*
- [Code demo](#code) *[60 minutes]*

## Readings

- HTML Chapter 1: "Structure"
- HTML Chapter 8: "Extra Markup"
- HTML Chapter 17: "HTML5 Layout"
- HTML Chapter 18: "Process & Design"
- JS Chatper 1: "The ABC of Programming"

<a id="kickoff"></a>
## Kickoff!

[Slides: 1-first-day-orientation.pdf](slides/1-first-day-orientation.pdf)

This is the welcome and introduction to Code Fellows. Students will meet the campus manager and learn about campus operations and policies.

[-top-](#top)

<a id="academic"></a>
## Academic Overview

[Slides: 2-academic-overview.pdf](slides/2-academic-overview.pdf)

The instructor will give an overview of the topics to be covered in this course and how those topics fit into the overall academic program at Code Fellows.

[-top-](#top)

<a id="toolbelt"></a>
## Verify Student Toolbelts

By doing a few quick tests and exercises, as detailed below, ensure that students have functionality of all of the core pieces of their development environment:

- Atom: type `atom` in the command line to verify that it opens properly. Command line tools may need to be installed.
- Atom packages: `apm install linter minimap open-in-browser` installed.
- Chrome: how to open the console/dev tools :

	   	- elements
	   	- console
	   	- sources
	   	- resources

- Git: enter `which git` in the command line to verify installation
- Directory structure: Have students set up a directory at ~/codefellows/201/ in which they will store their classwork. Go over directory structure in general; compare to GUI.

[-top-](#top)

<a id="ug"></a>
## Unix & Git

[Slides: 3-unix.pdf](slides/3-unix.pdf)
[Slides: 4-git-intro.pdf](slides/4-git-intro.pdf)
[Slides: 5-git-branching.pdf](slides/5-git-branching.pdf)

Slides to introduce students to core concepts of file management from the command line and the fundamentals of Git and GitHub.

[-top-](#top)

<a id="linter"></a>
## Set up a JavaScript linter
Have students go to the command line and `apm install linter-eslint`. Have them open a new tab in their terminal ( which also shows them that this is something they can do!) and cd to their home directory. Then `atom .eslintrc` in their home directory and copy/paste the contents of the .eslintrc file (send it through the class Slack channel, which is a nice verification of that functionality). Then go into the package settings in Atom and make sure that it is looking for that .eslintrc

[-top-](#top)

<a id="readings"></a>
## Go over the assigned readings

**HTML Chapter 1: "Structure"**

- p.15: How pages use structure
- p.20: HTML describes the structure of pages
- pp.21-22: Tags as containers (great graphic page)
- p.24: Tags
- p.26: Attributes
- p.33: Code in a CMS

**HTML Chapter 8: "Extra Markup"**

- p.179: Evolution of HTML
- p.181: Doctypes
- p.182: Comments
- p.183: Class & id attributes
- p.185: Block vs. inline
- p.191: Meta tags
- p.193: Escape characters
- p.194: Special characters

**HTML Chapter 17: "HTML5 Layout"**

- Semantic HTML
- Traditional layout vs. HTML5
- Header, footer, nav, aside, section, figure, div

**HTML Chapter 18: "Process & Design"**

- Things to think about when starting a project
  - Who is the site for?
  - User stories
  - Sitemaps
  - Wireframes
- Visual hierarchy, grouping, navigation

**JS Chatper 1: "The ABC of Programming"**

- p.16 	Designing a script
- p.28 	Objects & properties
- p.30 	Events
- p.36 	Browsers & document object
- p.40 	How a browser sees a web page
- p.44 	How HTML, CSS, JS work together			
- p.45 	Progressive enhancement
- p.51 	JavaScript runs where it is found in the HTML

**We also need to discuss the role of *pseudocode*, which is something the Duckett text does not cover very well.

[-top-](#top)

<a id="code"></a>

##Tonight's Assignments
###1. Learning Journal AKA Today I Learned...
One of the most effective tools in adult learning is reflection. By writing coherent summaries of some lesson learned, we cement that learning and deepen our understanding of a subject.

**Tasks**

- Each day, you will write an entry in your learning journal about some lesson you learned that day. Your entry may contain code samples, links to additional resources you found, or anything else you feel is relevant. I have found a correlation between students who write consistently in their journals, and student who succeed in class. Take this assignment seriously.

- Create a repository on Github called `daily-learning-journals`. Copy the URL for this to your clipboard.
- **Instead of cloning the repo**  we will create a directory in your 201 directory, also called `daily-learning-journals` and we will set the remote from the command line.
- Move into your new directory:`cd daily-learning-journals`  
- then `git remote add origin <paste your Github URL here>`
- Now we will be able to push our learning journals up to the remote Github repo.

- Create a new markdown file for each day, e.g. "LJ-code201-day1.md"
- In that markdown file, create an h1-level header at the top entitling the document with the day's entry, e.g. `# LJ Code 201 - Day 1`
Write to your heart's content. Write about what you learned, what may or may not have happened in group work, what you're hoping for, etc. This is for your own reflection more than it is just another thing for us to assess you on.
See "sample-LJ.md" for an idea of how it should look.

**Submitting Your Work**

Please paste a link to each day's entry into the Canvas assignment corresponding to that day. This assignment is due before 9 am on the day after it is assigned (e.g. assigned on July 18th, due the morning of July 19th). Late entries will not be accepted.

###2.Readings
- HTML Chapter 2: "Text"
- CSS Chapter 10: "Introducing CSS"
- JS Chapter 2: "Basic JavaScript Instructions"

###3. Code Assignment
We will do today's lab assingment together in class during the "live code demo"

## Live code

This code demo is to help students be ready to complete the first assignment and also to show off some functionality of the REPL and Chrome Developer Tools. This demo should also reveal any lingering issues with student computer setups.

[-top-](#top)
