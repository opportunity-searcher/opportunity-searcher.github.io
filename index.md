The basis of this project can be found [here](http://courses.ics.hawaii.edu/ics314s21/morea/final-project/reading-project-company-connector.html)

Repository for [source code](https://github.com/opportunity-searcher/opportunity-searcher)

![ci-badge](https://github.com/opportunity-searcher/opportunity-searcher/actions/workflows/ci.yml/badge.svg)

## Table of Contents

* [The problem](#the-problem)
* [The solution](#the-solution)
* [Overview](#overview)
* [Goals](#goals)
* [Team Members](#team-members)
* [User Guide](#user-guide)
* [Deployment](#deployment)
* [Developer Guide](#developer-guide)
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

## User Guide

This section provides information of interest to users who would like a step-by-step tutorial on how to use this application to its extent.

## Sign up

You will first have to sign up, the following screenshot will show you how the sing-up page looks.
<img src="doc/signup.png">

## Add Profile

You can then add a profile, you will need to click at the "Add Profile" tab on the navbar. You will then need to fill out the following form with your information.
<img src="doc/add-profile.png">

## List Profiles

After adding your new profile, you can then see your profile along with everyone elses!
<img src="doc/list-profiles.png">

## List Companies

Feel free to browse the catalogue of many different and unique companies looking for talented enthusiasts such as yourself to add to their ranks!
<img src="doc/list-companies.png">

## Deployment

The application can be found hosted on the Digital Ocean cloud servers [here](http://104.131.93.174/).\
The landing page will look like the screenshot below.
<img src="doc/landing-page.png">

## Developer Guide

This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation

First, [install Meteor](https://www.meteor.com/install).

Second, visit the [Opportuniter Searcher application github page](https://github.com/opportunity-searcher/opportunity-searcher), and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo.  However you do it, download a copy of the repo to your local computer.

Third, cd into the opportunity-searcher/app directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Application Design

Opportunity Searcher is based upon [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/) and [meteor-example-form-react](https://ics-software-engineering.github.io/meteor-example-form-react/). Please use the videos and documentation at those sites to better acquaint yourself with the basic application design and form processing in Bowfolios.

## Initialization

The [config](https://github.com/bowfolios/bowfolios/tree/master/config) directory is intended to hold settings files.  The repository contains one file: [config/settings.development.json](https://github.com/bowfolios/bowfolios/blob/master/config/settings.development.json).

This file contains default definitions for Profiles and Companies. Consult the walkthrough video for more details.

### Quality Assurance

#### ESLint

Opportunity Searcher includes a [.eslintrc](https://github.com/opportunity-searcher/opportunity-searcher/blob/master/app/.eslintrc) file to define the coding style adhered to in this application. You can invoke ESLint from the command line as follows:

```
meteor npm run lint
```

Here is sample output indicating that no ESLint errors were detected:

```
$ meteor npm run lint

> bowfolios@ lint /Users/philipjohnson/github/bowfolios/bowfolios/app
> eslint --quiet --ext .jsx --ext .js ./imports ./tests

$
```

ESLint should run without generating any errors [Note that at the time of writing, searchpage.jsx has not been fixed yet so an eslint error will pop up].

It's significantly easier to do development with ESLint integrated directly into your IDE (such as IntelliJ).

# Project Progress

The Milestones provide issues about the [application](http://104.131.93.174/) and [github homepage](https://opportunity-searcher.github.io/) being worked on.

## Milestone 1

* [Final Project: Milestone 1](https://github.com/orgs/opportunity-searcher/projects/1)

5 mockup pages are implemented and available to see on Digital Ocean.

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

## Webpages

### Home

The simple home page directs users to use the search function.

<img src="doc/home-m1.png">

### List Companies and Profiles

This page shows a list of all the companies, and also has a similar page for students/regular users.

<img src="doc/companies-m1.png">

Here is the student page:

<img src="doc/students-m1.png">

### Search

The search page is simple. It provides a searchbar for typing in keywords which display both companies and profiles in a unified format.

<img src="doc/search-m1.png">

## Milestone 2
* [Final Project: Milestone 2](https://github.com/orgs/opportunity-searcher/projects/2)

### Add Profile

The add profile page lets all users create a profile of a student looking for an opportunity.

<img src="doc/add-profile.png">

### Add Company

The add company page lets all users create a profile of a company looking for potential hires or candidates.

<img src="doc/add-company.png">

### List Profiles

When logged in as an administrator, the list profiles page includes an edit button for all profiles so that admins may edit any info included with the profile.

<img src="doc/list-profiles.png">

### List Companies

When logged in as an administrator, the list companies page includes an edit button for all companies so that admins may edit any info included with the company.

<img src="doc/list-profiles.png">

### Edit Profile

The edit profile page is only available to admins who have clicked on a specific profile to edit. This page allows admins to change information associated with the profile using a form

<img src="doc/edit-profile.png">
