# How to build webapps

Get familiarized with HTML and CSS. Most people don't directly do CSS, they used some kind of "wrapper" like Bootstrap that makes it easier, but you still need to know how CSS works.

Python is there to add python functionality

Then you choose a web framework. Flask is quite simple to learn, and it's modular, so you can learn it in bits. Look at Corey Schaffer (?) tutorial.

**ALWAYS READ THE DOCUMENTATION**

Another big difference between web apps apps and desktop apps, is that web apps are stateless while desktop apps are stateful. A web app is inherently one with no state, **meaning each request to the server is handled as if it is completely separate from all others,** and you have to provide some extra info (through a cookie for instance) that identify the user so that the server knows how to connect their requests together into one context. You don't have that in a desktop app. You are always working with the same state. The same user. It makes a lot of things easier.