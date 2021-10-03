# Maxim Stepanov
## This repo is a clone of the https://github.com/nelaturuk/education_pathways repository

# Feedback on the CARTE Education Pathways system

## Functional
The most glaring issue with the functionality of the system is the almost arbitrary decision to block/filter the results of the search by the course year.
 I was truly baffled when the initial search for “engineering” presented me with a list of less than ten courses, mostly belonging to the Faculty of Music – the liming factor was the ‘course year’ being set to zero.
 There is no option to set the system to display courses matching all the ‘course year’ entries. Many students, including myself, have frequently mixed up the year-designated and the year-taken for the courses we have taken. The necessity to keep switching between the ‘course year’ selection makes it challenging to actually compare the courses offered.

I would suggest at the very least augmenting the system with the ability to display all the courses matching all the ‘course year’ entries.


## Non-functional
Optimization of a software product for usability in no way, shape, or form implies robbing the user interface of any semblance of aesthetics, and/or design.
 Interface feels glued to the borders of the screen, static, and lacking any logical optimization for end user experience.
 Table entries are unaligned, column names are offset and unjustified in relation to the entries, and the utter lack of colour-coding and contextual design cues renders the experience unnecessarily unintuitive. 

 At the very least using aligned justification for the tables, and using dynamic search bars would have somewhat improved the currently abysmal user experience. 
 Furthermore, colour-coding different elements; altering the background colours of the results list with subtle shades aiding visual grouping of the entries; and selection highlighting would all improve the end user experience and would have added to the usability of the application. 

# Screenshots of the four activities

![activity1Proof](https://github.com/maxsteep/ECE444-F2021-Lab3/blob/main/Activity1.png?raw=true)

![activity2Proof](https://github.com/maxsteep/ECE444-F2021-Lab3/blob/main/Activity2.png?raw=true)

![activity3Proof](https://github.com/maxsteep/ECE444-F2021-Lab3/blob/main/Activity3.png?raw=true)

![activity4Proof](https://github.com/maxsteep/ECE444-F2021-Lab3/blob/main/Activity4.png?raw=true)

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
