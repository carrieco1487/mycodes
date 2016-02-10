# mycodes
# Define a procedure, countdown, that takes a
# positive whole number as its input, and prints
# out a countdown from that number to 1,
# followed by Blastoff!
# The procedure should not return anything.
# For this question, you just need to call 
# the procedure using the line
# countdown(3)
# instead of print countdown(3).

#EMILY: It prints the # passed in and "Blastoff!" without a countdown. The forum, before it shut down, pointed to the fact that the #Boolean response ends up a False. Something about how after it subtracts 1, anynumber ends up greater than "n". But when I add the #2nd "print n" to test, it displays 3 2 Blastoff! and no 1... which confuses me. I don't see what I am missing! Thanks for offering to #look at it!

def countdown(n):
    anynumber=n
    while anynumber <= n:
        print n
        n = n-1
        print n     
    else:                  
        print "Blastoff!"
      

countdown(3)
#>>> 3
#>>> 2
#>>> 1
#>>> Blastoff!
