# Skrub.

Skrub is a composer plugin that will remove useless files and free up some space, 
especally useful when keeping Docker images small.

Usage:
`composer skrub` will list the files Skrub feels it can safely remove and the 
total disk space that can be regained.

Adding `--perform` to the command will actually delete the files &amp; 
directories from your system.


### Warranty, Disclaimer etc.

This is a plugin that will perform a deletion command on your system. The 
author is in no way liable for any data loss arising from its use or if it 
deletes unexpected files. Pay attention to the files Skrub lists.   


### Security Issues

If you discover a security issue with Skrub, please email scott@dor.ky and I'll
response as soon as possible.