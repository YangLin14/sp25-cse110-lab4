1. Some JavaScript developers believe that most of the issues with JavaScript stem from its asynchronous nature, its loose typing, and the web platform it runs on. For each of the three reasons listed, explain in your own words why a developer might believe that it is a pain point.

    #### a. Asynchronous Nature

    JavaScript was built to handle tasks that might not finish immediately without stopping other tasks. Because of that, it makes the debugging process a lot harder because it could be hard to track when this error is happening since the error message could come out at a werid time. Leading to create bugs that are hard to notice and harder to fix.

    #### b. Loose Typing
    JavaScript doesn't force us to declare our variable types like C does. Meaning we can first set a number variable and later change it to a string. This can make coding faster but can lead to creating confusing bugs accidentally. Such as `'1' + 2 = '12'` instead of `3` when `2 - '1' = 1`. Because of automatic type conversion (or "coercion"), it can cause unexpected results that are hard to debug, especially in large project.

    #### c. Web Platform
    Different browswers might perform slightly differently. So when building rich application on top of this messy foundation could feel like building something that will easily collapse (constantly stacking things up to make them work reliably on different platforms). 


2. Related to the first question, why do you believe that the developer(s) who created JavaScript made it loosely typed? Why do you think they added asynchronous features?

    I think they it's because in the beginning when JavaScript was built for is to make small simple web pages more interactive, instead of big websites or applications that we see nowadays. With that, they only need language that is fast to write and easy to use. That's why automatic type conversion and asynchoronous features came up.


3. What are the key differences between a compiled language and an interpreted one? Which one is JavaScript? What are the benefits & drawbacks of JavaScript being made that way?

    A <strong>complied language</strong> is something like C/C++ that requires the source code to be translated into machine code <i>before</i> it can run. This complied file is what the computer actually execute, not the original code itself.
     
    JavaScript is an <strong>interpreted language</strong>, which runs the original code <i>directly</i> with the help of an interperter that reads and executes it line by line at runtime.
    
    The benefits of this could be easy debugging using DevTools and faster development since we can test the changed code immediately without needing to complie everything. The drawbacks could be sometimes it can be messy and the performance differs on different platforms.

4. The professor believes that, though sometimes misused, JavaScript frameworks are incredibly powerful tools that can help teams work more efficiently and effectively. Given that, why do you believe he is focusing more on vanilla JavaScript for this course? What are the benefits of mastering vanilla JS first? What are the drawbacks of not learning a framework?

    I believe the professor is focusing more on vanilla JavaScript because he wants us to build a strong foundation first — to fully understand how JavaScript works at its core before relying on frameworks. He once said that "we have to know what good outcomes look like before reaching those good outcomes," and I think he’s training us to recognize what clean, efficient JavaScript code looks like and how to reach it step-by-step.

    Mastering vanilla JavaScript first has important benefits:

    * It teaches us how the language actually behaves under the hood.
    * It helps us become better problem-solvers without relying on shortcuts or pre-built tools.
    * It makes it easier to learn frameworks later, because frameworks are ultimately just JavaScript underneath.
    * We'll be able to customize, troubleshoot, or even write framework code ourselves if necessary.

    Some drawbacks on not learning a framework could be slower development since others might have already solved that problem that is troubling you; harder to work on real-world project since most of them are using frameworks.


5. Explain, in your own words, how you think this lab relates to your project. How might you be able to use this information in your own project?

    I actually spent the whole day just focus working on this lab. Right now, 9 hours has passed and I'm finally finishing it. To be honest, this lab helps me a lot on understanding how JavaScript works including the syntax and its problems. Drawing the flowchart is also another critical thing I learned from this lab. These are skills that I would bring to the real-world job and this course's team is a place for me to practice them.