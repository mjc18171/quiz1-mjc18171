# Quiz #1 : Assessment and Planning 

### Date: November 10, 2021
### In Class/Lab Quiz:
### Due:
* Morning Class:  11:45
* Afternoon Class: 5:45


---
## Name: Martin Clemente  <!-- answer -->


1. A URL is comprised of a number of components.  Consider the following URL:

  ``one://two:three@four.five.size:seven/eight/nine/ten?eleven=twelve&thirteen=fourteen#fifteen``

  * Provide both the name and value of each component.
    1. scheme:                        'one://'                            <!-- answer -->
    1. authority:                     'two'                               <!-- answer -->
    1. separator:                     ':'                                 <!-- answer -->
    1. password:                      'three'                             <!-- answer -->
    1. separator:                     '@'                                 <!-- answer -->
    1. subdomain:                     'four'                              <!-- answer -->
    1. domain:                        'five'                              <!-- answer -->
    1. top level domain:              'size'                              <!-- answer -->
    1. port number:                   'seven'                             <!-- answer -->
    1. path:                          '/eight/nine/ten'                   <!-- answer -->
    1. query string seperator:        '?'                                 <!-- answer -->
    1. query string:                  '?eleven=twelve&thirteen=fourteen'  <!-- answer -->
    1. fragment:                      '#fifteen'                          <!-- answer -->
    <!-- Add more lines as needed -->

1. In the following code block, provide the git instructions necessary to add a new file to the remote repository: git@github.com:org/project.git (You should presume that you don't have a copy of this repository on your local computer.)
   ```
    $cd /home #example of where you want the repo to be at
    $git clone git@github.com:org/project.git  
    $cp /(source)/newfile /home/project/newfile
    $git status
    $git add (newfile)       
    $git status
    $git commit -m "some message"
    $git status
    $git push                                         <!-- answer -->
   ```
   <!-- You many add any number of lines in the above code block that you need. -->

1. Provide the Apache Directive used to perform the requested action
   1. Position the location of root location of the website at:  /var/www/html
     * DocumentRoot /var/www/html                                          <!-- answer -->
   1. To disable the user "steve" from having a web presence on your server.
     * UserDir disabled steve                                                <!-- answer -->
   1. To create an alias between the URI: /marketing lsand the file: /user/marketing/www
     * Alias "/marketing" "/user/marketing/www"                                                 <!-- answer -->
   1. To define the location of the error log to be: /var/log/apps/apache/error.log
     *  ErrorLog "/var/log/apps/apache/error.log"                                                <!-- answer -->


1. What is the command used to create the user "steve" within your apache container?
    * sudo useradd -m steve                                                 <!-- answer -->


1. What does the "AllowOverride" Directive do?
    *  It basically allows the use of a .htaccess file and overrides the global apache configuration.                                                <!-- answer -->


1. Given the following command, provide the corresponding HTTP Request Header:
    * curl  https://www.csun.edu/~steve/roster/input/value/input/value
    ```
    Content-Type
    Content-Language
    language
    robots
    version
    author
    company
    copyright
    cache-control
    expires                                                 <!-- answer -->
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
    1. $1: http://www.fake.org/marking                                                           <!-- answer -->
    1. $2: /john.smith                                                      <!-- answer -->
    1. $3: /code=10325                                                          <!-- answer -->
    1. $4: /app/input                                                          <!-- answer -->

1. There are a number of different types of files.  Each of these file types can be identified by a single character in the output of the command ``ls -l``.  What are these types of files:
   1. -: a regular file
   1. p: FIFO                                                         <!-- answer -->
   1. l: Symbolic link                                                         <!-- answer -->
   1. d: directory                                                         <!-- answer -->
   1. b: block                                                         <!-- answer -->
   1. c: character                                                         <!-- answer -->
   1. s: socket                                                        <!-- answer -->

1. Describe each of the following:
  - process: a running program                                                      <!-- answer -->
  - environment: variables that are set either by you or are already defiend                                                <!-- answer -->
  - stdin: standard input stream,                                                     <!-- answer -->
  - $?: variable that stores the exit status of a command                                                          <!-- answer -->
 
