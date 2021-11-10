# Quiz #1 : Assessment and Planning 

### Date: November 10, 2021
### In Class/Lab Quiz:
### Due:
* Morning Class:  11:45
* Afternoon Class: 5:45


---
## Name: Edgar Aguilar                                  <!-- answer -->


1. A URL is comprised of a number of components.  Consider the following URL:

  ``one://two:three@four.five.size:seven/eight/nine/ten?eleven=twelve&thirteen=fourteen#fifteen``

  * Provide both the name and value of each component.
    1. "one" - scheme                                   <!-- answer -->
    1. "two" -                                    <!-- answer -->
    1. "three" -                        <!-- answer -->
    1. "four" -                         <!-- answer -->
    1. "five" -                           <!-- answer -->
    1. "six" -                      <!-- answer -->
    1. "seven" -                    <!-- answer -->
    1. "eight" -                  <!-- answer -->
    1. "nine" -                 <!-- answer -->
    1. "ten" -                <!-- answer -->
    1. "eleven" -               <!-- answer -->
    1. "twelve" -               <!-- answer -->
    1. "thirteen" -               <!-- answer -->
    1. "fourteen" -               <!-- answer -->
    1. "fifteen" -                                       <!-- answer -->
    <!-- Add more lines as needed -->

1. In the following code block, provide the git instructions necessary to add a new file to the remote repository: git@github.com:org/project.git (You should presume that you don't have a copy of this repository on your local computer.)
   ```
  git clone git@github.com:org/project.git .
  touch newfile
  git add .
  git commmit -m "adding new file"
  git push                                                      
  <!-- answer -->
   ```
   <!-- You many add any number of lines in the above code block that you need. -->

1. Provide the Apache Directive used to perform the requested action
   1. Position the location of root location of the website at:  /var/www/html
     *                                                  <!-- answer -->
   1. To disable the user "steve" from having a web presence on your server.
     *                                                  <!-- answer -->
   1. To create an alias between the URI: /marketing and the file: /user/marketing/www
     *                                                  <!-- answer -->
   1. To define the location of the error log to be: /var/log/apps/apache/error.log
     *                                                  <!-- answer -->


1. What is the command used to create the user "steve" within your apache container?
    *                                                  <!-- answer -->


1. What does the "AllowOverride" Directive do?
    *                                                  <!-- answer -->


1. Given the following command, provide the corresponding HTTP Request Header:
    * curl  https://www.csun.edu/~steve/roster/input/value/input/value
    ```
                                                      <!-- answer -->
    ```                                                      
    <!-- You many add any number of lines in the above code block that you need. -->

1. The CGI standard defines a number of environment variables that are provided to a CGI program.  Identify and explain the purpose of 6 of these environment variables.
   1. QUERY_STRING:  the part of URL after ? character.             <!-- answer -->
   1.                                                               <!-- answer -->
   1.                                                               <!-- answer -->
   1.                                                               <!-- answer -->
   1.                                                               <!-- answer -->
   1.                                                               <!-- answer -->


 1. Consider the following URL and regular expression used to process this string:
    * URL:   ``http://www.fake.org/marking/john.smith/code=10325/app/input``
    * regexp: ``"^marketing/([a-z]*.[a-z]*)/(code=[0-9]{4,6})/(.*)$"``

    Define the value of each of the following back references
    1. $1:                                                           <!-- answer -->
    1. $2:                                                           <!-- answer -->
    1. $3:                                                           <!-- answer -->
    1. $4:                                                           <!-- answer -->

1. There are a number of different types of files.  Each of these file types can be identified by a single character in the output of the command ``ls -l``.  What are these types of files:
   1. -: a regular file
   1. p: pipe                                                         <!-- answer -->
   1. l: symbolic link                                                         <!-- answer -->
   1. d: directory                                                         <!-- answer -->
   1. b: block file                                                        <!-- answer -->
   1. c: character file                                                         <!-- answer -->
   1. s: socket                                                        <!-- answer -->

1. Describe each of the following:
  - process:                                                      <!-- answer -->
  - environment:                                                  <!-- answer -->
  - stdin:                                                        <!-- answer -->
  - $?:                                                           <!-- answer -->
 
