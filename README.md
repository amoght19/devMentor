# DevMentor

DevMentor is an open-source chatbot platform designed to assist users with coding-related questions and provide helpful answers. It serves as a friendly virtual mentor for developers, offering guidance and solutions to coding challenges.

## Features

- Ask coding-related questions and receive helpful answers
- Get assistance with various programming languages and frameworks
- Benefit from the knowledge and expertise of an AI-powered chatbot
- No user authentication required, making it user-friendly
- Easy-to-use interface for a seamless chat experience

## How to Use

1. Open the DevMentor website or application.
2. Type your coding-related question in the chat interface.
3. Submit the question to receive an AI-generated response.
4. Engage in a conversation with devMentor to clarify doubts or ask follow-up questions.
5. Explore the provided solutions or explanations to understand coding concepts better.

## Technologies Used

- Node.js
- Express.js
- Text (text-davinci-003 OpenAi language model)
- HTML/CSS
- JavaScript

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/amoght19/devMentor.git
   ```

2. Navigate to the project directory:
    ```bash
    cd devMentor
    ```

3. Install the dependencies for the server:
    ```bash
    cd devMentor/server
    npm install
    ```
4. Set up the environment variables:
    Create a .env in /server folder
    ```bash
    OPENAI_API_KEY=<Your OpenAi key>
    ```
    Replace <Your OpenAi key> with your api key.

5. Start your server
    ```bash
    npm run server
    ```

6. Install dependencies for client:
    ```bash
    cd ../client
    npm install
    ```
7. Start yor Ai chatbot
    ```bash
    npm run dev
    ```
8. Open your web browser and navigate to http://localhost:5173 to access devMentor.




## Demo

https://dev-mentor-pemuks8bz-amoght19.vercel.app/




## Contributing

Contributions are always welcome!
If you find any bugs or have suggestions for improvements, please open an `issue` or submit a `pull request`.
