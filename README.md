Project
Task Build a Note-Taking Web App, using React.js, that accepts text, URL, and
audio as input and transcribes it to text using Browser Web Speech API
Functional Requirements:
Please build a single-page React.js app with the following specs:
 It is mandatory to build the UI using Nextjs or React/ejs, feel free to use a
React UI library like Shadcn, Tailwind, or any other of your choice to develop
the project and match the design as closely as possible.
 The App should have authentication using JWT, both sign-up and login should
be functional.
The design can be kept simple, focusing solely on ensuring the required
fields and functionality work as expected.
 The main page of the app should display all the notes of the user, these notes
should be stored in MongoDB and the note list should be sortable from old to
new.
 Note Creation
a A note can be created using a text, and audio record button
b When you click on the start recording button it should record your voice
(max duration 1min) and when you stop recording it should transcribe the
audio into text using Browser Web Speech API check this documentation
and create a note using the transcribed text.
c The design for this is on the Main Page at the bottom. you are free to build
your own design.
Project 2
 Note Card Functionality
a Delete note button
b Rename note button
 On clicking on any note card
a It should display a modal that has the content of the note
b If it is an audio note it will have the transcription
c Ability to edit the note
 Search Feature (optional)
a There should be an option to search notes at the top of the title and the
content of the note should be searchable across all the notes a user has.
b Typing anything in the search bar should update the page view with the
note search results in real-time
 
