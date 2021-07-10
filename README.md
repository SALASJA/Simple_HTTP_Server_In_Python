# Simple_HTTP_Server_In_Python
it uses pure sockets!
This is not mine but is based on the tutorial in the pdf. I felt like it was necessary to have something like this on github since it is useful for educational purposes. If wanting to associate it with a domain name, SERVER_PORT = 8000, might have to be changed to SERVER_PORT = 80, since port 80 is what is typically used for webservers (but i don't know). just do python3 httpserver.py, then put http://http://localhost:8000 in the browser URL bar. Use this for anything you like, so I'm not putting on a license (since its not mine technically).

there are 5 examples that gets more complex as you go up in number:

- httpserver.py is for setting up the HTTP request
- httpserver2.py takes what we have in httpserver.py and adds code that will allow visiters to see the index.html file (which is editable)
- httpserver3.py takes what we have in httpserver2.py and adds code that will allow one to navigate to different html files (if we have links for example)

- httpserver4.py takes what we have in httpserver3.py and adds code that will return a 404 not found, if html file was not found (one of the links intentionally does not work)

- httpserver5.py works exactly the same as httpserver4.py, but the example uses a python function to make it more modular

note: the favicon.ico file is needed for some reason else it wont work (there is a request for it) so don't erase it, it's basically an image file and there are online sites where you can make one
