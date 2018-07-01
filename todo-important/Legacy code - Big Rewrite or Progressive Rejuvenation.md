@ramtop

legacy is
- difficult to maintain, improve, expadn
- but is working and is making money
- sometimes: dont know who is using it

Suggestions:

1. just fix it, quickly. Duct tape approach.
- Law of Broken Windows

2. Rewrite it
- more often or not it doesn't work and is left unfinished.
- data migration is always more painful than expected
- legacy system complexity underestimated, previous kwnoledge would be thrown away and slowly rediscovered
- new features delay the release. 
- new people have no expeirence in the business context.

Progressive Rewrite aka strangler pattern
- reduced risk

code quality
we go it working

graph: time cost vs features
pink line - parabolic up
blue line - bumpy trending up, linear.

code quality: techniques is not quality (tdd/design patterns, functional programming). code coverage is a crazy way to measure code qualty.
what is code quality?
it is the time that it takes to implement a feature.
- how fast is it to fix a bug
- how fast is it to add a feature.

modularity

"Source code Rejuvenation is not Refactoring"

- seal with external tests
- split into modules
- clean the modules
- unit tests
- repeat

but first, simplify the onboarding
then wrap it with end to end tests

github achelmical Rejuvenation