---
layout: full-width
categories: assignment
tags: HTML, web, project
excerpt: Website Project 1 - The Oscars
due-date: 2014-03-07
points: 10
grade-category: Homework
---
# Website Project 1 #

## Purpose ##

Every website you visit is ultimately composed of HTML code.  Understanding the structure behind this language will allow you to not only create your own websites, but make better use of web-building tools.


## Goals ##

*  By the end of this project, you will have built a functioning webpage that is available for the world to see.
* Additionally, you will have demonstrated the ability to use a code editor program (Cloud 9)


## Instructions ##

### Part 1:  Setup and Interactive Demo ###
<span class="label">Whole Class</span>

#### Step 1 ####
Set up our Cloud9 accounts and get started with the basic code:


    <!DOCTYPE html>
    <html>
        <head>
            <title>Type Your Title Here</title>
        </head>
        
        <body>
        
        ~~[Your Webpage Content Goes Here]~~
        
        </body>
    </html>

            
#### Step 2 ####

As a class, we will import our content:  The 2014 Oscar Winners:

1.  Open [this link](https://dl.dropboxusercontent.com/u/3135266/classes/Assignments/Web/Assignment%201/oscars.txt) to get the text
2.  Highlight the text with your mouse and then push <kbd>CTRL</kbd> + <kbd>C</kbd> on the keyboard to copy it.
3.  In your cloud9 workspace, paste the text (<kbd>CTRL</kbd> + <kbd>V</kbd>) in between 
        
        <body>    and
        </body>
        
4.  We will then add HTML code for Paragraphs, Headings and Emphasis to one or two of the sections.
    
         <p>...</p>        Paragraphs
         <h1>...</h1>      Heading Level 1
         <h2>...</h2>      Heading Level 2
         <em>...</em>      Emphasis
         
         

#### Part 2:  Complete the webpage ####
                 
<span class="label">Pair Programming</span>

In this part, you will work as pairs to complete the webpage.  Here is **one** common way to do pair programming:


**Parter 1 is the driver** (this person types the code and operates the computer)

**Parter 2 is the navigator** (this person does not touch the computer, but gives directions to the driver)

After completing the assignment on one of the computers, the partners switch roles and do it again on the other computer.


#### Part 3: Questions ####

<span class="label">Individual Work</span>

Please email your responses to <span class="label alert">chec.shafiei@gmail.com</span>


1.  What is HTML and what does it do?
2.  How did the look of the text change as you added the HTML code?
3.  Look at the sample code below.  What can you infer about the page based on this code?


        <html>
	        <head>
		        <title>View the Source of This Page</title>
	        </head>
	        <body>
		        <h1>How to View the Source of This Page</h1>
		        <p>If you go to your web browser's View menu, you will see an option that allows you to see the source code behind a web page.</p>
		        <p>When the web was first taking off this was a very popular way for people to learn how web pages had been built.</p>
		        <p>Today, people still often view the source of pages to learn how a web page has been built.</p>
	        </body>
        </html>


