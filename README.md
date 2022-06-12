# GPX_add_timestamp
Add timestamp into the GPX file that do not have timestamps at points.

# Purpose:
To automatically produce a hiking using Relive, a website where people can share their hiking, running, or bicycling route, people can upload a GPX file to this website or APP, then it will generate a tour video. Thus, we should have a GPX file containing **continuous** timestamps in the sequencial GPX points.

Although our bureau had a lot of GPX files, these files have been modified for ensuring people's safty. As a result, the timestamps in these fiels were lost.
Instead of typing timestamps hand by hand, I created this python program to add continuous timestamps automatically.
This program save my collegue and I a lot of time. If I did not have this programe, I would spend about 4 hours each GPX.
