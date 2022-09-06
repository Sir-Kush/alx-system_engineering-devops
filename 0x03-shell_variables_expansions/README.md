 Solution to 0x03-shell_variables_expansions proble
SOLUTIONS for 0x03-shell_variables_expansions

Task 0.
alias ls="rm *"
Task 1.
echo "hello $USER"
Task 2.
export PATH=$PATH:/action
Task 3.
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))
Task 4.
printenv
Task 5.
set
Task 6.
BEST="School"
Task 7.
export BEST="School"
Task 8.
echo $(($TRUEKNOWLEDGE + 128))
Task 9.
echo $(($POWER / $DIVIDE))
Task 10.
echo $(($BREATH**$LOVE))
Task 11.
echo $((2#$BINARY))
Task 12.
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"
Task 13.
printf "%.2f" $NUM | sort
Task 14.
printf '%x\n' $DECIMAL
Task 15.
tr `echo {a..z} | tr -d ' '` `echo {n..z} $(echo {a..m}) | tr -d ' '` | tr `echo {A..Z} | tr -d ' '` `echo {N..Z} $(echo {A..M}) | tr -d ' '`
Task 16.
perl -lne 'print if $. % 2 == 1'
Task 17.
echo $(printf %o $(($((5#$(echo $WATER | tr 'water' '01234'))) + $((5#$(echo $STIR | tr 'stir.' '01234'))))) | tr '01234567' 'bestchol')m
