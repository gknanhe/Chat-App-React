# React Chat Application

This project is a front end for a chat application built with React. The application enables users to create conversations, search for contacts, send messages within conversations, and handle alerts. The project uses dummy data from a JSON file for demonstration purposes.

## Hosted Link (https://gregarious-nougat-92f7d8.netlify.app/)

## Functionality

- chat with friends.
- add new users to chat
- Search a user by name






## Project Structure

      src/
          ├── components/
          │   ├── Conversations.js
          │   ├── MessageContainer.js
          │   ├── Conversation.js
          │   ├── NewConversation.js
          │   ├── ConversationCard.js
          │   └── NewMessageContainer.js
          │   └── index.js
          ├── styles/
          │   ├── Conversations.css
          │   ├── MessageContainer.css
          │   ├── Conversation.css
          │   ├── NewConversation.css
          │   ├── ConversationCard.css
          │   ├── NewMessageContainer.css
          │   ├── App.css
          ├── DummyData/
          │   ├── dummycontacts.json
          │   ├── dummyConversations.js
          ├── App.js
          ├── index.js




## Table of Contents

- [Components](#components)
- [Styles](#styles)
- [Dummy Data](#dummy-data)
- [App.js](#appjs)

## Components

- **`Conversations.js`**: Displays the list of conversations in the left sidebar.

- **`MessageContainer.js`**: Represents the message container for a conversation.

- **`Conversation.js`**: Represents an individual conversation, showing contact name and last message snippet.

- **`NewConversation.js`**: Displays a pop-up with a list of contacts to initiate a new conversation.

- **`ConversationCard.js`**: Renders an individual conversation card.

- **`NewMessageContainer.js`**: Provides a form to send messages within a conversation.

## Styles

The `styles` directory contains CSS files for styling individual components.

- **`Conversations.css`**
- **`MessageContainer.css`**
- **`Conversation.css`**
- **`NewConversation.css`**
- **`ConversationCard.css`**
- **`NewMessageContainer.css`**
- **`App.css`**

## Dummy Data

The `DummyData` directory contains JSON files with dummy data for contacts and conversations.

- **`dummycontacts.json`**
- **`dummyConversations.js`**

## App.js

- **`App.js`**: The main component that handles routing and state management using React hooks.

### Clone Project

1. Clone the repository to your local machine.

2. Navigate to the project folder using the terminal.

3. Install dependencies using `npm install`.

4. Start the development server using `npm start`.

5. The app will open in your default web browser at `http://localhost:3000`.

## Dependencies

The project uses the following dependencies:

- React: A JavaScript library for building user interfaces.
- React Router: A library for handling routing within a React application.
- Redux (optional for bonus feature): A state management library for React applications.

## Notes

This is a frontend-only chat application that simulates user interactions using dummy data. The project provides a foundation for building a real-time chat application with features such as conversation management, message sending, and alerts.

---

With this README, developers will have a comprehensive understanding of the chat application's functionality, structure, and how to run it. Place this README at the root of the project repository and ensure it's written in Markdown format for optimal presentation on GitHub.





### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
