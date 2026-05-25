ChatGPT UI Clone – React Native
Overview

This project is a simple ChatGPT-style mobile UI built using React Native.
It includes a modern dark-themed chat interface where users can send messages and receive fake AI replies.

The app is designed for beginners who want to learn:

React Native basics
State management using useState
Building chat interfaces
Styling with StyleSheet
Handling user input
Features
Clean dark-mode UI
Chat message bubbles
User and AI message alignment
Dynamic message rendering
Input field with multiline support
Send button enable/disable functionality
Fake AI auto-reply using setTimeout
Technologies Used
React Native
JavaScript
React Hooks (useState)
Project Structure
project-folder/
│
├── App.js
├── package.json
└── README.md
Installation
1. Create React Native Project

Using Expo:

npx create-expo-app chatgpt-ui
2. Move to Project Folder
cd chatgpt-ui
3. Replace App.js

Replace the default App.js file with the provided code.

4. Start the Project
npx expo start
How It Works
State Management

The app uses two states:

const [input, setInput] = useState('');
const [messages, setMessages] = useState([]);
input stores the current text field value
messages stores all chat messages
Sending Messages

When the user presses the send button:

User message is added to chat
Input field is cleared
Fake AI response appears after 800ms
Message Rendering

Messages are displayed using:

messages.map()

Each message changes style depending on whether it is:

User message
AI message
UI Components Used
Component	Purpose
View	Layout container
Text	Display text
ScrollView	Scrollable chat area
TextInput	User typing field
TouchableOpacity	Send button
SafeAreaView	Safe mobile screen layout
StatusBar	Status bar styling
Screenshots
Chat Screen UI
4
Future Improvements

You can improve this project by adding:

Real AI integration using OpenAI API
User authentication
Typing animation
Voice input
Image upload support
Message timestamps
Firebase backend
Chat history storage
Learning Outcomes

After completing this project, you will understand:

React Native fundamentals
Mobile UI design
React Hooks
Event handling
Conditional styling
Dynamic rendering
Author

Created by M. Raza

License

This project is open-source and free to use for educational purposes.
