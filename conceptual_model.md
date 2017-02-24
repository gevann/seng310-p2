#Conceptual Model

The application, based on [this original design document](https://grahamcmacdonald.wixsite.com/seng310b01p5phase1),
is designed to be first and foremost a tool for class registration at the University of Victoria (UVIC), with
secondary functions of displaying the student's class schedule as well as listing the textbooks required or
suggested for each course the student is registered in. An ancillary usage of the application is a course search,
which is integrated directly into the registration system as a necessary first step.

For the primary function of course registration, the application takes as input a user-generated string, such
as 'first year after 10am', and displays an ordered series of suggested courses to match the given criteria.
The suggested courses are shown alongside the user's current class schedule. A detailed view of the course
listing is provided to the user should they select any course, at the same time the course being inspected
is superimposed upon the user's current schedule at the appropriate time. From the course-details the user
can save the course for later (which places the course in the user's schedule but does not register the user
in the course), or register for the course. This primary feature of the application is designed to fit the
conversing-style conceptual model of the search engine; the search bar acts as user input as in most other
search engines, while the courses are displayed in a list ordered by best-fit, in the same manner as the
common search engine's output. Additionally, the results list is designed to fit the exploring and browsing
style conceptual model just as online search-engine websites are. This is done in order to provide a set
of perceived affordances (learned conventions) to the user - those which they employ to use internet search
engines - which in turn is designed to increase both the learnability and memorability of the application.

The schedule-viewer secondary function is designed with the conceptual model of a physical calendar. It
represents days as the columns of a grid, times as the rows. Entries in the schedule are two-dimensional
squares blocking out the grid-pattern of the calendar with an outlined shape, background colour, and label,
making use of the concept model of a paper note placed upon a physical calendar. Both of these models fall
into the browsing style of concept models. While the schedule displayed alongside the search results is
similar to the one previously described, it is nevertheless a manipulating-style conceptual model, owing
to the fact that the user can interact with the items displayed on the schedule via direct manipulation.

The final usage of the application - displaying the relevant textbooks given the user's registered
courses - follows the conceptual model of the list. Each entry of the list represents a single textbook.
The attributes of each entry include the book title, author's list, the status of book regarding it's
usage in the course (whether it is mandatory or suggested), the title of the course it is used in, and
the name of the professor teaching said course. Users are able to get an additionally detailed
view of the book by selecting its entry in the list. This detailed view has the additional
attributes of an image of the book's cover, any subtitles of the book, the location of the book
in the bookstore, and the availability of used copies in the bookstore. None of this information
can be changed through this view, as such, the concept model here falls under the category of exploration
and browsing, rather than direct manipulation.
