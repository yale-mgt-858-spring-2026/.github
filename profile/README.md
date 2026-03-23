# MGT858 - Database Systems, Spring 2026

Hello 👋👋! This is the "about" page for [MGT858 "Database
Systems"](https://858.mba) at the Yale School of Management in Spring 2026.
This is the fourth time I've taught this course. Thanks for joining! 

## Overview

| Key                     | Value                                                                                                                             |
| ----------------------- |-----------------------------------------------------------------------------------------------------------------------------------|
|  🎓&nbsp;Course  number  |  MGT858  |
|  📚&nbsp;Units  |  2  units  in  Yale  College  and  equivalent  elsewhere  |
|  👥&nbsp;Enrollment  |  Open  to  any  student  at  Yale  |
|  📅&nbsp;Term  |  Spring-2  2026  (half-term)  |
|  🕓&nbsp;Meeting  Time  |  Monday &  Wednesday 14:40-16:00  EDT,  March  23  -  May  4,  2026  |
|  💀&nbsp;Final Exam | Monday, May 4th in class |
|  🏫&nbsp;Meeting  Location  |  Room  2410  in  [Evans  Hall](https://map.yale.edu/?id=1910#!m/560094)  |
|  💻&nbsp;Zoom  link  |  No  zoom  🙁  |
|  📅&nbsp;Calendar  |  [Yale  SOM  Academic  Calendar](https://som.yale.edu/programs/mba/integrated-curriculum/the-academic-calendar)  |
|  🩺&nbsp;Excused absence form |  [https://forms.office.com...](https://forms.office.com/pages/responsepage.aspx?id=u76M3Tkh-E20EU4-h6vrXPLVmr3BOOhClWgGsWkBz6NUMUlIVFBaNlY1VTdZUzFGQTRHWkVURzUyTiQlQCN0PWcu&amp;route=shorturl)  |
|  🌐&nbsp;Website  |  http://858.mba   |
|  💬&nbsp;Discussions  |  https://github.com/orgs/yale-mgt-858-spring-2026/discussions (must be GitHub org member) |  
|  👨‍🏫&nbsp;Instructor  |  Kyle  Jensen  |
|  🤝&nbsp;Teaching Assistant | [Max Li](mailto:max.li.yl2847@yale.edu) |


MGT858 introduces students to the database systems used in modern
technology companies.  You will emerge from this course an SQL
champ, well-prepared for tech sector roles including data scientist,
product manager, and technical product manager.  The first half of
the course covers relational databases (after a brief discussion of
content-addressable storage) and the latter half covers other kinds
of systems including key-value stores, document databases (noSQL),
distributed databases, and vector databases.  We will discuss the business
case for each of these database such that you ought to emerge from the
course able to think of a software product or service and describe what
kind of database systems ought to be used to build that product.  You will
not learn how to build such systems, though you will learn a little bit
about their internals. You will definitely learn how these systems can be
used to answer to the kinds of analytics questions you will encounter as
a manager.  The coursework includes *daily* in-class quizzes, several
homework assignments, and a final in-class examination.  The homework
assignments all require writing code and must be submitted using the git
version control system.  (Experience with git is not required; however,
some experience programming is necessary. The particular language does
not matter.) Students can expect to spend perhaps three to four hours
per week on homework.

## Admission to the class

You can be admitted to the class by bidding in the Yale SOM bidding system.
I asked for a big 'ole room this year, so you should get in for "free".
Anybody at Yale can take the class. But, you have to figure out what is 
required by your program. At a minimum, you must [request enrollment from
the SOM registrar](https://som.yale.edu/programs/resources-non-som-students).

## How to use this document/repo

Because our class info and policies are tracked using git, you can
see if and how they change over the course of the semester. Further,
you have the ability to make changes yourself---please send me a pull
request. Similarly, if you feel these documents are lacking, please
open an "[issue](https://github.com/yale-mgt-858-spring-2026/.github/issues)" on
GitHub for this repo and we'll address the issue. Finally, because our
git repo is hosted on GitHub, you can easily receive push notifications
of changes to this repo.  (Woot!)

## Office hours

Your first stop for help should be the [classroom
discussion](https://github.com/orgs/yale-mgt-858-spring-2026/discussions)
on GitHub. Please only email if you need private help. Please, check
with the TA first. (I care greatly about you, but my inbox is often a
hot mess and I'm not always the best at responding to email. 😞)

The office hours for each of the teaching staff is shown
below. Though, if you are reading this before the start of
the semester, it is possible some staff are missing because
they did not yet determine their schedule. 

Feel free to send an email if these times do not work for you.

| Person          | Email | Hours            | Location/URL                                                                |
| --------------- | ----- | ----------- | ----------------------------------------------------------------------- |
| Kyle Jensen     | kyle.jensen@yale.edu | TBD | TBD |
| Max Li | max.li.yl2847@yale.edu | TBD | TBD |


## Development environment

You will need to write a lot of code this semester, mostly
domain-specific query languages like [PostgreSQL-flavored
SQL](https://www.postgresql.org/docs/).  Most of the homework
assignments and the final exam will require using the [git version
control system](https://git-scm.com/) for submission. On the first day
of class you will sign up for GitHub, join the [yale-mgt-858-spring-2026
organization](https://github.com/yale-mgt-858-spring-2026).  You will
submit each of your homework assignments through GitHub using git. Each
homework will begin with some starter code, e.g.  When you complete
your assignments, you'll make git commits and push those commits up to
GitHub so that I can download your answers and test them.  Obviously
this requires knowing a little bit of git. I'll point you to some
git tutorials, but I'm *barely* going to teach git in class. You are
forewarned 😉.

You can complete the homework assignments on any kind of computer:
Windows, Mac, Linux, whatever. You'll almost certainly need to install
some software in order to do so.
That usually starts with choosing
a package manager ([homebrew](https://brew.sh/) on Mac OS and
[Chocolatey](https://chocolatey.org/) on Windows) and choosing a
[good code editor](https://github.com/collections/text-editors). For
most students I recommend [VSCode](https://code.visualstudio.com/),
[Cursor](https://www.cursor.com/), or [Zed](https://zed.dev/).
Alternatively, if you've aspirations to be shell ninja, I recommend
[NeoVim](https://neovim.io/) or [Helix](https://helix-editor.com/).

Obviously you'll need git. You might
also need _clients_ for different database systems. For example,
you will almost certainly need a PostgreSQL client.  The `$XYZ`
_client_ is a piece of software that connects to the `$XYZ` _server_
in order to send the server queries (or other commands) and interpret
the responses. (Here, `$XYZ` is a stand-in for PostgreSQL, Redis,
MongoDB, Clickhouse, Elasticsearch, etc.) Now, it could be that
you don't want to set up the `$XYZ` client software on your
computer, which would be totally reasonable: it can be a pain
in the rear-end. For this reason, you might want to use [GitHub
Codespaces](https://docs.github.com/en/codespaces/overview) for your
assignments. You can find a lot of tutorials for doing that online.
Our GitHub organization gets Codespaces for free, so knock yourself
out!




## Quizzes

Most classes begin with an on-paper, ten-minute multiple choice quiz.
Alas, these are a crude and imperfect assessment of
the degree to which you understand the pre-class reading material.
The following are my reasons for giving pre-class quizzes:

1. It makes you think about the upcoming class!
2. Empirical evidence shows that the [testing effect](https://en.wikipedia.org/wiki/Testing_effect)
   increases your understanding and retention of material.
3. They give you a low-stakes, super-small reward for coming to class prepared.
4. They ensure that your classmates are better prepared for class and therefore more fun to speak with.
5. You can drop your lowest two scores, so they are not stressful.


A few notes about the quizzes...

* The quiz questions are not uniformly drawn from material in
  the pre-class reading. Some pre-class reading will be over-represented
  and some under-represented, usually because of heterogeneous
  importance of the pre-class reading material.
* We want the quiz questions to test your conceptual understanding.
  We do not want to ask "gotcha" questions or simple recall questions.
  However, we will fall short in those aspirations often.
* Some quiz questions will have obvious answers. We do this in part
  to remind you of important concepts.
* If you feel like a quiz question is unfair or that the answer
  is wrong, please tell Kyle. It is easy for Kyle to "fix" a bad
  question.
* Questions that have multiple correct answers are indicated as
  such.

## Using AI

You should use AI for all your homework assignments. Most commercial
models are pretty decent at the Postgres dialect of SQL. They can also
help you if you get stuck with git.

There are at least two free AI resources for you. First, you can get free
access to [GitHub Copilot](https://github.com/features/copilot)
by applying for the [GitHub Student Developer
Pack](https://education.github.com/pack).  You can also use [Yale's
Clarity Platform](https://ai-chat.yale.edu/), which is a thin wrapper
around various frontier models.  Any of these models will
be great at the homework I give you (as long as you prompt
them smartly).


## Preparing for the course

I am receiving a few emails from students about how best to prepare
for the class. There's a few ways to think about doing so. One is to
prepare narrowly for the content you're going to encounter. For SQL,
in my personal opinion, the best way to do so is going through the
exercises at [SQLBolt](https://sqlbolt.com/).  I think that website
is fantastic and it's part of the assigned reading in class. For the
other database systems we'll use, the answer is less clear.  You can
read about [ClickHouse](https://github.com/ClickHouse/ClickHouse) or
[DuckDB](https://duckdb.org/) (the representative columnar stores we might
use); [Redis](https://github.com/redis/redis) (the representative caching
database we might use); [MongoDB](https://github.com/mongodb/mongo)
(the representative noSQL database we'll likely use); and
[Chroma](https://www.trychroma.com/home) (the representative vector
database we will use).

A second way to prepare is to level-up your computer skills in general,
particularly your *nix skills. A good resource for doing so is [MIT's
missing semester course](https://missing.csail.mit.edu/). You should
know how to use your terminal, no matter your operating system.

Also 😜, you'll want to be familiar with
[git](https://git-scm.com/). You can find [many tutorials
online](https://medium.com/@javinpaul/top-10-free-courses-to-learn-git-and-github-best-of-lot-967aa314ea).
Your use of git this semester will be super simple because you
won't generally have collaborators. If you like, you can use a [git
GUI](https://git-scm.com/downloads/guis).  I use GitHub Desktop often,
mostly for line-by-line staging of changes.


## Textbook

There is no textbook for the course. Readings will be posted on the
[class website](https://858.mba).

## Inclusion

This class will be an inclusive environment. If you see behavior that
you feel is discriminatory, abusive, or unprofessional, _particularly_
from the professor or teaching staff, we encourage you to avail yourself
of one or more of the following resources.

- [Preventing and Responding to Sexual Misconduct at Yale Booklet](https://smr.yale.edu/sites/default/files/files/Guide-Preventing-and-Responding-to-Sexual-Misconduct.pdf)
- [Yale
  Sexual Harassment and Assault Response & Education (SHARE)](https://sharecenter.yale.edu/)
- Diane Temple in SOM Human Resources and Sheri Scully in the SOM AASL.
- [Yale Title IX Coordinators](https://provost.yale.edu/title-ix/coordinators) (SOM's Title IX Coordinator is Rebecca Udler)
- [Yale's Live Safe App](https://your.yale.edu/community/public-safety/campus-safety-services/livesafe-app)
- [Office for Equal Opportunity Programs](https://equalopportunity.yale.edu/)


## Grading

Grading will follow the official Yale SOM grading
policy, which is as follows.

| Grade | Description                                                                 | Reported on Transcript |
|-------|-----------------------------------------------------------------------------|------------------------|
| HH    | High Honors. Up to top 10% of class.                                        | Yes                    |
| H     | Honors. Next 25%.                                                           | Yes                    |
| PR    | Proficient. Next 55%.                                                       | No                     |
| P     | Pass. Lowest 10% in core courses; guideline of 5% in electives.             | No                     |
| F     | Fail. An absolute standard; no minimum requirement.                         | Yes                    |


In my opinion, it's a quite generous
curve (though [the ethics of grading on a curve are
dubious](https://digitalcommons.law.byu.edu/cgi/viewcontent.cgi?httpsredir=1&article=1153&context=elj)).
I will compute the grades for non-SOM students by overlaying their
school's grading scale on top of the SOM curve. There's not a 1-to-1
correspondence.  Your letter grade will be based on your sum grade
and your sum grade will be determined _roughly_ as follows (I reserve
the right to make changes. The most common change I make is dropping
assignments or quizzes.)


| Component       | Percentage            | 
| --------------- | ---------------- |
| Homework     | 30% | 
| Quizzes   | 30% | 
| Final exam   | 30% | 
| Participation   | 10% | 

The ethics of counting participation in the grade are also a bit dubious 🙁.
But, I'm including it for consequentialist reasons: your participation makes
the class more fun for all of us and most importantly for me 🤣.
