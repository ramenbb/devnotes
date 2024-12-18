# Best practices for debugging

breakpoint ()

h: help (brings up glossary of commands)
w: where (shows wher eyou are in stack trace)
n: next (next line
s: step (steps into function. this goes to the next function call - that's how it's different than next)
c: continue
p: print. example, if a=0, "p a" will print 0. you can also do p type(a)
l: list (shows you where you are in code, visually)
q: quit
until [line number]: continue until reaching (or skipping over) a specified line number
tbreak [line number]: establishes a breakpoint that is only used once. could be useful in a loop where you only want one breakpoint.

you can put a break point in a loop and it'll stop at that breakpoint each time it goes through the loop. could be helpful if the loop is getting hung up on an error somewhere.

I should try to read error messages carefully and really dissect them for good practice.

If an error message gives you a line number where something wrong happened, could be a good idea to set the breakpoint at that line number.