# Log

The daily digest of my self-directed learnings.

<br>

---

## 10 May 2022

Added basic socket communication to the lesson chat app for the freeCodeCamp.org
curriculum.

---

## 9 May 2022

Learned how to use the Nodejs package passport to do social login. Registered my
application with GitHub and setting up the authorization flow with passport was
pretty straightforward. Later I will have to expand this app to use other social
login options as well.

---

## 8 May 2022

Learned about hashing and salting passwords in Nodejs today. I've been aware of
these ideas for a long time, however I've never before written user
authorization code before so I've never used it in practice until now. After
finishing the tutorial project and reading more about hashes and salts I now
have a better understanding of what they are and how they work.

A **Hash** is a one-way cryptographic function that converts a given piece of
variable-length data (such as a password) into a fixed-length output that is
unique to the given input. Hash algorithms are designed in such a way as to
avoid giving the same output for different pieces of input data (which would be
called a *collision*), even if the inputs are very similar. Some hash algorithms
have been retired as a result of their potential for producing collisions, such
as [SHA-1](https://security.googleblog.com/2017/02/announcing-first-sha1-collision.html).
Hash algorithms are *one-way* in that they are designed in such a way as to
prevent deriving the original input data from a given hash value without a very
significant time and processing-power burden. This is why hashes are used to
store passwords in a user database so if the database is compromised it would
still be a lengthy and expensive process to crack the hashed passwords.

A **Salt** is an additional piece of randomized data that is taken with the data
to be hashed and combined in some way before being put through a hash algorithm.
Salts are generated uniquely for each hashed value. Salted hashes slows
potential attacks by modifying the hash inputs (with the salt values) such that
an attacker would need to know the salt and the method by which it is combined
with the original data in order to produce a value to test against the final
hashed data. The fact that salts are unique to each piece of stored data reduces
an attackers ability to check a given input value against a hash. This increases
the time required to crack a hashed password and has the additional benefit of
protecting weak or common passwords by preventing duplicate passwords in a
database from having same stored hash values.

---

## 7 May 2022

Today I learned about [javascript generator functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*)
while solving a [Codewars](https://www.codewars.com/kata/5d2659626c7aec0022cb8006)
problem. I've been aware of iterators but this is the first time I've ever had
the opportunity to program one myself. I'm excited to have this new and powerful
concept under my belt and in my toolbox for the future.

I also learned about VSCode's [Emmet shortcuts](https://docs.emmet.io/cheat-sheet/)
which will be a great time saver when writing HTML & CSS documents. Emmet was
presented near the beginning of [The Odin Projects's](https://www.theodinproject.com/)
Full-Stack JavaScript path. This is exactly the kind of thing I had hoped
for by following an additional course: Emmet wasn't mentioned at all in the
freeCodeCamp curriculum, yet it will be an incredible boon for me moving forward.

Finally, I advanced through more of the Advanced Node & Express section of the
Quality Assurance Certification unit in freeCodeCamp which involved implementing
basic login and registration flows.

---

## 6 May 2022

Continued on the Advanced Node & Express section of the freeCodeCamp Quality
Assurance unit. I'm excited about this section as it covers user authentication
and building a simple chat app.

Also, I removed Edabit from my profile in the Knowledge log. It turns out that
it isn't free and as it is redundant and lower-quality in both interface and
presented practice problems as compared to Codewars I'll simply stick with
Codewars for now. As it is I haven't made much time to work on either of those
sites as I've been mainly focused on the freeCodeCamp curriculum which is
already on top of running my existing company. This way when I do need a break
from the main curriculum and want to solve some random problems I only need to
go to one place rather than split it up among a couple, which will also all me
to gain better ranks on there more quickly than the alternative.

---

## 5 May 2022

Started the Advanced Node and Express section of the freeCodeCamp Quality
Assurance unit.

---

## 4 May 2022

Completed the first course section of the freeCodeCamp Quality Assurance unit on
[Testing with Chai](https://github.com/mjkjr/fcc-mochachai/tree/main/tests).

---

## 3 May 2022

Today I completed the remainder of the projects for the freeCodeCamp
[Back End Development and APIs Certification](https://www.freecodecamp.org/certification/mjkjr/back-end-development-and-apis)
and began working on the Quality Assurance Certification lessons which cover
unit testing. Simultaneously I've started on the full-stack javascript course at
[The Odin Project](https://www.theodinproject.com/paths/full-stack-javascript);
my hope is that by working through another course I will be able to fill in any
potential blind-spots from the freeCodeCamp material.

---

## 2 May 2022

I completed the [first](https://mjkjr-fcc-timestamp.glitch.me/)
[two](https://mjkjr-fcc-headerparser.glitch.me/) projects toward the
freeCodeCamp.org Back End Development & APIs Certification this morning. I am
pretty excited learning to work with node, my brief experience with it in the
past left me with a negative impression of it, however it was in an unstructured
context where I didn't have the proper groundwork knowledge from which to draw.
I'm looking forward to completing the remainder of the projects and using what
I learn to flesh out the plans for the future back-end of my business' website
and my future CRM/ERP project as well. I will need to think of some of my own
ideas for a few small practice projects to add to my portfolio list as well.

---

## 1 May 2022

Continued working through the Back End Development Certification curriculum on
freeCodeCamp.org. I'm using Glitch.com to host the projects. Despite the
curriculum not covering actually installing node or npm and directing students
to use an online service such as replit.com or glitch which manages node and npm
automatically I decided to figure out how to install node and
[pnpm]((https://pnpm.io/)) on my local ubuntu machine. While I am indeed hosting
the project files on my [Glitch profile](https://glitch.com/@mjkjr84), setting
up the local server allowed me to feel confident that I understand the
underlying workings of these tools.

---

## 30 April 2022

Today I began working on the Back End Development certification on freeCodeCamp.

The first section covers using NPM which is new to me as I've never really
worked with Node (and by extension the Node Package Manager) before (aside from
working briefly on a simple Trello Power Up using node hosted on Glitch.com but
I didn't really know what I was doing then and scrapped the project).

Also, I've started planning a few initial projects for my portfolio. I've added
them to the [Knowledge log](README.md#📓-portfolio-projects) and I will continue
to add project ideas to the table which will serve to help me remember the
projects I want to work on. I also have cards in my personal Trello board with
links to related resources and checklists of the user stories that each project
will require. I'll end up including notes within the comments of the individual
projects themselves with the related planning and resources that went into them.

---

## 29 April 2022

Today I completed the 5th and final project in the freeCodeCamp Data
Visualization certification which was a
[Treemap Graph](https://codepen.io/mjkjr/full/ExQYrBN). I'm looking forward to
moving on to the Back End Development and APIs Certification as I plan to use
what I learn there in building the client portal of my business website.

---

## 25 April 2022

Today I completed the 4th project towards the freeCodeCamp Data Visualization
certification which is a [Choropleth Map](https://codepen.io/mjkjr/full/GRyaLxy)
of an education statistic within the US.

---

## 24 April 2022

I completed the [3rd project](https://codepen.io/mjkjr/full/KKZYLEq) toward the
freeCodeCamp Data Visualization certification which is a heat map visualization.

---

## 23 April 2022

I completed the [2nd project](https://codepen.io/mjkjr/full/qBpwwON) toward the
freeCodeCamp Data Visualization certification and started working on the 3rd.

---

## 22 April 2022

Today I completed the first freeCodeCamp project towards the Data Visualization
certification which was a
[simple bar graph](https://codepen.io/mjkjr/full/JjMzVyJ) using the D3 library.

---

## 21 April 2022

I started thinking about the high-level design of my next project,
[ImprintMint](https://imprintmint.com), which will be an ERP+CRM SaaS tool for
print shops that do custom apparel decoration, signage, vehicle wraps, and small
& large-format printing. I plan to use node and am considering a front-end
framework which is an alternative to React called [Aurelia](https://aurelia.io/)
(which I love because it just so happens to be my eldest daughter's name). I
plan to follow the aurelia "Contact Manager" tutorial to get a better idea of
how it works.

---

## 20 April 2022

Today I started working on the freeCodeCamp Data Visualization certification.

---

## 19 April 2022

Today I completed the final two projects in the freeCodeCamp curriculum toward
the Front-End Development Libraries certification which were a simple
[Javascript calculator](https://codepen.io/mjkjr/full/xxpMVZm), and a
[25+5 clock](https://codepen.io/mjkjr/full/RwxvgrV), earning me the
[certification](https://www.freecodecamp.org/certification/mjkjr/front-end-development-libraries).

---

## 18 April 2022

Today I worked on and finished the next
[freeCodeCamp project](https://codepen.io/mjkjr/full/jOYXGVZ) toward the
Front-End Development Libraries certification, which is a simple "Drum Machine"
app. That leaves only 2 small projects left for this certification, and my goal
will be to finish those both before the end of this week.

I also updated the [Goals](./README.md#🏆-goals) section of the Knowledge Log to
include the goal of converting my existing brick-and-mortar business into an
online-only e-commerce shop. This milestone will serve a dual-purpose: 1. it
will free up my time by automating much of my current workload associated with
running the business while preserving it as an income stream, and 2. it will
serve as an excellent learning experience and portfolio piece.

The current iteration of the website is created using a custom static site
generator which I wrote myself. Written in PHP, it uses a
[NoSQL database](https://github.com/rakibtg/SleekDB) to manage dynamic data, and
outputs a compact static HTML5 website that is designed for speed. It's a work
in progress and I have parts I'd like to improve, specifically the fact that it
uses Bootstrap for CSS which is heavier that necessary for this website's needs.
Currently it uses Git workflows to deploy to a DigitalOcean droplet when a
version-formatted tagged commit is pushed.

---

## 16 April 2022

Today I finished my
[Markdown Previewer project](https://codepen.io/mjkjr/full/gOovJga) as a part of
the freeCodeCamp Front-End Development Libraries certification. The previewer is
built with React as taught in the course and the layout is done with CSS grid
including a media breakpoint to automatically switch from a side-by-side layout
on wider screens to a top-and-bottom layout on more narrow screens. The project
is pretty straight-forward and uses a third-party library for converting the
raw input into html.

---

## 9 April 2022

Today I warmed up by registered an account on
[Edabit](https://edabit.com/user/4QXooTfP97tnnBkHb) and doing some of the
challenge problems there. I added my new Edabit profile to my profile links.
Then I did a few problems on codewars.

I improved the formatting of the tables in the
[skills assessment](./README.md#💻-skills) section of the Knowledge Log.

Finally, I worked through the first 6 levels of JSRobot.

For my next session I want to complete the next freeCodeCamp Front End
Development Libraries project which is a Markdown previewer.

---

## 5 April 2022

Today I spent some time going through
[Skynapse's Resources](https://github.com/Syknapse/resources) and adding to my
curriculum and reference links any that I felt would be personally most useful.

Next time I plan to do the same with the
[Rusty CS course material](https://github.com/AbdesamedBendjeddou/Rusty-CS).

Some resources that stuck out were [Codewars](https://www.codewars.com/),
[Edabit](https://edabit.com/), and [HackerRank](https://www.hackerrank.com/),
all of which I believe will not only be helpful in strengthening my coding
abilities, but will also be great to add to my profile links section. The
progress in these sorts of sites is tracked and works as nice little "badges of
honor". Additionally, this gives a couple of alternative options for work
progress if I have a day where I'm not particularly motivated to work through
the linear coursework (like today).

For now, I've signed up for Codewars and added it along with my other profile
links to the [About Me](./README.md#🧠-about-me) section of this knowledge log.

I also updated my Knowledge Log by adding a [Goals](./README.md#🏆-goals)
section that clearly lays out my goals for this project.

Finally, I added a spell-checking extension to Visual Studio code today.

---

## 2 April 2022

Today I set up this knowledge log repo as a place to organize and collect the
notes of my self-directed studies.

The README.md file contains an overview of my topics of interest, a self-
assessment of my skills, the (incomplete) first rough draft of my curriculum,
and a collection of links for future reference.

My daily routine shall include reviewing the README.md overview and following
the curriculum therein, recording my notes in this log.md file as I progress.
