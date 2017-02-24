#Scenarios and Use Cases

_Modified from phase 1_.

##Scenario 1

Jenna has never registered for class before. She begins by logging in to the application and choosing
the registration section. Due to her inexperience at UVic, she is unsure what courses she has to take.
She decides to see what the search will do for her, and hits enter on an empty search bar. The search
displays multiple courses, but she is primarily concerned with requirements, and navigates to the wants
to get a list of the suggested required courses for her. She clicks on the 'required' filter, and adds
some suggested required courses to her schedule. During this process she tries to add a course which
conflicts with another course in her schedule already, however, since this is a popular first year course
there is another offering which does not conflict with her schedule which is suggested to her. She
accepts the suggestion. After this suggestion, Jenna notices a course which looks interesting,
but she is not sure if she will want to take it his semester. She askes the system to save it for her in
her schedule without registering for it yet.

##Scenario 2

Paul only has his last few  classes remaining and is not worried at all about getting into them.
He takes his time, building his schedule slowly, setting his earlier start time as 9:30am under the settings.
Since Paul was not able to begin registering until two days after the open-registration date, one of his
courses is already full. When he tries to register, the system informs him that there is no room left in
the course, and suggests that he put himself on the waitlist. Paul accepts the suggestion.
After registering for one more course, Paul decides he does not want to be in the first course anymore.
He views the details of it from the schedule, choosing to drop the course and have it downgraded to a
saved course. After thinking it over, he decides that his decision is final and chooses to delete the
saved course from his schedule altogether.

###Scenario 3

Kelly knows what classes she needs but not what she wants to actually take.
She logs in and checks out the electives tab of the search results. She adds an elective to
her time table and the system tells her that the elective conflicts with a course already on her
schedule. Since there are no other offerings of the course, the system suggests either aborting
or swapping the conflicting course for the elective. Kelly really wants to get into the elective, worried
that such a popular course will be quicker to fill up than the unexciting course it conflicts with.
She opts for the system to automatically drop her from the original course and enroll her in the
new course. The system notifies her of the success, and asks her if she wants to undo the action
or accept. Kelly regrets her decision, and chooses to undo the action.

###Scenario 4

_Modified from phase 1_.

Jenna cannot remember where or when her next class is. She logs in to the application and views
her schedule to get the information.

###Scenario 5

Kelly is registered for courses, and wants to purchase her books. She logs in to the application
and views the book list for her registered courses.


##Use Cases

The following use-cases have been considered -- covered more than the functionality laid out in the
hierarchical task analysis:

- searching for courses
- view textbooks
- view schedule
- add a course
- drop a course
- save a course
- unsave a course
- add a course with a conflict and a suggested alternative
- add a course with a conflict and no suggested alternative
- join waitlist
- update default search criteria
- view required courses only
- view elective courses only
- find similar courses

###Searching for courses

1. The user logs in to the application.
2. The user selects on the course registration option.
3. The system redirects the user to the course search engine.
4. The user submits a search.
5. The system dislay suggested results.

###View textbooks

1. The user logs in to the application.
2. The user selects the textbooks option.
3. The system displays the user's textbooks.

###View schedule

1. The user logs in to the the application.
2. The user selects the view schedule option.
2. The application displays the user's class schedule.

###Add a course

1. The user selects a course from the list.
2. The system displays course details.
3. The user selects to register.
4. The system registers the user.
5. The system adds the course to the user's schedule.

###Drop a course

1. The user selects a course on the schedule.
2. The system displays the course information.
3. The user chooses to drop the course.
4. The system drops the user from the course.
5. The system saves the course in the schedule.
6. The system announces the success of the action.
7. The system requires the user to accept or undo the action.
8. The user accepts the action.

###Save a course

1. The user selects a course on the schedule.
2. The system displays the course information.
3. The user chooses to save the course.
4. The system adds the course to the user's schedule.

###Unsave a course

1. The user selects a saved course on the schedule.
2. The system displays the course information.
3. The user chooses to unsave the course.
4. The system removes the course to the user's schedule.

###Add a course with a conflict and a suggested alternative

1. The user selects a course from the list.
2. The system displays course details.
3. The system displays the conflict on the schedule.
4. The user selects to register.
5. The system warns the user of the conflict and suggestions another offering of the course.
6. The user selects to register in the suggested course
7. The system adds the course to the user's schedule.

###Add a course with a conflict and no suggested alternative

1. The user selects a course from the list.
2. The system displays course details.
3. The system displays the conflict on the schedule.
4. The user selects to register.
5. The system warns the user of the conflict and offers to swap the conflicting courses, or abort.
6. The user selects to drop the swap the courses.
7. The system announces the success of the action.
8. The system requires the user to accept or undo the action.
9. The user accepts the action.

Alternative courses
9. The user selects undo the action.
10. The system undoes the swap.

###Join a waitlist

1. The user selects a course from the list.
2. The system displays course details.
3. The user selects to register.
5. The system warns the user the course is full and suggests going the waitlist.
6. The user selects to join the waitlist.
7. The system adds the user to the waitlist.
8. The system displays the waitlisted course on the schedule.

###Update default search criteria

1. The user selects the settings option.
2. The system display the set of settings options.
3. The user choose search settings.
4. The system displays the search options.
5. The user toggles those settings they desire.

###View required courses only

1. The user selects the required filter in the search results.
2. The system removes all non-required courses from the results.

###View elective courses only

1. The user selects the elective filter in the search results.
2. The system removes all non-elective courses from the results.

###Find similar courses

1. The user selects a course.
2. The system displays the course details.
3. The user selects to view similar courses.
4. The system displays courses similiar to the selected in the results area.
5. The system populates the search bar with the search query that achieved these results.
