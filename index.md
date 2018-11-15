<img src="assets/logo.png" alt="logo" width="300"/>

# UHM Hotfix

UHM Hotfix is a web application that allows students to report suggestions or problems they find on campus in ten seconds or less. 

## Introduction

University of Hawaiʻi at Manoa is <b>our</b> campus. We all deserve a campus that is safe, clean, and beautiful. With UHM Hotfix, students make suggestions and report problems found on campus near-instantly using their laptops or smartphones. UHM Hotfix will encourage and empower students to take an active approach to improving our campus, so that we all can have a more enjoyable college experience.

![init-mockup](assets/uhm_hf_home.png)


## Features

<ul>
 <li> Lightning fast, simple to use interface.</li>
 <li> Students are able to login using their uh username</li>
 <li> Use of geolocation to automatically identify the location of the issue.</li>
 <li> issues are organized by status of completion and degree of importance.</li>
 <li> A Real-time feed of new  problems and suggestions.</li>
 <li> An fully featured Admin interface to manage problems and suggestions.</li>
</ul>

## Tech and Frameworks Used

UHM Hotfix uses the Meteor full stack web framework, The React library, Semantic UI, and MongoDB.

## Developer Guide
UHM Hofix is a open-source! To downlooad, install, and run this application locally on your machine, please follow the steps below:

Please ensure you have these prerequisites on your machine:
* <a href="https://nodejs.org/en/download/">NodeJS</a>
* <a href="https://www.meteor.com/install">Meteor</a>

To download the application, please navigate to a directory where you would like to download the files, and run the following command:

Download using HTTPS:
```git clone https://github.com/uhm-hotfix/uhm-hotfix.git```

Download using SSH: 
```git clone git@github.com:uhm-hotfix/uhm-hotfix.git```

Once you have the files download, navigate into the uhm-hotfix directory and run ```npm install```.

After that, please run ```npm start```, and the application should be running on your localhost!

## About the Team

<B> Kenneth Lauritzen </B>

Kenneth is a senior pursuing a bachelor's degree in computer engineering at UH Manoa. He begain his college education with an interest in electronic hardware, but is now has a bigger interest in computer software and computer science. His interests include machine learning, low-level programming, and computer architecture.

<B> Nicolas Lum </B>

Nicolas is a computer science major at UH manoa. His interest in coding was sparked by computer games, specifically Starcraft 2. His curiosity shifted from game developement to software engineering, which has it's own interesting set of challenges. He has experience in HTML/CSS, JS, C, C++, SQL, Python, Java, and Swift.

<B> Will Post </B>

Will is a Kapiolani Community College transfer student and computer science major at UH Manoa. His interest in mathmatics led him to discover the joys of Computer Science via a research project involving data science. His interests include software developement, low-level programming, integrated systems, and data science. He has experience in C, C++, Python, Java, HTML and CSS, JS, Linux, and SQL.


# Next Steps

The team will first focus on both creating the static web pages that will make up the site, and designing and implementing the database schema. Once this is completed, we will integrate the database with the static user interface. Finally, we will add the finishing touches by implementing the use of geolocation using the google maps api, and creating the new issue stream.
