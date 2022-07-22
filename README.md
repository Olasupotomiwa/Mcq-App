# Multiple Choice Question Web Application


## Table of Contents

- [Description](#description)

- [Challenges](#challenges)

- [Usage](#usage)

- [Materials](#materials)

- [Credits](#credits)

## Description

```md 
   ![Mcq picture](assets/images/)
```

*This project is a Multiple Choice Question Web-application which allow users to put their knowledge to test on a particular area of interest like Use of English, Mathematics, General Knowledge etc
 within a stipulated time and get the result almost immediately. There is also an option for groups, organization, schools to deploy their question on the Web-App.
I was motivated to build this after weeks of learning Javascript. Truly I have come across similar projects like this, some are usually named Quiz app but 
I want mine to stand out. Hence, the name ##Multiple-Choice-Question-Web-application [MCQ APP].

*It was necessary that I put my knowledge into practice as it enabled me to realize my strength and where I should put more effort.


## Usage

*Making use of the application is quite easy. Users are directed to the homepage to choose their preferred subject, followed by instruction on the chosen area of interest.
I ensured users are not directed to the quiz page immediately after clicking the ##Get-started button. This is to allow users to be fully ready by the time the questions would be displayed.
The next button on the app allows users to proceed while the submit button end the quiz and display result subsequently.

*Depending on the selected area of interest, a calculator was also designed to be used. It was programmed to be shown at the top left corner on large screens so as to avoid it overlaying the live countdown, bottom left corner on small screens to allow users view the question while being used.
The quiz ends when the allotted time lapse.

Click [here](https://olasupotomiwa.github.io/Mcq-App/Quiz doc) to use the App.


## Challenges
 I faced a lot of challenges while building the App. 

 1. I had difficulty in manipulating the bootstrap modal to display different instructions which I later realize it was caused by the modal having the same ID. I solved this by deactivating the Javascript function of the modal and I make of the JQUERY modal show and hide function to solve the problem
 2.Being my second time of using the CSS loader, I had to fix a lot of bug to make sure the SetTimeout function stops the loader at the desired time.
 3.Lol, I was oblivious of the Cleartimeout function. So even after submitting, the programmed HTML content to be displayed still over write the one programmed to be displayed when the user submits. I made ise of google and got it solved.
 Also, making it accessible in the DOM was quite difficult but after reading my Global scope and hoisting I fixed it.
 4. Faced a lot of responsive issues as well.

 *However, all these helped me to have a better understanding of how Javascript works especially using callback functions, manipulating HTML content of a page, using live countdown, passing in argument into function, and the SetTimeout function as well.

 ## To Do
*I hope to improve it in the future so as to allow users login, take the test, have their performances documented on the app and so on.

## Materials
*HTML *CSS *JAVASCRIPT *JQUERY *BOOTSTRAP
- Of course HTML was used as the markdown language, lol.
- The beautiful styling, fade animation as well as the loaders were implemented with multiple editing of the CSS files
- JQUERY was used to control the modal content
- Almighty Javascript control the logical aspect: accessing the questions and answer array, using boolean to set the correct answer, incrementing the scores and the questions progress as well as displaying result at the end.
-BOOTSTRAP was used to create the responsive cards with subjects at the homepage.

## Credits

Zino Trust Tutorial on Youtube.
I got the idea to build the App by watching two youtube videos. What I built is, however different from what I watched.



