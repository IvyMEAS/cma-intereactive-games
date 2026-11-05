# CMA Classroom Challenge

Open https://ivymeas.github.io/cma-intereactive-games/

## Instructor
1. Choose a question set.
2. Choose Independent race or Instructor paced and a question time.
3. Select Host live game. Share the displayed link/code.
4. Students enter a display name; wait for them to appear.
5. Select Start game. Keep this tab open.
6. Independent race: students select Continue after feedback. Instructor paced: select Next question to advance the class.
7. End the game and select Download results before closing. Closing or reloading loses the session.

## Student
Open the game link, enter the game code and a display name, and select Join game. Wait for the instructor. Each question is timed. Correct answers earn 1,000 points plus up to 500 speed points. Feedback appears after every answer.

## Canvas
Add an External URL to a module using the public game URL above. Select Load in a new tab. Instructors can host separate sessions from the same page when courses are copied.

## Question sets
Create a question set opens a JSON editor. Download the set to keep a copy. Load that file on another computer or a later day, then select Use question set. Newly created sets are only held in memory until downloaded; they are not automatically published to GitHub.

## Scope and connection requirements
This version uses room codes and display names, not authenticated student/instructor accounts or Canvas SSO. Anyone with the site URL can create their own room. Only the browser creating a room controls that room. Use nicknames rather than student IDs. Scores are session-only and are not sent to Canvas Grades.

GitHub Pages serves the app; PeerJS 1.5.5 and the free PeerServer Cloud broker live browser connections. The instructor browser holds session state and computes scores. Free service availability and school WebRTC/network policies can affect connections. Test on the actual classroom devices/network before class; no TURN relay is configured. This is a classroom practice tool, not a secure graded examination system. Reconnection/resuming after reload is not supported; start a fresh room if needed.

## Starter sets
Medical Word Parts (10 questions) and Medical Terminology Match (8 questions).

## Verification
GitHub Pages deployment completed successfully. A two-tab browser test verified creating a room, student joining, instructor start, a timed question, scoring/feedback, synchronized leaderboard, advancing to question 2, and instructor ending the game. Classroom-scale, cross-network, CSV download, question editor, and instructor-paced mode have not yet been verified in browser.
