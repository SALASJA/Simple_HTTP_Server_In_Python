# VERYSMALLSimple_HTTP_Server_In_Python
it uses pure sockets!
This is not mine but is based on the tutorial in the pdf. I felt like it was necessary to have something like this on github since it is useful for educational purposes. If wanting to associate it with a domain name, SERVER_PORT = 8000, might have to be changed to SERVER_PORT = 80, since port 80 is what is typically used for webservers (but i don't know). just do python3 httpserver.py, then put http://http://localhost:8000 in the browser URL bar. Use this for anything you like, so I'm not putting on a license (since its not mine technically).

there are 5 examples that gets more complex as you go up in number:

- httpserver.py is for setting up the HTTP request
- httpserver2.py takes what we have in httpserver.py and adds code that will allow visiters to see the index.html file (which is editable)
- httpserver3.py takes what we have in httpserver2.py and adds code that will allow one to navigate to different html files (if we have links for example)

- httpserver4.py takes what we have in httpserver3.py and adds code that will return a 404 not found, if html file was not found (one of the links intentionally does not work)

- httpserver5.py works exactly the same as httpserver4.py, but the example uses a python function to make it more modular

note: the favicon.ico file is needed for some reason else it wont work (there is a request for it) so don't erase it, it literally has only 2-bytes of data in it (using online generated favicons might make the code crash); but these examples are confirmed to work on macOS 10.12.1 (and Im pretty sure it will work on other operating systems).

- 00000000: 300a                                     0. <-- hex dump of favicon.ico using xxd


my python version is Python 3.6.5 (but it should work with later versions)
Google Chrome Version 91.0.4472.114 (Official Build) (x86_64) (but should work with similar versions of chrome earlier and later)
