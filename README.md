
# target-times-scales-covid

<!-- badges: start -->
<!-- badges: end -->

The goal of target-times-scales-covid is to demonstrate the use of renv, targets and friends.

The rmarkdown document is taken from my own blog post:

[Fancy Times and Scales with COVID data](https://www.njtierney.com/post/2020/10/11/times-scales-covid/)

# Using `renv`

1. run `renv::restore()` in the console
2. Knit the "fancy-covid-times.Rmd" document

Making changes to the R libraries?

1. A user installs, or updates, one or more packages in their local project library;

2. That user calls renv::snapshot() to update the renv.lock lockfile;

3. That user then shares the updated version of renv.lock with their collaborators;

4. Other collaborators then call renv::restore() to install the packages specified in the newly-updated lockfile.


# Alternative way 1: Capsule


# Alternative way 2: Capsule + targets



