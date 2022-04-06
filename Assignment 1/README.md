# Learning Music the Easy Way
## Assignment 1: Heuristic Evaluation
### Ariel Kuo | Spring 2022 
DH 110: User Experience and Design 

**About the Project**  
For a middle-aged man, learning music theory online can be a daunting task with the overflow of information available. There are numerous options for learning, and it may be difficult to find one source that can fit the needs of the student. In this assignment, I will evaluate two different options for online music theory learning using Nielsen and Molich's 10 user interface design heuristics. 

### Heuristics and Severity Ratings 

**Nielsen and Molich's 10 user interface design heuristics** 

1. **Visibility of system status** - The interface should indicate to the user the current system status.
2. **Match between system and the real world** - Information and terminology on the interface should match how they are experienced in the real world.
3. **User control and freedom** - Users should be able to move back and forth within an interface.
4. **Consistency and standards** - Features and terminology should be kept consistent throughout the interface when referencing a certain task or topic.
5. **Error prevention** - The interface should be designed to minimize possible user errors.
6. **Recognition rather than recall** - The user should understand what is happening on the interface without drawing on previous knowledge.
7. **Flexibility and efficiency of use** - The user should be able to navigate the website efficiently with minimal steps.
8. **Aesthetic and minimalist design** -  The interface should not include unneccessary or distracting content that would clutter the space.
9. **Help users recognize, diagnose and recover from errors** - Include error prevention and error messages that can guide the user to fix the problem.
10. **Help and documentation** - The user should be able to seek help within the website.

**Nielsen Norman Group Severity Ratings**  

**0** = Not a usability problem 
**1** = Only a cosmetic problem 
**2** = Minor usability problem given low priority 
**3** = Major usability problem given high priority 
**4** = Must be fixed before product release 

### Option 1: musictheory.net

URL: https://www.musictheory.net/ 

**About the Website**  
The website musictheory.net is an online tool for learning music theory. The website includes free learning features like Lessons, Exercises, and Tools, as well as paid premium apps called Theory Lessons and Tenuto. 

![homepage](musictheory-screenshot.png) 

**Heuristic Evaluation** 

