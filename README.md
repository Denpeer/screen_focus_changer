Forked and adjusted for 3 monitor setup
Behaviour changed to left**most**, right**most** or middle screen.

can be useful to create a shortcut that allows you to switch between monitors / screens


![Image](doc/shortcut.png)

install:

sudo apt install xdotool x11-xserver-utils


usage:

To set focus to left screen pass "left" as arg

python3 ./focus_changer.py left

To set focus to right screen pass "right" as arg

usage python3 ./focus_changer.py right
