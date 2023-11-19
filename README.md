# Project Description
This is a very simple and basic web server built with GO.

## Basic set up
The app is running on port 8080, "localhost:8080"

### Methods
There is 2 of the most basic methods, "GET" & "POST"

### Routes
2 routes : 
- "/" : will get you a web page saying "Simple Web Server"
- "/form.html" : will get you a web page to fill the name and adress and then submit to be redirected to "/form" with those value you've filled.

## Personal Takeaways
I have learnt and used the "net/http" package, the function ListenAndServe to start the application, "http.FileServer()" to serve an html file, and both "http.Handle" , "http.HandleFunc".