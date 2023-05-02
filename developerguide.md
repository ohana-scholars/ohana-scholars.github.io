---
layout: page
title: Developer Guide
subtitle: Here's how you can download, install, run, and modify our application!
---

Install meteor from the [Meteor API Docs](https://docs.meteor.com/install.html) page.

To copy, change, or modify our web application, first go to [the repository](https://github.com/ohana-scholars/ohana-scholars-application), clone ohana-scholars-application by clicking "Code" and choosing "Open with GitHub Desktop", name your new repository, and use the IDE of your choice.

Next, open terminal and navigate to the /app directory and run `meteor npm install` to install the necessary files.

Then run `meteor npm run start` and the webpage should be running at [http://localhost:3000](http://localhost:3000). Your terminal should show the following (small warning: it's a lot!):

```
D:\github\ohana-scholars-application\app>meteor npm run start

> meteor-application-template-react@ start D:\github\ohana-scholars-application\app
> meteor --no-release-check --exclude-archs web.browser.legacy,web.cordova --settings ../config/settings.development.json

[[[[[ ~\D\github\ohana-scholars-application\app ]]]]]

=> Started proxy.
=> Started HMR server.
=> Started MongoDB.
I20230501-23:36:49.883(-10)? Creating the default user(s)
I20230501-23:36:49.900(-10)?   Creating user admin@foo.com.
I20230501-23:36:49.985(-10)?   Creating user fool@foo.com.
I20230501-23:36:50.068(-10)?   Creating user john@foo.com.
I20230501-23:36:50.144(-10)? Adding Courses.
I20230501-23:36:50.144(-10)?   Adding: Introduction to the Visual Arts
I20230501-23:36:50.296(-10)?   Adding: Introduction to Drawing
I20230501-23:36:50.301(-10)?   Adding: Introduction to Hawaiian Art
I20230501-23:36:50.308(-10)?   Adding: Introduction to Electronic Arts
I20230501-23:36:50.313(-10)?   Adding: Introduction to Digital Imaging
I20230501-23:36:50.316(-10)?   Adding: Intermediate Drawing
I20230501-23:36:50.322(-10)?   Adding: Art of Hawaii
I20230501-23:36:50.324(-10)?   Adding: Hawaiian Environmental Science
I20230501-23:36:50.328(-10)?   Adding: Introduction to Biology I
I20230501-23:36:50.330(-10)?   Adding: Introduction to Biology I Lab
I20230501-23:36:50.332(-10)?   Adding: Introduction to Biology II
I20230501-23:36:50.333(-10)?   Adding: Introduction to Biology II Lab
I20230501-23:36:50.335(-10)?   Adding: Biostatistics
I20230501-23:36:50.336(-10)?   Adding: Introduction to Business
I20230501-23:36:50.337(-10)?   Adding: Principles of Marketing
I20230501-23:36:50.339(-10)?   Adding: Business Finance
I20230501-23:36:50.340(-10)?   Adding: Business Statistics
I20230501-23:36:50.345(-10)?   Adding: Marketing Management
I20230501-23:36:50.346(-10)?   Adding: General Chemistry I
I20230501-23:36:50.347(-10)?   Adding: General Chemistry I Lab
I20230501-23:36:50.348(-10)?   Adding: General Chemistry II
I20230501-23:36:50.349(-10)?   Adding: General Chemistry II Lab
I20230501-23:36:50.350(-10)?   Adding: Organic Chemistry I
I20230501-23:36:50.351(-10)?   Adding: Organic Chemistry I Lab
I20230501-23:36:50.352(-10)?   Adding: Physical Chemistry I
I20230501-23:36:50.353(-10)?   Adding: Physical Chemistry I Lab
I20230501-23:36:50.355(-10)?   Adding: Introduction to Economics
I20230501-23:36:50.356(-10)?   Adding: Principles of Microeconomics
I20230501-23:36:50.357(-10)?   Adding: Principles of Macroeconomics
I20230501-23:36:50.361(-10)?   Adding: Data Analysis and Visualization
I20230501-23:36:50.362(-10)?   Adding: The Economy of Hawaii
I20230501-23:36:50.366(-10)?   Adding: Introduction to Statistics
I20230501-23:36:50.368(-10)?   Adding: Composition
I20230501-23:36:50.369(-10)?   Adding: Composition II
I20230501-23:36:50.370(-10)?   Adding: Business Writing
I20230501-23:36:50.371(-10)?   Adding: Technical Writing
I20230501-23:36:50.372(-10)?   Adding: Creative Writing
I20230501-23:36:50.376(-10)?   Adding: World History to 1500
I20230501-23:36:50.377(-10)?   Adding: World History since 1500
I20230501-23:36:50.378(-10)?   Adding: Issues in World History
I20230501-23:36:50.379(-10)?   Adding: Introduction to American History
I20230501-23:36:50.380(-10)?   Adding: History of the Hawaiian Islands
I20230501-23:36:50.381(-10)?   Adding: Topics in History
I20230501-23:36:50.382(-10)?   Adding: Introduction to Computer Science
I20230501-23:36:50.383(-10)?   Adding: Discrete Mathematics for Computer Science
I20230501-23:36:50.384(-10)?   Adding: Introduction to Computer Science II
I20230501-23:36:50.385(-10)?   Adding: Discrete Mathematics for Computer Science II
I20230501-23:36:50.386(-10)?   Adding: Algorithms
I20230501-23:36:50.387(-10)?   Adding: Software Engineering I
I20230501-23:36:50.393(-10)?   Adding: Software Engineering II
I20230501-23:36:50.394(-10)?   Adding: Computer Security and Ethics
I20230501-23:36:50.395(-10)?   Adding: Precalculus: Trigonometry and Analytic Geometry
I20230501-23:36:50.396(-10)?   Adding: Calculus I
I20230501-23:36:50.397(-10)?   Adding: Calculus II
I20230501-23:36:50.399(-10)?   Adding: Calculus III
I20230501-23:36:50.400(-10)?   Adding: Calculus IV
I20230501-23:36:50.401(-10)?   Adding: Introduction to Professional Nursing I
I20230501-23:36:50.402(-10)?   Adding: Introduction to Professional Nursing II
I20230501-23:36:50.403(-10)?   Adding: Professionalism in Nursing
I20230501-23:36:50.407(-10)?   Adding: Health and Illness I
I20230501-23:36:50.408(-10)?   Adding: Health and Illness I Lab
I20230501-23:36:50.409(-10)?   Adding: General Physics I
I20230501-23:36:50.410(-10)?   Adding: General Physics I Lab
I20230501-23:36:50.411(-10)?   Adding: General Physics II
I20230501-23:36:50.412(-10)?   Adding: General Physics II Lab
I20230501-23:36:50.413(-10)?   Adding: General Physics III
I20230501-23:36:50.414(-10)?   Adding: General Physics III Lab
I20230501-23:36:50.415(-10)?   Adding: Quantum Mechanics I
I20230501-23:36:50.416(-10)?   Adding: Advanced Physics Lab
I20230501-23:36:50.418(-10)? Adding Student.
I20230501-23:36:50.418(-10)?   Adding: John Doggo
I20230501-23:36:50.558(-10)?   Adding: Admin Doggo
I20230501-23:36:50.561(-10)?   Adding: April Fools
I20230501-23:36:50.566(-10)? Creating default sessions.
I20230501-23:36:50.566(-10)?   Adding: ICS314 Final Exam Study Group (john@foo.com)
I20230501-23:36:51.288(-10)?   Adding: ICS311 Final Exam Study Group (john@foo.com)
I20230501-23:36:51.295(-10)?   Adding: CHEM162 Exam 3 Study Session (admin@foo.com)
I20230501-23:36:51.297(-10)?   Adding: ICS241 Final Exam Study (admin@foo.com)
I20230501-23:36:51.299(-10)?   Adding: Art Contest (admin@foo.com)
I20230501-23:36:51.301(-10)?   Adding: ICS Hackathon (admin@foo.com)
I20230501-23:36:51.303(-10)?   Adding: ICS314 Final Exam Study Group 2 (admin@foo.com)
I20230501-23:36:51.305(-10)?   Adding: ART213 Idea Brainstorming Session (admin@foo.com)
I20230501-23:36:51.312(-10)?   Adding: BIOL171 Help (admin@foo.com)
I20230501-23:36:51.314(-10)?   Adding: BUS200 Jeopardy Game (admin@foo.com)
I20230501-23:36:51.317(-10)?   Adding: CHEM272 Homework Help (admin@foo.com)
I20230501-23:36:51.318(-10)?   Adding: ECON120 Chapter Review (admin@foo.com)
I20230501-23:36:51.320(-10)?   Adding: ECON321 (admin@foo.com)
I20230501-23:36:51.325(-10)?   Adding: BUS621 Business Stats (admin@foo.com)
I20230501-23:36:51.327(-10)?   Adding: ENG308 Peer Editing (admin@foo.com)
I20230501-23:36:51.328(-10)?   Adding: ENG313 Creative Writing Brainstorming (admin@foo.com)
I20230501-23:36:51.330(-10)?   Adding: HIST284 Review Game (admin@foo.com)
I20230501-23:36:51.332(-10)?   Adding: MATH241 Final Exam Study (admin@foo.com)
I20230501-23:36:51.333(-10)?   Adding: NURS211 Study Sesh (admin@foo.com)
I20230501-23:36:51.336(-10)?   Adding: PHYS480 Study Group (admin@foo.com)
I20230501-23:36:51.346(-10)?   Adding: NURS220 homework help (admin@foo.com)
I20230501-23:36:51.349(-10)?   Adding: ART479 Project Brainstorming (admin@foo.com)
I20230501-23:36:51.351(-10)?   Adding: CHEM161 Final Exam Study Group (admin@foo.com)
I20230501-23:36:51.358(-10)? Adding reputation.
I20230501-23:36:51.359(-10)?   Adding: 9/10 by admin@foo.com
I20230501-23:36:52.017(-10)? => Started jobs queue
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.
```
