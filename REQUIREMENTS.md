# Software Requirements

## Vision

Welcome to "MindMelter", a learning app that introduces a unique trivia associated with each day's history. Powered by the innovative AI technology of ChatGPT, users can dive deeper into any topic, engage in informative conversations and broaden their knowledge. It's your daily dose of learning, presented in an interactive and enjoyable format.

Step into the world of "MindMelter" and explore the fascinating annals of history at your own pace!

## Scope

### IN

* User can sign up and log in.
* User can view the trivia of the day on the home page.
* User can click on the trivia to open a chat interface and ask questions about the trivia topic.
* User can view a history of past chats.

### OUT

* Users cannot suggest their own trivia.
* The app does not support multiple chat threads or user-user interactions.
* The app will not cover future trivia or trivia planning.

### Minimum Viable Product

* User can create an account and log in.
* User can view today's trivia on the home page.
* User can click on the trivia to initiate a conversation with ChatGPT for deeper learning about the topic
* The user's chat history related to a specific trivia is saved for future reference on their profile page.
* User can edit their name on their profile page.

### Stretch Goals

* The home page will show a feed of previous trivia.
* User can bookmark favorite trivias for easy access.
* User can add a photo to their profile.
* Speech-to-text/text-to-speech for conversations with the AI assistant using Amazon Transcribe/Android.Speech and Amazon Polly
* Incorporate AWS lambda for safe use of OpenAI API key.

## Functional Requirements

* A user can create an account and log in.
* The user can view the trivia of the day.
* The user can initiate a conversation with ChatGPT about the trivia of the day.
* The chat history related to a specific trivia is saved for the user to view later.

### Data Flow

This contains the ins/outs, functional requirements, and data flow of the app

![Domain Model of XXX](images/XXX)

![Database Schema of XXX](images/XXX)

## Non-Functional Requirements

* Security
  * Combine Amazon Cognito with bhash encryption of passwords, and enforce stronger passwords than Cognito's baseline
  * Implement Open AI moderations endpoint and prompt engineering of system messages to enforce proper usage

* Usability
  * Application will focus on user-friendly and intuitive design
  * Best Android practices for accessbility (contrast ratio/speech-to-text/etc...)
