# Week 1 Review

We'll review topics from week one by preparing a text data set for a 
classification task.
The [20 Newsgroups dataset](http://qwone.com/~jason/20Newsgroups/) is a
collection of 20,000 forum posts belonging to 20 different forum topics.
We'll look at posts from four topics - Atheism, Religion, Computer Graphics, and
Space - and try to assign them to the correct topic using only the text in the
post.
For example, given the post

```
The sightings were apparently spurious.  There is no planet inside of
the orbit of Mercury.

The idea of Vulcan came from the differences between Mercury's observed
perihelion precession and the value it should have had according to
Newtonian physics.  Leverrier made an extensive set of observations
and calculations during the mid 19th century, and Simon Newcombe later
improved on the observations and re-calculated using Leverrier's system
of equations.  Now Leverrier was one of the co-discoverers of Neptune
and since he had predicted its existence based on anomalies in the orbit
of Uranus his inclination was to believe the same sort of thing was
afoot with Mercury.

.
.
.
```

we would want to predict that it has the highest probability of being in Space.