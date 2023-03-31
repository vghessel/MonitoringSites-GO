# Monitoring and Logging with Golang

### Steps
* Put the websites that will be monitored in the "sites.txt" file.
* You can change the "monitoring" and "delay" constants:
    *monitoring* - How often will you monitor the site sequence
    *delay* - How long will the application wait to run again
* Run application!

### How it works?
The application will check through a GET if the Status will be 200, showing that the site is online.

If any other Status Code returns, it will show that it is offline and the error and status will be printed in the terminal.

You can run the application directly from the source code, or if you are using Linux just run the "hello" file.
