#Data Required

The application has multiple sources of necessary data. These include:

- all courses offered at UVIC
- user transcripts
- user course of study
- all course requirements, in full, for each course of study offered by UVIC
- and user given search queries

##Courses offered at UVIC

The application's primary function is provide UVIC students a means of finding and registering for courses
at the university. In order to achieve this goal, the application requires the set of all courses being
offered by UVIC for the next term eligible for registration, at the least. Without this data it is
impossible for the application to present available courses to the student.

##User transcripts, course of study, and the program requirements for each course of study at UVIC

The application makes use of the user's transcripts in order to suggest courses. In addition to this,
the application makes use of the detailed requirements for each course of study provided by UVIC.
These two sets of data are necessary for the application in order for it to provide suggested courses
to the users, such as suggesting a course which is required in the course of study - a detail that
comes from the set of all program requirements at uvic - yet which the user has not already taken and
has the necessary prerequisites for - a detail which comes from the user's transcripts and course
of study.

##User provided search input

The application is primarily geared towards enabling the user to quickly find (and register for)
courses relevant to them. This goal necessitates the need for user input; the user provides additional
criteria for the application to use to suggest courses, such as a faculty they wish to take a course
in, a year, or a time of day for the course to begin after. Without user input, the application
would degrade from a search engine to a list.
