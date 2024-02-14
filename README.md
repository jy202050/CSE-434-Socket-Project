# CSE-434-Socket-Project

JIAYUAN YU
BAIXI JIAO


Copy from given project zip file
This directory/folder contains two files:

1. UDPEchoClient.c
2. UDPEchoServer.c

You may want to check out the video giving a demo of this code on general.asu.edu.


You may also want to create your own defns.h file containing a structure definition.  Then
I suggest you try to modify the client and server to:
(a) Each of the client and server #include this "defns.h" file.
(b) Have the client initialize the structure, and pass a pointer to it to the server using sendto(),
    writing a number of bytes equal to the sizeof( struct Name-of-Struct ).
(c) Have the server read the structure from the socket using recvfrom(), print the fields in the
    structure and then modify the structure in some way, e.g., increment an integer field.  Send the
    modified structure back to the client using sendto().
(d) Have the client read the structure from the socket using recvfrom(), print the fields in the
    modified structure; iterates ITERATIONS times.