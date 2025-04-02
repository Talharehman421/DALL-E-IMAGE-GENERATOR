# Custom Image Generator

This project is a Flask-based web application that generates images based on user-provided textual descriptions. It utilizes OpenAI's DALL·E 3 model to create AI-generated images from text prompts.

## Features
- Input a textual description and generate an AI-created image.
- Uses OpenAI's DALL·E 3 for high-quality image generation.
- Displays the generated image on a web interface.
- Provides an option to copy the image URL to the clipboard.
- Simple web interface built with Flask and Bootstrap.

## Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.x
- Flask
- OpenAI API access and API key

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Install dependencies:
   ```sh
   pip install flask boltiotai
   ```

3. Set up your OpenAI API key as an environment variable:
   ```sh
   export OPENAI_API_KEY='your-api-key-here'  # Linux/macOS
   set OPENAI_API_KEY='your-api-key-here'  # Windows (Command Prompt)
   ```

## Usage
1. Run the Flask application:
   ```sh
   python main.py
   ```
2. Open a web browser and go to:
   ```
   http://localhost:8080/
   ```
3. Enter a textual description and generate an image!

## API Endpoints
- `/` - Main page with form input.
- `/generate` - Backend API endpoint that processes user input and returns an image URL.

## Deployment
To deploy this project on a cloud server:
- Use services like AWS, Heroku, or Render.
- Set the `OPENAI_API_KEY` in the server environment.
- Ensure Flask is running on a public-facing IP.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
- Powered by [OpenAI](https://openai.com/)
- Flask framework for web development
- Bootstrap for styling

