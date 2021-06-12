#!/bin/bash
#BEGIN---TEST
#This script displays the date and who's logged on
echo "The time and date are: "
date
echo "Let's see who's logged into the system: "
who
#secret-happiness (I wrote this a month before my Father died.  I was receiving cryptic messages through passphrases,
#trying to catch up with algorithms and hashrates... The more I think about it, the more I miss him,
#The important thing is to remember this life is not for ever, and rethink math problems if they get cryptic in nature #;)
-----------------------------------------------------------------------------------------------------------------------------
# The following day, upon writing this short script I am about to share with you, the output of the script relayed the Birth month 
# and Birth Day of my, now, Late Father.

#!/bin/bash
# copy the /usr/bin directory listing to a log file
today=$(date +%y%m%d)
ls /usr/bin -al > log.$today

# The variable is assigned the output of a formatted date command.  This common technique redirects the output of a directory listing.

$ date +%y%m%d
210612
$

# After running the above command you should see a new file in your directory:

-rw-rw-r--   1 jprill784 jprill784 101934 Jun 12 04:54 log.210612




