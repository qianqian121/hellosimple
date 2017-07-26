=====================================================
RTI Connext (formerly, RTI Data Distribution Service)
Hello_simple Example Application
=====================================================

Welcome to Connext.


Compiling this Example
----------------------

Before compiling make sure that the environment variable NDDSHOME is defined
and that it refers to your RTI Connext installation directory.

To build this example on Windows, open the appropriate solution file for your
version of Microsoft Visual Studio in the win32/ directory.

To build this example on a UNIX-based system, type the following in a command
shell:

  > gmake -f make/Makefile.<architecture>


Running this Example
--------------------
To run this example on Windows, type the following in two different command
shells, either on the same machine or on different machines:

  > objs\<architecture>\HelloSubscriber.exe
  > objs\<architecture>\HelloPublisher.exe

To run this example on a UNIX-based system, type the following in two
different command shells, either on the same machine or on different machines:

  > objs/<architecture>/HelloSubscriber
  > objs/<architecture>/HelloPublisher

For more information, please consult your "Getting Started Guide."
