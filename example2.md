#Create	a	program	that	asks	the	user	for	the	time	(1-24).
#	Depending	on	what	time	it	is,	print	a	different	phrase.	If	the	time	is
#before	10,	print “ Good	Morning. ”	If	the	time	is	before	19,	print “ Good
#Day. ”	If	the	time	is	after	19,	print “ Good	Night. ”

time=int(input("what is the time?"))
if time<10:
    print "Good morning"
elif time<=19:
    print "Good day"
elif time>19 and time<24:
    print "Good night"

