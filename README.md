# Basic Python Page Server
## Author Info
Author: Kaleo

Contact: kaleom@uoregon.edu

## Description
This project hosts a webpage server on the port specified in the credentials file. 
It returns pages in the docroot path specified in the credentials file. 
The characters ".." and "~" are considered invalid, and will return http 403. 
A skeleton credentials file "credentials-skel.ini" is included. 


## Research sources used:
For python documentation references: python docs, w3 schools, and geeks for geeks
https://docs.python.org/
https://www.geeksforgeeks.org/
https://www.w3schools.com/python/
These sources were only used to check how certain python functions/language constructs work
For http header format reference:
https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages
To complete the gitignore: git scm docs
https://git-scm.com/docs/gitignore