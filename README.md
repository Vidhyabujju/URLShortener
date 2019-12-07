# URLShortener
 Minify a URL and redirect to Long URL

# Installers
 Python3
 Flask
 Flask-restful

# How to run?
 1. Execute the application with the following command
	$ python restAPI.py
 2. In a new command window, execute the following command to see the application
        $ curl http://127.0.0.1:5000

# Existing issues
  1. Memory leaks to be handled (since no hosting server locally) 
  2. The statistics page is designed with hard coded values, since XMLHttpRequest does not   allow to read locally saved files to browser. But the logs and profiling files are available.
  3. The profiling output file is disabled for memory issues (since no hosting server locally)
 
