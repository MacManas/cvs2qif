# cvs2qif
Convert bank statements in CVS to QIF to be able to use them in other tools.

The CVS format can change from bank to bank, therefore the command line need to provide some kind of pattern matching.
Also, some lines at the beginning and end of the file may be misc data unrelated to the transactions and therefore need to be ignored.
