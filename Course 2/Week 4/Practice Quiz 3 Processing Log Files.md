**Processing Log Files**



###**Question 1**###

syslog=sys.argv[1]

###**Question 2**###

Dictionary

###**Question 3**###

Continue

###**Question 4**###

r"IP \((\d+)\)$"

###**Question 5**###

You should parse log files line by line.
It is efficient to ignore lines that don't contain the information we need.
We have to open() the log files first.
