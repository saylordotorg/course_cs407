---
layout: default

---
**Unit 4: Transporting Text Across a Network** <span id="4"></span> 
*By now, you know that you can receive input from users and generate
outputs using a subset of streams on a local machine.  In this unit, you
will learn how to create streams to receive input and write output.  You
will focus on writer and reader stream classes, ultimately learning to
open writing and reading streams across machines on a network.*

**Unit 4 Time Advisory**  
This unit should take you approximately 12 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.1: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.2: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.3: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 4.4: 3 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Explain the fundamental concepts of streaming in Java.
-   Differentiate the coding methods for writing and reading across
    machines.
-   Compare and contrast methods for input and output streaming.
-   Complete programming tasks utilizing different streaming methods.

**4.1 Streams Overview** <span id="4.1"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Chapter 11: Advance
    Input/Output Streams, Files, and Networking”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Chapter 11:
    Advance Input/Output Streams, Files, and
    Networking”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read the introduction to Chapter 11.  Note the
    topics to be covered in the subunits that follow.  Explain the role
    of streams in networking.  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**4.2 Stream Definition and Types** <span id="4.2"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 11.1: Streams,
    Readers, and Writers”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 11.1:
    Streams, Readers, and
    Writers”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)(PDF)  
        
     Instructions: Please read Section 11.1 in its entirety.  What types
    of data streams are covered in this section?  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**4.3 Files** <span id="4.3"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 11.2: Files”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 11.2:
    Files”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read Section 11.2 in its entirety.  Compile
    and run the samples included.  Because files have to be protected
    for security, how is the data in a file processed?  
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**4.4 File Processing** <span id="4.4"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 11.3: Programming
    with Files”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 11.3:
    Programming with
    Files”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read all of Section 11.3, which provides a
    number of examples for processing files.  Compile and run the
    samples included.   
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**4.5 Streaming Checkpoint** <span id="4.5"></span> 
-   **Assessment: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Programming Exercises for
    Chapter 11”**
    Link: Hobart and William Smith Colleges: David J. Eck's
    *Introduction to Programming Using Java*: [“Programming Exercises
    for Chapter
    11”](http://www.saylor.org/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please complete the exercises for subsections 11.1
    through 11.3.  Each exercise identifies the subsection it is based
    on.  Review that subsection if you need more information before
    completing that exercise.  When you have finished, solutions are
    found at the link to the right of the question.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).


