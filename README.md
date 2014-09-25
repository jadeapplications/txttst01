txttst01
========

Demonstrate how to look for a text (.txt) file, read the file and then update it.

syscall APIs used:
- dir: get the directory information for the file(s).  This returns an empty ("") string.  The "*" and "?" wildcards are allowed.
- dirnext: return the next file from the "dir" command.  This continues until all applicable files have been found, at which point an empty ("") string is returned.  
- fileread: return the contents of the specified text (.txt) file.  No wildcards are allowed.  
- filedelete: delete the specified (.txt) file.  This is required before the file can be written to.  No wildcards are allowed.  
- filewrite: write a string into the specfied (.txt) file.  This file cannot already exist.  No wildcards are allowed.  

### Release History:
2014.09.20 - Initial Release.

### Copyright (c) 2014 Mimetics Inc.
All Rights Reserved

This software is provided by Mimetics "as is" without any expressed or implied warranties.  In no case shall Mimetics or any contributors be liable in any damages caused by the use of this software.  
