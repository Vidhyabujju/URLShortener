# URLShortener
 Minify a URL and redirect to Long URL

# Installers
 Python3
 Flask
 Flask-restful

# How to run?
 1. Execute the application with the following command
	$ python restAPI.py
 2. Open index.html file 

# Existing issues
  1. Memory leaks to be handled (since no hosting server locally) 
  2. The statistics page is designed with hard coded values, since XMLHttpRequest does not   allow to read locally saved files to browser. But the logs and profiling files are available.
  3. The profiling output file is disabled for memory issues (since no hosting server locally)
  4. For URLs with arithmetic operators and float values, exception occurs. Need to handle this issue
  5. Redirection for now happen in new window (since no client side framework developed), will be done and delivered as version2 soon
 
