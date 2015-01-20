---
layout: default
course: CS407
course_fulltitle: 'Network Applications Development'
course_description: 'Exploration of the design and implementation of network-based applications, focusing on Object-Oriented Programming and programming techniques, both at the application layer and the transport layer of the TCP/IP protocol stack.'
---
**Unit 8: Transporting Function Calls** <span id="8"></span> 
*In the last unit, you learned how objects can be transported across
networks so that other programmers can use those objects’ methods.  This
unit will introduce a different method of object sharing: initiating a
function call on a certain object type when the object resides on a
remote machine by using Java RMI and SOAP.  The unit will close with a
discussion of programming excellence including program correctness,
robustness, and efficiency.*

**Unit 8 Time Advisory**  
This unit should take you approximately 12 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.1: 4 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.2: 4 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 8.3: 4 hours

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Explain object sharing in a network. 
-   Explain the purpose and use of Java RMI.
-   Explain the purpose and use of the SOAP.
-   Complete Java RMI and SOAP programming tasks.
-   Code problems using of techniques for program excellence.

**8.1 Java RMI** <span id="8.1"></span> 
-   **Reading: Oracle's “An Overview of RMI Applications”**
    Link: Oracle's [“An Overview of RMI
    Applications”](http://docs.oracle.com/javase/tutorial/rmi/overview.html)
    (HTML)  
        
     Instructions: Please read this entire webpage.  As you look at the
    components required for a Java application, what is included that
    you have not seen anywhere else in this course?  Excluding the
    application example, there should not be anything new.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.1 Oracle's “Writing an RMI Server”** <span id="8.1.1"></span> 
-   **Reading: Oracle's “Writing an RMI Server”**
    Link: Oracle's [“Writing an RMI
    Server”](http://docs.oracle.com/javase/tutorial/rmi/server.html)
    (HTML)  
        
     Instructions: Please read this page.  This material has been
    divided into two separate readings.  The RMI Design Process will be
    covered in subunit 8.1.2 that follows.  The RMI Implementation
    Process will be covered in subunit 8.1.3 below.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.2 RMI Design Process** <span id="8.1.2"></span> 
-   **Reading: Oracle's “Designing a Remote Interface”**
    Link: Oracle's [“Designing a Remote
    Interface”](http://docs.oracle.com/javase/tutorial/rmi/designing.html)
    (HTML)  
        
     Instructions: Please complete this page.  Review the sample code to
    see how to build the compute engine to process code from any
    machine.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.3 RMI Implementation Process** <span id="8.1.3"></span> 
-   **Reading: Oracle's “Implementing a Remote Interface”**
    Link: Oracle's [“Implementing a Remote
    Interface”](http://docs.oracle.com/javase/tutorial/rmi/implementing.html)
    (HTML)  
        
     Instructions: Please complete this page.  Review the sample code to
    see how to build the interface to implement the compute engine.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.4 Creating a Client Program** <span id="8.1.4"></span> 
-   **Reading: Oracle's “Creating a Client Program”**
    Link: Oracle's [“Creating a Client
    Program”](http://docs.oracle.com/javase/tutorial/rmi/client.html)
    (HTML)  
        
     Instructions: Please read the screen carefully.  Review the sample
    code to see how to create a client program to define the task to be
    performed by the compute engine.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.5 Running Java RMI** <span id="8.1.5"></span> 
-   **Reading: Oracle's “Compiling and Running the Example”**
    Link: Oracle's [“Compiling and Running the
    Example”](http://docs.oracle.com/javase/tutorial/rmi/example.html)
    (HTML)  
      
     Instructions: Please compile and run the example.  You will need to
    use both links provided in the material.  What is your problem, and
    what output does this process produce?  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2 Simple Object Access Protocol (SOAP) and SOAP with Attachments API
for Java (SAAJ)** <span id="8.2"></span> 
-   **Reading: Sun Microsystem’s “Overview of SAAJ”**
    Link: Sun Microsystem’s [“Overview of
    SAAJ”](http://docs.oracle.com/javaee/1.4/tutorial/doc/SAAJ2.html#wp72293)
    (HTML)  
        
     Instructions: Please read the “Overview of SAAJ” tutorial.  SAAJ is
    an API that developers can use to write SOAP messaging applications
    directly, especially for XML messaging from the Java platform. 
    Because the SAAJ API conforms to the Simple Object Access Protocol
    (SOAP) specification, the elements of SOAP are also covered in the
    6.2 subunits that follow.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.1 SOAP Protocol** <span id="8.2.1"></span> 
-   **Reading: W3C's “Simple Object Access Protocol (SOAP)”**
    Link: W3C's [“Simple Object Access Protocol
    (SOAP)”](http://www.w3.org/TR/2000/NOTE-SOAP-20000508/) (HTML)  
        
     Instructions: Please complete the SOAP tutorial.  As you progress
    through this material, you will have the opportunity to examine the
    SOAP protocol as specified by W3C.  Compile and run each of the
    examples provided.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.2 SAAJ** <span id="8.2.2"></span> 
-   **Reading: Sun Microsystem’s “Overview of SAAJ”**
    Link: Sun Microsystem’s [“Overview of
    SAAJ”](http://docs.oracle.com/javaee/1.4/tutorial/doc/SAAJ2.html#wp72293)
    (HTML)  
        
     Instructions: Please complete the SAAJ tutorial found at this
    link.  Follow the steps in the material to create a SOAP message,
    send the message, and retrieve the response.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.3 Examples** <span id="8.2.3"></span> 
-   **Reading: Sun Microsystem’s “Code Examples”**
    Link: Sun Microsystem’s [“Code
    Examples”](http://docs.oracle.com/javaee/1.4/tutorial/doc/SAAJ4.html#wp66012)
    (HTML)  
        
     Instructions: Complete the “Code Examples” tutorial starting with
    the first example.  Follow the instructions that precede each
    example.  Look for the SOAP elements in each example.  Once you
    compile and run each example, proceed to the next one.  A good
    reference for using SOAP can be found
    [here](http://docs.oracle.com/cd/A97630_01/appdev.920/a96616/arxml11.htm).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3 Correctness, Robustness, and Efficiency** <span id="8.3"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Chapter 8: Introduction to
    Correctness and Robustness”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Chapter 8:
    Introduction to Correctness and
    Robustness”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of Chapter 8.  The topics of each
    section in Chapter 8 cover the material you need to know for
    subunits 8.3.1 through 8.3.6.  Now that you have completed the prior
    units, showing you how the Java language is used in the network
    programming environment, it is time for you to hone in on your
    skills to be a superior Java programmer.  As you complete each
    subunit compare and contrast each tool for creating the most
    efficient code.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**8.3.1 Correctness and Robustness** <span id="8.3.1"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 8.1: Introduction
    to Correctness and Robustness”**
    Link: Hobart and William Smith Colleges: David J. Eck's
    *Introduction to Programming Using Java*: [“Section 8.1:
    Introduction to Correctness and
    Robustness”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of  Section 8.1.  Explain the
    difference between correctness and robustness.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**8.3.2 Writing Correct Programs** <span id="8.3.2"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 8.2: Writing
    Correct Programs”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 8.2:
    Writing Correct
    Programs”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of  Section 8.2.  Compile and run the
    samples provided in this material.  Explain the role of process and
    state for correctness.  How does the role of process and state
    impact robustness?  How do you write code that you can “prove” is
    correct?  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**8.3.3 Exceptions and Try…Watch** <span id="8.3.3"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 8.3: Exceptions and
    Try...Catch”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 8.3:
    Exceptions and
    Try...Catch”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of Section 8.3.  Note the various
    types of exceptions that might occur and how you can improve your
    Java code to provide for them.  Compile and run the sample code
    provided.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**8.3.4 Assertion and Annotation** <span id="8.3.4"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 8.4: Assertion and
    Annotations”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 8.4:
    Assertion and
    Annotations”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of  Section 8.4.  Note that this
    material provides advanced information for using assertions and
    annotations in your Java code.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**8.3.5 Analysis of Algorithms** <span id="8.3.5"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 8.5: Analysis of
    Algorithms”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 8.5:
    Analysis of
    Algorithms”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of  Section 8.5.  Network efficiency
    programs depend on the analysis of algorithms.  This section will
    show you what this specialization is and how it can be accomplished
    with Java programs.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**8.3.6 Programming Exercises** <span id="8.3.6"></span> 
-   **Assessment: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Programming Exercises for
    Chapter 8”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Programming
    Exercises for Chapter
    8”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Compile and run each programming exercise following
    the instructions provided with each problem.  You will find the link
    to the solution in the right hand corner preceding the next problem
    or end of the assessment.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).


