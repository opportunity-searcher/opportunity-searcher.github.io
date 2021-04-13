The basis of this project can be found [here](http://courses.ics.hawaii.edu/ics314s21/morea/final-project/reading-project-company-connector.html)

Repository for [source code](https://github.com/opportunity-searcher/opportunity-searcher)

## Table of Contents

* [The problem](#the-problem)
* [The solution](#the-solution)
* [Overview](#overview)
* [Goals](#goals)
* [Team Members](#team-members)
* [Deployment](#deployment)
* [Project Progress](#project-progress)

## The problem

Many UH computer science and engineering students want to learn about internship and job opportunities, but currently they must wait until a company decides to visit the campus or send out some sort of announcement. There is no efficient way for students to understand the “landscape” of internship and job opportunities that might be available in the future, so they can prepare for them now.

## The solution

The web application provides a new way for local and non-local companies who want to recruit students from UH to make their (potential) opportunities known to students. At the same time, students can create profiles on the site with their interests. The site can match students to employers and vice-versa.

## Overview

Instead of sending out announcements each year, a company can create a page in the site that lists:

- A brief overview of the company.
- Geographic location of the company.
- A list of positions that they commonly recruit for from new UH graduates. Each position has a brief description, a set of skills, whether it’s an internship, permanent position, or both, how many people they would like to hire, and salary range.
- Links to pages for additional information.
- Contact email(s) for followup.

Students who visit the site can create a profile with their interests (skills), preferred geographic location, and link to their professional portfolio page.

## Goals

- Profile page for students and companies
- a way to search by various categories like skill, geographic preference, etc.
- messaging system
- quality UI

## Team Members

- [Matthew Ito](https://github.com/Matt-Ito): UH Manoa student majoring in ICS and minoring in Japanese. Hobbies include video games, anime, and weightlifting.
- [Kegan Flagg](https://github.com/keggit): UH Manoa student who enjoys running as a hobby.
- [Jay Paul Luben](https://github.com/jpluben): UH Manoa student majoring in Computer Science:Security Science with a hobby in Video Games and Anime.

## Deployment

The application can be found hosted on the Digital Ocean cloud servers [here](http://104.131.93.174/)
The landing page will look like the screenshot below.
<img src="doc/landing-page.png">

# Project Progress

* [Final Project: Milestone 1](https://github.com/orgs/opportunity-searcher/projects/1) (In progress)
* [Final Project: Milestone 2](https://github.com/orgs/opportunity-searcher/projects/2) (In progress)

The Milestones provide issues about the [application](http://104.131.93.174/) and [github homepage](https://opportunity-searcher.github.io/) being worked on.

The following sections contain the project's progression of the application in chronological order.

## Mockup Pages

### Home Page

The home page will contain the profile of students looking for work as well as the profiles of companies looking for students. Besides this, it will have a navbar that will show different links based on whether somone is using a student account, company account, or no account at all.
<img src="doc/home.png">

### Profile Page

There will be two different types of profile pages: student profiles and company profiles. Besides the basic information, student profiles contain the type of position they are searching for. Meanwhile, company profiles include information about what kinds of candidates they are looking for.
<img src="doc/profile.png">

### Messaging Page

A Company will put down an email link of a company representative so that students can quickly email the company, students also have an email link so that companies can scout them.
<img src="doc/message.png">

### Search Page

Students and companies can both search using a unified search button. Results are in the form of profiles.
<img src="doc/search.png">
