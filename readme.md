# Chatbot

This is a simple chatbot built using HTML, CSS, and JavaScript. The bot can respond to basic greetings, inquiries, and certain commands. It's designed for conversational interactions and can respond with pre-defined messages.

## Features

- Responds to basic greetings like "Hello", "Hi", "Hey"
- Can introduce itself as "Jarvis"
- Provides a few simple responses to inquiries about its capabilities and how it's doing
- Responds to basic queries like "Tell me a joke"
- Handles some negative feedback with a polite message

## Technologies Used

- HTML5 for structuring the chatbot interface
- CSS3 for styling the layout and appearance
- JavaScript for chatbot logic and event handling
- Font Awesome for the Telegram icon on the send button

### HTML (`index.html`)

- A simple structure with a container holding the chatbot interface.
- A text input field and button for users to send messages.
- Links to external stylesheets (CSS and Font Awesome) and the `script.js` file for functionality.

### CSS (`style.css`)

- Styles the chatbot container, messages, and avatars.
- Uses Google Fonts for a custom font.
- Styles user and bot messages differently for a clear UI distinction.

### JavaScript (`script.js`)

- Defines the chatbot function (`chatbot(input)`) that processes user input and returns the corresponding response.
- Contains two functions, `displayUserMessage` and `displayBotMessage`, to display the respective messages in the chat window.
- Includes logic to handle user input through the `input` field and send button (`sendMessage` function).
- Listens for both click events on the send button and keypress events (Enter key) to send messages.

## How to Use

1. Open `index.html` in any modern web browser.
2. Type a message in the input box and click the send button or press Enter.
3. The bot will reply based on your input.

## Example Interactions

- **User**: "Hi"  
  **Bot**: "Hello, nice to meet you!"

- **User**: "What is your name?"  
  **Bot**: "My name is Jarvis, I'm a chatbot."

- **User**: "Tell me a joke"  
  **Bot**: "Why did the chicken go to the seance? To get to the other side."

## Credits

- Chatbot designed and implemented by Suraj Kumar.
- Uses Font Awesome icons and Google Fonts (Poppins).
