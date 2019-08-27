Setup files for a new user on the sb-ont. (Including a help file for novice Linux users.)

For complete novice users, to get a good feel for the command line I redirect you
to this introduction to bash: https://www.youtube.com/watch?v=oxuRxtrO2Ag I think
this one is very well done, and is in fact the one that helped me the most
when I was learning.

Now, if you are on Windows, you need a terminal to interact with Linux machine.
A very feature rich on is MobaXTerm: https://mobaxterm.mobatek.net/download.html
This will give you an X11 Server as well to use graphical applications.

You will be send login instructions, but for MobaXTerm to get started you
select "Session --> SSH --> Fill in host --> Prompt for name/password"
and than you are in the login node.

Mac users already have a terminal running bash, but for the X11 Server you need
to install XQuartz: https://www.xquartz.org/

Within the command line you can login using the command `ssh`. (Don't forget to
use the -X flag to have the graphical applications activated.)
