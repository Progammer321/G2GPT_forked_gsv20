G2GPT Multi-LLM Chat Application
Description:

This project is a web-based chat application that allows users to interact with multiple language models at the same time. The goal of the project was to create a simple interface where a user can send a single prompt and receive responses from multiple models in parallel, making it easier to compare outputs.

The application also supports saving conversations, viewing previous chats, and searching through conversation history. Throughout the development of this project, I followed an Agile approach and worked iteratively across requirements, development, and testing.

Installation:

Clone the repository:
git clone https://github.com/Programmer321/G2GPT_forked_gsv20.git

Navigate into the project directory:
cd G2GPT_forked_gsv20

Install dependencies:
npm install

Start the server:
npm start

Usage:

After starting the server, open a browser and go to:
http://localhost:3000

From there, you can create an account or log in, start a new conversation, select one or more models, send prompts, and view responses. The sidebar allows you to revisit previous conversations and use the search bar to filter through them.

Features:
Multiple model responses for a single prompt
Conversation history persistence using SQLite
Search functionality for saved chats
Basic user authentication including login, signup, and logout
Responsive interface with model selection through the dashboard

Testing:
Testing for this project was done using Cucumber.js and Puppeteer to simulate real user interactions. These tests validate key functionality such as saving conversation history, searching conversations, sending prompts with multiple models, and general UI behavior.

To run the tests, use the following commands:
$env:NODE_ENV="test"
npm run test:cucumber

Development Approach:

For this project, I took on the roles of requirements engineering, development, and testing. I defined the core features and user flows, implemented both the frontend and backend, and created automated tests to verify functionality.

The backend was built using Node.js and Express, while the frontend was developed using HTML, CSS, and JavaScript.

The project followed an Agile development process, where features were implemented incrementally, tested continuously, and refined over multiple iterations. This allowed me to identify issues early and improve the system step by step rather than building everything at once.

Contributing:

This project was developed individually, but feedback and suggestions are welcome.

License:

This project was created for academic purposes.

Notes:

This project represents a complete development cycle, including planning, implementation, and testing, with a focus on building and validating a multi-LLM chat system.
