#Modifications to Phase 1

The document which this document is based upon has several flaws. As such, some modifications and
assumptions were necessary to completed this document.

###Textbook exchange

The original document mentions the application having a textbook exchange; however, under the
listing of the key features of the application the original document makes no note of
a textbook exchange. Taking this into consideration, alongside the already-significant scope
or designing a user interface for a course search, registration, schedule viewer, and textbook
lising application, the textbook exchange was removed from further consideration and is not
included in this design document.

This results in the exclusion of the scenario of using the textbook exchange.

###User profiles

The fourth user profile, Zaphod BeebleBrox, is not included in this design document. In addition to being,
in our opinion, written as a joke, this user profile primarily provides detailed information about
how the user arrived on Earth and is not generalizable.

###User requirements

The original document included both user-experience goals and usability goals under user requirements.
However, no template was used for these requirements. Additionally, none of the requirements make
mention of any of the user-experience or usability goals as they were discussed in class and examined
in the textbook. As a result, wach user requirement was examined and adapted; some were found to be
functional requirements rather than design requirements (these were dropped form this document),
others were broken out into multiple user-experience and usability goals that when taken together
could arguably satisfy the user requirement as written, others still were simple dropped from
consideration after being found to be applied to the user of the application rather than on the application
itself.


#####Clear, concise functionality of the class registration system

This requirement was broken out into focuses on:

- learnability
- feedback
- percieved affordances
- consistency

to satisfy the notion of 'clear', and:

- efficiency

to satisfy the notion of 'concise'.

#####Mobile version of the site robust enough to do everything (or most things) the main version can

This requirement was dropped from consideration. A mobile design is here considered to be an
entirely separate design process, requiring an entirely new design document. Additionally,
the problems which inspire this requirement, as mentioned in the original document, are actually
anti-features; the inability of mobile users to zoom the website to fit there screen. No including
this anti-feature is viewed as sufficient for making the site comply with this requirement without
introducing an entire sub-project.

#####Modern, user friendly redesign of the UVic registration pages

No design requirements were adapted from the term 'modern' as it is too general to extrapolate from
without significant experience in the field.

To satisfy the notion of 'user friendly', this requirement was broken out into focuses on:
- percieved affordances
- consistency
- learnability
- memorability
- utility
- safety

It is noted that these overlap with those extracted from the notion of 'clear'; we argue that an
application which is clear for the user is as a result user friendly if it also is of high utility
and ensures safety features are in place for users.

#####Intelligent course selection system based on suggestions

This requirement was dropped for consideration after being determined to be a technical functional
requirement rather than an interface design requirement.

#####Database should be able to recommend courses based on degree and be able to check with a student’s transcript for past courses

This requirement was dropped for the same reason as that of the above.

#####Visual based class search and registration system to allow easier registration for non-english speakers.

This requirement was dropped from consideration as the features of the application require text-based input,
and it is not possible to verify if there is enough emphasis on non-textual elements to be considered
visually based. Additionally, preferring visual cues to transfer information whenever it is of benefit to the
users is considered to be covered by _utility_ and _perceived affordances_.

#####A K-12 education

This requirement was dropped due to the fact that it is a requirement of the user and not a requirement of the
system.
