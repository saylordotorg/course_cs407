---
layout: default
title: "CS407: Network Applications Development"
course_description: "An exploration of the design and implementation of network-based applications, focusing on object-oriented programming and programming techniques, both at the application layer and the transport layer of the TCP/IP protocol stack."
next: ../Unit06
previous: ../Unit04
---
**Unit 5: Text Transport Using UCP and TCP** <span id="5"></span> 
*This unit will introduce you to new programming skills – more
specifically, programming skills on the transport layer of the TCP/IP
stack.  This unit will begin by providing you with a layered view of the
Internet, focusing on the UDP and TCP protocols in the TCP/IP stack.  We
will then learn how text can be sent over the network and identify the
principles of creating UDP datagrams or TCP segments, packaging text,
and transferring it from one machine to another across the network.*

**Unit 5 Time Advisory**  
This unit should take you approximately 10 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.1: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.2: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.3: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 5.4: 1 hour

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Explain the fundamental concepts of programming for the transport
    layer.
-   Differentiate the coding methods for writing and reading across
    machines.
-   Compare and contrast methods for input and output streaming.
-   Complete programming tasks utilizing different streaming methods.

**5.1 Internet Basics** <span id="5.1"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 11.4: Networking”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 11.4:
    Networking”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of Section 11.4, which provides an
    overview of networking.  Programming for client-server data
    transport is discussed.  Be sure to test the sample code included in
    this section.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**5.1.1 Application Layer** <span id="5.1.1"></span> 
-   **Reading: Oracle's “What You May Already Know about Networking in
    Java”**
    Link: Oracle's [“What You May Already Know about Networking in
    Java”](http://docs.oracle.com/javase/tutorial/networking/overview/alreadyknow.html)
    (HTML)  
        
     Instructions: Please read the “What You May Already Know about
    Networking in Java” tutorial.  This tutorial covers basic
    application development for networks.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.2 Networking Basics: TCP or UDP?** <span id="5.1.2"></span> 
-   **Reading: Oracle's “Networking Basics”**
    Link: Oracle's [“Networking
    Basics”](http://docs.oracle.com/javase/tutorial/networking/overview/networking.html)
    (HTML)  
        
     Instructions: Please complete the Networking Basics reading as a
    review of network communication layers.  Note the comparison and
    contrast of TCP with UDP.  What is a port?     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.3 Internet Addresses in Java** <span id="5.1.3"></span> 
-   **Reading: Oracle's “Working with URLs”**
    Link: Oracle's [“Working with
    URLs”](http://docs.oracle.com/javase/tutorial/networking/urls/index.html)
    (HTML)  
        
     Instructions: Please complete the “Working with URLs” tutorial as a
    review of the network addressing convention.  Follow each of the six
    links completing the material provided at each link.  The sample
    code at each link reveals how a lot of the Internet functionality is
    actually coded and reveals its dependency on the sending or
    receiving computer's address.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.4 Sockets** <span id="5.1.4"></span> 
-   **Reading: Oracle's “All about Sockets”**
    Link: Oracle's [“All about
    Sockets”](http://docs.oracle.com/javase/tutorial/networking/sockets/index.html)
    (HTML)  
        
     Instructions: Please complete the “All about Sockets” tutorial for
    an understanding of how client-server processing occurs on the
    Internet.  Follow each of the three links completing the material at
    each link.  What is the client machine class called?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2 Text Transport Using User Datagram Protocol** <span
id="5.2"></span> 
-   **Reading: Oracle's “All about Datagrams”**
    Link: Oracle's [“All about
    Datagrams”](http://docs.oracle.com/javase/tutorial/networking/datagrams/index.html)
    (HTML)  
        
     Instructions: Please complete the “All about Datagrams” tutorial
    for an understanding of how UDP processing occurs on the Internet. 
    Follow each of the three links, completing the tutorial at each
    link.  Compare and contrast sample client-server processing in the
    TCP example in the preceding subunit with the client-server
    processing in this tutorial using the wireless connection.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3 Network Interfaces** <span id="5.3"></span> 
-   **Reading: Oracle's “Programmatic Access to Network Parameters”**
    Link: Oracle's [“Programmatic Access to Network
    Parameters”](http://docs.oracle.com/javase/tutorial/networking/nifs/index.html)
    (HTML)  
        
     Instructions: Please complete the “Programmatic Access to Network
    Parameters” tutorial for an understanding of the network interface
    class.  Follow each of the four links completing the tutorial at
    each link.  Describe a situation where you might use the network
    interface.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.4 Cookies** <span id="5.4"></span> 
-   **Reading: Oracle's “Working with Cookies”**
    Link: Oracle's [“Working with
    Cookies”](http://docs.oracle.com/javase/tutorial/networking/cookies/index.html)
    (HTML)  
        
     Instructions: Please complete the “Working with Cookies” tutorial
    for an understanding of managing cookie classes and interfaces. 
    Follow each of the four links completing the tutorial at each link. 
    Describe a situation where a website you recently visited might have
    used a cookie class and/or interface.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