| Heuristic      | Evaluation     | Recommendation | Severity Rating | 
| ------------- | ------------- | ----- | ------- |
| Visibility of system status |**Good:** The title of the page is underlined when the user is on that page **Bad:** When doing an exercise, the title of the exercise is only shown for about 1 second before it is replaced with the user's score. This could cause the user to forget which exercise they are currently on. | At the top of the exercise page, the website should read "Exercise" as well as the exercise name such as "Key Signature Identification" during the whole duration of the exercise. | 2 | 
|Match between system and the real world|   **Good:** The page titles are user-familiar words like "Lessons," "Tools," and "Products."  **Bad:** Although the page labels are clear, there is no description stating the purpose of these pages.   | Provide a description at the top of each page describing the purpose. For example, "Use our Exercises to practice your music theory knowledge." | 2 |
|User control and freedom| **Good:** On every lesson, exercise, or tools page, there is a home icon that can take the user back to the previous page.   **Bad:** 1. Once returning to the previous page using the home button, the user cannot return back to the same spot in their lesson/exercise because the progress is not saved.  2. The home icon only takes the user back one page, not to the actual home page of the website which can be misleading. | Auto-save user progress within a lesson or exercise, and include a "Continue" option to allow the user to continue the lesson where they left off.  Include a button that clearly states "Back to Home" and another button for "Back to Lessons/Exercises/Tools" to give the user clarity and freedom. These can be implemented in a dropdown option. | 3 |
|Consistency and standards| **Good:** Page titles and terms are kept consistent throughout the website.  **Bad:** The brand's products are displayed twice, once on the home page and again under the "Products" page. This is redundant and can cause user confusion. | Get rid of the "Products" page, or link the product page to the home page to keep all of the same information in one place. | 3 |
|Error prevention| **Good:** There is little room for user error on the website, because lessons, exercises, and tools are executed with buttons only (no typing). **Good:** There is a "reset score" function within exercises in case one makes a mistake or wishes to start over. **Bad:** There is no single-action undo function, so if the user makes a mistake they have to reset their whole score rather than going back one step.  | Include an "undo" feature within exercises to give the user the ability to undo one error. | 3 |
|Recognition rather than recall| **Good:** There are no short-answer options, only button selection for answers (similar to multiple-choice). This prevents the user from having to recall information. **Bad:** Features in Exercises and Tools use terminology that one would have to recall from Lessons. | Include links to necessary/relevent lessons within the exercise or tool page. For example, the exercise "Key Signature Identification" should include a link to the lesson "Key Signatures". | 2 |
|Flexibility and efficiency of use| **Good:** The user can either click back and forth arrows or use the back and forth arrow keys on the keyboard to move within a lesson. **Bad:** All of the options within an exercise (such as "reset score" or "show timer" require an extra click on the top right corner to reveal the options, and there are no shortcuts for the options. | Include a sidebar on the exercise page with the available options for the user to minimize steps. | 2 |
|Aesthetic and minimalist design| **Good:** This website is very good about keeping uneccessary information to a minimum, considering how much content there is on the website. **Bad:** The website is very simple, and the lessons, exercises, and tools are organized as lists on those pages, which is not the most efficient organization because the user has to scroll to find their current lesson. | The lessons, exercises, and tools should be organized by section (like subfolders) rather than a long running list. | 1 |
|Help users recognize, diagnose and recover from errors| **Good:** There is little room for error on the website, and incorrect answers within an exercise are made clear with red coloring, while correct answers are in green. | N/A | N/A |
|Help and documentation| **Good:** Under the "Contact" page, users have the option to contact the company via a message box, and there is a link to frequently asked questions on this page. **Bad:** There is no search bar on the website if the user wishes to find information about a topic, and the title "Contact" does not make it clear this is where the user should go for help in general. | The page should be titled "Help", and then include options to go to the FAQ page or to submit a message. Also, include a search bar for the website so the user can easily find relevant information. | 4 |

**Overall Evaluation**  
For a middle-aged man, this website is a pretty good starting point for learning music theory. The interface is kept very simple and is relatively easy to use. There is a lot of content and useful information on the website, and little unneccessary information shown. Overall, the website is sufficient but could use many improvements in the interface to create a better learrning experience for the user.

### Option 2: lightnote.co

URL: https://www.lightnote.co/

**About the Website**  
The website lightnote.co is a basic interactive website for learning music theory. The website features a free complete lesson on basic music theory, as well as an option for a paid "Lightnote Premium" music theory course.

![homepage](lightnote-screenshot.png) 

**Heuristic Evaluation** 

| Heuristic      | Evaluation     | Recommendation | Severity Rating | 
| ------------- | ------------- | ----- | ------- |
| Visibility of system status |**Good:** The current lesson is highlighted on the right sidebar to show the user which lesson is currently on the screen. **Bad:** The interface's scrolling format makes the distinctions between lessons less clear, such as when scrolling between two different lessons. | The scrolling format can be kept within each lesson, but each lesson should be on a different page to maintain the distinction. | 3 | 
|Match between system and the real world|   **Good:** The website title "How Music Works" with subtitle "Interactive Music Theory Lessons" makes it clear to the user the website's purpose. The description actually states "no confusion notation," which is true throughout the website. Simple terms are used to describe more complex music theory terms.  | N/A | N/A |
|User control and freedom| **Good:** The user can freely scroll back and forth between lessons, as well as click on the lesson they want on the right sidebar which is visible at all times. **Bad:** The scrolling format almost leaves too much freedom, making it easy for the user to potentially lose the spot they left off on. | Separating lessons by page would give the user clear control and allow for easier navigation. Including "Next Lesson" and "Previous Lesson" buttons will also make the experience more organized and give the user a sense of progress rather than endless scrolling. | 3 |
|Consistency and standards| **Good:** Terms and format are kept consistent throughout the free portion of the website. **Bad:** There are two ways to view the premium option, with the button "Lightnote Premium" on the sidebar and "View the Course" at the end of the free lesson. | Change "View the Course" to "Lightnote Premium" to keep terminology consistent and avoid user confusion. | 1 |
|Error prevention| **Good:** There is little room for user error on the website, because the free lesson consists mainly of examples or guided multiple-choice questions. **Good:** There is a clear back option if the user clicks on the premium page, and the user can easily navigate between lessons if they clicked the wrong one. **Bad:** There is no "Hide answer" option, so after the user clicks "Show answer" they cannot undo it if it was a mistake. There is also no retry for an example problem.  | Include a "Hide answer" option and a "Retry" option within lessons to give the user the option to retry the example problem. | 2 |
|Recognition rather than recall| **Good:** There are no short-answer options, only button selection for answers (similar to multiple-choice). This prevents the user from having to recall information. **Bad:** Each lesson builds on knowledge from previous lessons and includes terminology from those previous lessons. This means the user would have to recall information in order to understand the new information. | When specific terminology is used, hyperlink the corresponding lesson so the user can quickly read about necessary concepts rather than recalling. | 1 |
|Flexibility and efficiency of use| **Good:** The user can click on the desired lesson if they do not want to go through the work of scrolling to find it. **Bad:** The scrolling format is not very efficient to move through lessons or skip to a desired section within a lesson. | Include an arrow button or "Next" button to bring the user to the next section of a lesson faster than scrolling. | 2 |
|Aesthetic and minimalist design| **Good:** This website keeps unnesseccary information to a minimum and features a minimalist and easy design. **Bad:** Because the format is so simple, the website lacks features that could help the user track their progress through the lessons. | Include indications that a lesson has been completed so the user can track their progress. | 1 |
|Help users recognize, diagnose and recover from errors| **Good:** There is little room for error on the website because of the lack of short-answer boxes. Wrong answers in the problems are explained as well as correct answers. The user can also easily navigate between pages if they clicked the wrong one. | N/A | N/A |
|Help and documentation| **Good:** Answers to the questions are explained for the user. **Bad:** There is no search bar on the website if the user wishes to find information about a topic, and also no point of contact or FAQ section. | The website should definitely include resources for help considering it is a learning tool. There should at least be a point of contact, and a search bar and FAQ section would be very helpful.  | 4 |

**Overall Evaluation**  
This website is very simple and easy to understand. The information is all on one page, the font is large, and explanations are kept simple, which are great features for an audience of middle-aged men. This website would be good for an introduction to music theory, but would not likely be sufficient as an all-in-one learning tool because it is so simple and does not contain a lot of content. 


**Credits** 
https://www.interaction-design.org/literature/article/heuristic-evaluation-how-to-conduct-a-heuristic-evaluation  
https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/ 
