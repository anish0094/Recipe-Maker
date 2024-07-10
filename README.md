# Recipe Maker

Recipe Maker is a web application that generates recipes based on user inputs such as ingredients, cooking time, maturity level, and preferred cuisine type. This project leverages the power of Generative AI through the ChatGPT API and is built using Node.js.

## Features

- **User Inputs:** Users can input ingredients, cooking time, maturity level, and preferred cuisine type.
- **AI-Powered Recipe Generation:** The application uses the ChatGPT API to generate recipes based on the user inputs.
- **Customizable Recipes:** Recipes are tailored to the user's preferences and available ingredients.
- **User-Friendly Interface:** Easy-to-use web interface for recipe creation.

## Technologies Used

- **Node.js:** Backend framework for building the web application.
- **Express.js:** Web framework for Node.js to handle routing and middleware.
- **ChatGPT API:** AI model used to generate recipes based on user inputs.
- **HTML/CSS/JavaScript:** Frontend technologies for building the user interface.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/anish0094/Recipe-Maker.git
    cd recipe-maker
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add your ChatGPT API key:
    ```env
    CHATGPT_API_KEY=your_api_key_here
    ```

4. Start the application:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to use the application.

## Usage

1. **Input Ingredients:** Enter the ingredients you have available.
2. **Specify Cooking Time:** Provide the amount of time you have to cook.
3. **Select Maturity Level:** Choose your cooking skill level (e.g., Beginner, Intermediate, Expert).
4. **Choose Cuisine Type:** Select your preferred cuisine type (e.g., Italian, Chinese, Mexican).
5. **Generate Recipe:** Click on the "Generate Recipe" button to receive a recipe tailored to your inputs.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request


## Acknowledgements

- [OpenAI](https://www.openai.com/) for providing the ChatGPT API
- [Node.js](https://nodejs.org/) for the backend framework
- [Express.js](https://expressjs.com/) for the web framework

## Contact

If you have any questions or feedback, please contact me at `anish.fc0094gmail.com`.

---

Happy cooking!
