# Rough Outline

Part 2 Scope:

Need:

- Improve interaction in lectures
- Provides feedback to lecturers about areas of poor understanding

Goals:

- To allow the host to run quizzes and users to answer them
- Obtain live feedback from students to quickly address areas of misunderstanding
- Engage students

Business Case:

- The need of this new interactive quiz system is that it will provide lecturers
with invaluable feedback about whether students are understanding the content. It will also
use gamification which will increase engagement from users.

Stakeholders: creator (lecturers/students), users (students), host, server admins, The University

High Level Operational Concepts:

- Server admin will set up server package
- Creator will create quizzes of varying length and be able to edit them
- Host will set quizzes to run
- Users will answer questions on a running quiz
- Allow students to register
- A timer will provide a timeout on questions when:
  - all participating players have answered the question
  - The time for the question is up
  - The host terminates the question early
- Generate a unique number/code for users to connect
- Quiz provides a summary at the end of each question
- Quiz generates a report at the end of the quiz

Part 3:

Scenario One - A user signs in and creates a new quiz containing several multiple choice questions. After finishing the quiz, the user shares it with another registered user and logs out.
- The registered user(creater) signs in onto the welcome page
- The user selects the option to create a new quiz
- The user adds a new question
- The user selects the number of options and fills in the question and answer options
- The user selects the correct answer option
- The user sets the predefined timeout
- The user repeats step 3 to 6 until the user is happy and saves the quiz
- The user selects the option to share the quiz
- The user selects the user they want to share with and confirms
- The user logs out

Scenario Two - A host signs in a starts an existing quiz. The players join in and answer the questions.
- The host signs in on the welcome page
- The host selects a defined quiz and a unique number is generated for it
- The users enter the generated number to join the quiz
- The host initiates the quiz
- The quiz goes through the predefined questions
- Each questions ends when the timer has run out, all users have answered or the host terminates the question prematurely
- A summary of answers to the question is displayed after each question ends
- Once all questions have been answered a summary is produced, displayed and saved to the host's account

Part 4:

A user signs in and creates a new quiz containing several multiple choice
questions. After finishing the quiz, the user shares it with another registered
user and logs out

Scope

Need:
- To test other users' understandings
- Provide engagement

Goals:
- A user (Creator) needs to be able to create a quiz with several multiple choice
questions and share the quiz after it is completed.
- Another user, if the quiz is shared with them, needs to be able to access it

Primary Actor:
- User:
	who creates the quiz, shares it with another registered user and logs out

Stakeholders:

- The University:

The university will want to know whether Academic Integrity is being adhered to here,
having an unregulated quiz site could be a safe haven for illegitimately obtained or shared
answers. It could also have foul or obscene language which needs to be regulated.

- The creator:

The creator will want to know whether the quiz they made can be used by other students,
they will also want to know whether only the students they have shared quizzes with can
access the quizzes

- Registered users:

They will want to be able to access quizzes shared with them

Preconditions:

- The creator must be signed in
- The users that the creator intends to share the quiz with must be existing accounts
- All users must have internet connection

Main success scenario:

1) The Creator logs in
2) The Creator creates a New Quiz
3) The Creator creates a New Question
4) The Creator attaches one or more Answers to the Question
5) The Creator repeats step 3 and 4 as many times as desired
6) The Creator can either Save or Exit without Saving
7) The Creator specifies which user(s) they wish to share the quiz with
8) The Creator may sign out
8) A Registered User signs in
9) A Registered User can access the Quiz

Extensions:

1) What could go wrong?

- The Creator may not remember their username/password, and thus will not be allowed to sign in
- The Quiz may be of corrupt format meaning the Creator cannot save/the user cannot access the quiz
- The Quiz may not be saved properly due to incorrect choice, power cut, database crash, etc.
