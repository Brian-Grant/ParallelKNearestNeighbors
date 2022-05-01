# 547-assign02-21
Brian Grant

run make to compile

run make new for a small test

IF you want to run a scaling test

cd in
make new-large-gen         (creates input)
cd ..
./scaling.sh

The output will be in scaling-out.txt


I was able to test up to 8 cores and it scales reasonably well.
I had issues with slurm so I only used remote.cs

I would have liked to see how it scales up to 10, because I could have
tweaked with minor changes to the code.

With regard to the github issue

I never really resolved it.

I accidentally pushed a large test file.
the push failed
Searched the internet for a solution, I tried many different things.
Something I tried changed files to an earlier commit and I lost work.
There were also:

"<<<<<<HEAD"

and other things written throughout the code.

I assume that was a github error and had something to do with errors
during earlier push attempts.

Anyway something was just really wrong, and I lost some work, and spent some
time getting the code back to something working.

I do not think I was able to restore all the local changes I made before 
the disaster but what are you going to do.

I cloned it again, and had to try to restore my work there, and was able to push

While I was trying to fix this issue, no massive changes to the general
structure and idea of my code took place. I just wanted to restore what I had.





There are a lot of other things in this directory

I worked on code to generate tests in parallel,
There are all kinds of different scripts for this
Id like to keep them in here to work on them more in the future

The relevant files to this assignment:

knnClass.cpp
knnClass.hpp
makefile
driver.cpp
scaling.sh   <---dependent on files that need to be regenerated


Thank you for your time.


