**Unit 6: Data Transport** <span id="6"></span> 
*Data that needs to be sent across a network is rarely in plain text
format.  This is in part because transporting data in plain text is not
aesthetically pleasing, and you often need to present data to users in a
visually appealing manner while conserving its organization.  In this
unit, you will learn about XML, a means to organizing data
hierarchically so that it can be transported easily.  You will learn how
XML documents can be sent across a network and parsed on the receiving
end for display.  You will also learn about XSLT and DTD, two schemas
that, like XML, impose structure on documents.  These mechanisms ensure
a certain degree of consistency in data transfer and display.*

**Unit 6 Time Advisory**  
This unit should take you approximately 18 hours to complete.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 6.1: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 6.2: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 6.3: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 6.4: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 6.5: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 21px; text-align: left; -webkit-text-size-adjust: none; ">☐
   </span>Subunit 6.6: 3 hours

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Explain the consistency mechanisms for data transfer and display.
-   Differentiate the coding rationale between HTML and XML.
-   Explain the purpose and use of DTDs.
-   Explain the purpose and use of XML schemas.
-   Compare and contrast document-based and element-based parsing.
-   Complete XML programming tasks. 

**6.1 Extensible Markup Language (XML)** <span id="6.1"></span> 
-   **Reading: Hobart and William Smith Colleges: David J. Eck's
    Introduction to Programming Using Java: “Section 11.5: A Brief
    Introduction to XML”**
    Link: Hobart and William Smith Colleges: David J.
    Eck's *Introduction to Programming Using Java*: [“Section 11.5: A
    Brief Introduction to
    XML”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/01/CS407-TEXTBOOK.pdf)
    (PDF)  
        
     Instructions: Please read Section 11.5 in its entirety.  This
    reading provides a number of examples for using XML data.  Compile
    and run the samples included in this section.   
      
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Non-Commercial-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/).  It is
    attributed to David Eck and the original version can be found
    [here](http://math.hws.edu/javanotes/).

**6.2 Imposing Structure on XML Documents** <span id="6.2"></span> 
-   **Reading: Oracle's “Generating XML Data”**
    Link: Oracle's [“Generating XML
    Data”](http://docs.oracle.com/javaee/1.4/tutorial/doc/IntroXML3.html#wp67593)
    (HTML)  
        
     Instructions: Please complete the “Generating XML Data” tutorial. 
    Pay special attention to the section starting with the “Creating a
    Document Type Definition” header, as this portion of the material
    discusses the format and restrictions of using DTDs for structure
    with XML.  Compile and run all of the samples in this tutorial.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.3 Designing XML Schema** <span id="6.3"></span> 
-   **Reading: Sun Microsystem’s “Designing an XML Schema”**
    Link: Sun Microsystem’s [“Designing an XML
    Schema”](http://docs.oracle.com/javaee/1.4/tutorial/doc/IntroXML4.html#wp64992)
    (HTML)  
        
     Instructions: Please complete the “Designing an XML Schema”
    tutorial.  Compile and run all of the samples in this tutorial.  How
    many files did you create?  Check your
    [answer](http://docs.oracle.com/javaee/1.4/tutorial/doc/IntroXML5.html#wp71637).  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4 Processing Hierarchical Data** <span id="6.4"></span> 
-   **Reading: Sun Microsystem’s “Extensible Stylesheet Language
    Transformations”**
    Link: Sun Microsystem’s [“Extensible Stylesheet Language
    Transformations”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT.html#wp68287)
    (HTML)  
        
     Instructions: Please complete the “Extensible Stylesheet Language
    Transformations” tutorial, which introduces the XSLT standard and
    defines mechanisms for addressing XML data (Xpath).  
        
     What is Xalan?  Oracle tutorials in the subunits that follow use
    the sample code that can be found at the URL at the bottom of the
    page.  You might want to download the files to have them available
    as you need them.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.1 Overview** <span id="6.4.1"></span> 
-   **Reading: Sun Microsystem’s “Introducing XSL, XSLT, and XPath”**
    Link: Sun Microsystem’s [“Introducing XSL, XSLT, and
    XPath”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT2.html#wp68463)
    (HTML)  
        
     Instructions: Please complete the “Introducing XSL, XSLT, and
    XPath” tutorial, which introduces the three subcomponents of XSLT
    and discusses the packages used in the JAXP transformation APIs. 
    Pay attention to each API and when it is used, as you will be using
    these APIs in code samples in your lessons.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.2 How XPath Works** <span id="6.4.2"></span> 
-   **Reading: Sun Microsystem’s “How XPath Works”**
    Link: Sun Microsystem’s [“How XPath
    Works”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT3.html#wp72547)
    (HTML)  
        
     Instructions: Please complete the “How XPath Works” tutorial, which
    explains the XPath mechanisms for addressing XML data.  XPath is one
    of the more complicated processes, so you may want to do a fast read
    of the lesson, and then go back and work to understand each concept
    in this tutorial.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.3 Writing Out a DOM as an XML File** <span id="6.4.3"></span> 
-   **Reading: Sun Microsystem’s “Writing Out a DOM as an XML File”**
    Link: Sun Microsystem’s [“Writing Out a DOM as an XML
    File”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT4.html#wp64603)
    (HTML)  
        
     Instructions: Please complete the “Writing Out a DOM as an XML
    File” tutorial, which uses XPath mechanisms and the Xalan tool. 
    Refer back to the “How XPath Works” tutorial for additional
    competency in creating an XML File.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.4 Generating XML from an Arbitrary File Structure** <span
id="6.4.4"></span> 
-   **Reading: Sun Microsystem’s “Generating XML from an Arbitrary File
    Structure”**
    Link: Sun Microsystem’s [“Generating XML from an Arbitrary File
    Structure”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT5.html#wp64712)
    (HTML)  
        
     Instructions: Please complete the “Generating XML from an Arbitrary
    File Structure” tutorial, which walks you through the process to
    transform any existing structure to XML using DOM or SAX.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.5 Transforming XML Data with XSLT** <span id="6.4.5"></span> 
-   **Reading: Sun Microsystem’s “Transforming XML Data with XSLT”**
    Link: Sun Microsystem’s [“Transforming XML Data with
    XSLT”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT6.html#wp64930)
    (HTML)  
        
     Instructions: Please complete the “Transforming XML Data with XSLT”
    tutorial, which walks you through the steps to translate any XML
    input data to HTML output.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.6 Transforming from the Command Line with Xalan** <span
id="6.4.6"></span> 
-   **Assignment: Sun Microsystem’s “Transforming from the Command Line
    with Xalan”**
    Link: Sun Microsystem’s [“Transforming from the Command Line with
    Xalan”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT7.html#wp84943)
    (HTML)  
        
     Instructions: Please complete the “Transforming from the Command
    Line with Xalan” tutorial by running the code provided.  Xalan is a
    new tool for working with XML.  How is it different from the other
    tools used in your lessons?  
        
      Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.4.7 Concatenating Transformations with a Filter Chain** <span
id="6.4.7"></span> 
-   **Reading: Sun Microsystem’s “Concatenating Transformations with a
    Filter Chain”**
    Link: Sun Microsystem’s [“Concatenating Transformations with a
    Filter
    Chain”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPXSLT8.html#wp72462)
    (HTML)  
        
     Instructions: Please complete the “Concatenating Transformations
    with a Filter Chain” tutorial, which introduces the concept of a
    filter chain and then provides the code to build one.  What is a
    filter chain, and what is its purpose?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.5 Java API for XML Processing (JAXP)** <span id="6.5"></span> 
-   **Reading: Sun Microsystem’s “Introduction to JAXP”**
    Link: Sun Microsystem’s [“Introduction to
    JAXP”](http://docs.oracle.com/javase/tutorial/jaxp/intro/index.html)
    (HTML)  
        
     Instructions: Please complete the “Introduction to JAXP” tutorial,
    which lays out the technologies for using Java with XML data.  What
    is the purpose of JAXP?  What are its principle features?  Oracle
    tutorials in the subunits that follow use the sample code that can
    be found at the [Chapter
    5](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPSAX.html#wp69937)
    header, “Simple API for XML.”  The files are listed at the end of
    the page.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.5.1 SAX Methods** <span id="6.5.1"></span> 
-   **Reading: Sun Microsystem’s “The Simple API for XML APIs”**
    Link: Sun Microsystem’s [“The Simple API for XML
    APIs”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPIntro4.html#wp64181)
    (HTML)  
        
     Instructions: Please complete the “The Simple API for XML APIs”
    tutorial, which graphically presents the event model for converting
    existing data to XML.  What principle methods does it use?  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.5.2 When to Use SAX?** <span id="6.5.2"></span> 
-   **Reading: Sun Microsystem’s “When to Use SAX”**
    Link: Sun Microsystem’s [“When to Use
    SAX?”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPSAX2.html#wp72451)
    (HTML)  
        
     Instructions: Please complete the “When to Use SAX” tutorial, which
    presents a number of different uses for this parser.  How might it
    be used to perform data transport in a LAN?  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.5.3 Echoing an XML File with the SAX Parser** <span
id="6.5.3"></span> 
-   **Assignment: Sun Microsystem’s “Echoing an XML File with the SAX
    Parser”**
    Link: Sun Microsystem’s [“Echoing an XML File with the SAX
    Parser”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPSAX3.html#wp64190)
    (HTML)  
        
     Instructions: Please compile each event in this tutorial as
    instructed in each link.  What happens in each step?  Did your
    output match the tutorial?   
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.5.4 Adding Additional Event Handlers** <span id="6.5.4"></span> 
-   **Reading: Sun Microsystem’s “Adding Additional Event Handlers”**
    Link: Sun Microsystem’s [“Adding Additional Event
    Handlers”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPSAX4.html#wp64500)
    (HTML)  
        
     Instructions: Please complete the “Adding Additional Event
    Handlers” tutorial.  What are two methods for handling common SAX
    events described in this tutorial?  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.5.5 Handling Errors with the SAX Parser** <span id="6.5.5"></span> 
-   **Reading: Sun Microsystem’s “Handling Errors with the Nonvalidating
    Parser”**
    Link: Sun Microsystem’s [“Handling Errors with the Nonvalidating
    Parser”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPSAX5.html#wp64579)
    (HTML)  
        
     Instructions: Please complete the “Handling Errors with the
    Nonvalidating Parser” tutorial, which describes common errors and
    how to prevent them.  What are some of the common parsing errors you
    can avoid?  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6 Document-Based Parsing** <span id="6.6"></span> 
-   **Reading: Sun Microsystem’s “Document Object Model”**
    Link: Sun Microsystem’s [“Document Object
    Model”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM.html#wp79994)
    (HTML)  
        
     Instructions: Please complete the “DOM Object Model” tutorial,
    which lays out the DOM model for using Java with XML data.  DOM is a
    tree structure with nodes.  What types of data are represented as
    nodes on a DOM “jtree”?   Oracle tutorials in the DOM subunits that
    follow use the sample code that can be found at the URL shown at the
    bottom of this tutorial.  You may want to download this code before
    you get to the subunits with tutorials that use the code for its
    examples.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6.1 When to Use DOM** <span id="6.6.1"></span> 
-   **Reading: Sun Microsystem’s “When to Use DOM”**
    Link: Sun Microsystem’s [“When to Use
    DOM”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM2.html#wp67733)
    (HTML)  
        
     Instructions: Please complete the “When to Use DOM” tutorial.  How
    is DOM like SAX?  How is DOM different from SAX?  When is it better
    to utilize the DOM structure?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6.2 Reading XML Data into a DOM** <span id="6.6.2"></span> 
-   **Reading: Sun Microsystem’s “Reading XML Data into a DOM”**
    Link: Sun Microsystem’s [“Reading XML Data into a
    DOM”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM3.html#wp68274)
    (HTML)  
        
     Instructions: Please complete the “Reading XML Data into a DOM”
    tutorial, which provides example code for creating a DOM.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6.3 Displaying a DOM Hierarchy** <span id="6.6.3"></span> 
-   **Reading: Sun Microsystem’s “Displaying a DOM Hierarchy”**
    Link: Sun Microsystem’s [“Displaying a DOM
    Hierarchy”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM4.html#wp64186)
    (HTML)  
        
     Instructions: Please complete the “Displaying a DOM Hierarchy”
    tutorial, which provides sample code to expose DOM nodes so that you
    might examine the structure.  This allows you to gain an
    understanding of DOM structure now as it is a useful diagnostic
    tool.     
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6.4 Examining the Structure of a DOM** <span id="6.6.4"></span> 
-   **Reading: Sun Microsystem’s “Examining the Structure of a DOM”**
    Link: Sun Microsystem’s [“Examining the Structure of a
    DOM”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM5.html#wp64575)
    (HTML)  
        
     Instructions: Please complete the “Examining the Structure of a
    DOM” tutorial, <span id=":9o" dir="ltr">which walks you through how
    a node tree is generated.</span>  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6.5 Constructing a User-Friendly JTree from a DOM** <span
id="6.6.5"></span> 
-   **Reading: Sun Microsystem’s “Constructing a User-Friendly JTree
    from a DOM”**
    Link: Sun Microsystem’s [“Constructing a User-Friendly JTree from a
    DOM”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM6.html#wp64732)
    (HTML)  
        
     Instructions: Please complete the “Constructing a User-Friendly
    JTree from a DOM” tutorial.  How would you explain the internal
    structure of a DOM to a classmate who had problems with the
    assignments you just completed?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.6.6 Creating and Manipulating a DOM** <span id="6.6.6"></span> 
-   **Reading: Sun Microsystem’s “Creating and Manipulating a DOM”**
    Link: Sun Microsystem’s [“Creating and Manipulating a
    DOM”](http://docs.oracle.com/javaee/1.4/tutorial/doc/JAXPDOM7.html#wp65002)
    (HTML)  
        
     Instructions: Please complete the “Creating and Manipulating a DOM”
    tutorial, which lays out the technologies for using Java with XML
    data.  What is the purpose of JAXP?  What are its principle
    features?  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.


