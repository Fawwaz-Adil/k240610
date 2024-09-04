START
INPUT num
IF numMOD2 == 0, jump to step 5
PRINT "Entered number is odd" and jump to step 6
PRINT "Entered number is even"
OUTPUT "Want to enter another number? Y/N"
INPUT ans
IF ans == 'Y', jump to step 2
END
