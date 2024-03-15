# StartupAssist

### Overview

This project is aimed at assisting startups with information about government schemes using a chatbot interface. The chatbot is built using the Assistant API and is integrated into a streamlit web application.

### Test the app here: 

[https://startupassist.streamlit.app/](https://startupassist.streamlit.app/)

Download raw and view demo here:

[https://github.com/KilariHarthik/StartupAssist/blob/main/Screen%20Recording%202024-03-15%20at%2013.10.39.mov](https://github.com/KilariHarthik/StartupAssist/blob/main/Screen%20Recording%202024-03-15%20at%2013.10.39.mov)


### File Structure

- **.streamlit/**: Contains configuration files for Streamlit.
- **secrets.toml**: File for storing sensitive information securely. (Not included in the public repository)
- **README.md**: Markdown file providing an overview of the project.
- **app.py**: Python file containing the code for the Streamlit web application.
- **myvideo.mp4**: Video file generated using Vidnoz AI tool, for a demo and instructional video.
- **requirements.txt**: File listing the Python dependencies required for the project.

### Setup

1. **Clone the Repository**: Clone the repository to your local machine using Git:

   ```
   git clone <repository_url>
   ```

2. **Create secrets.toml**: You need to create a `secrets.toml` file in the root directory of the project to store sensitive information such as API keys. This file should not be committed to version control and should be kept secure.

   ```
   # Example structure of secrets.toml
   [api]
   openai_apikey = "YOUR_API_KEY"
   assistant_id = "YOUR_API_KEY"
   ```

3. **Install Dependencies**: Install the required Python dependencies using `pip`:

   ```
   pip install -r requirements.txt
   ```

### Usage

1. **Run the Streamlit App**: Start the Streamlit web application by running the following command in your terminal:

   ```
   streamlit run app.py
   ```

2. **Interact with the Chatbot**: Once the application is running, you can interact with the chatbot interface to get information about government schemes for startups.

### Additional Notes

- **Assistant API Integration**: Ensure that you have obtained the necessary API key for the Assistant API and stored it securely in the `secrets.toml` file. From https://platform.openai.com
- **Customization**: You can customize the chatbot's behavior, responses, and appearance by modifying the code in `app.py`.
- **Demo Video**: Refer to `myvideo.mp4` for a demo or instructional video if available. If not available, you may want to create one to demonstrate the functionality of the application.

### Support and Contributions

For any issues, questions, or feedback, please open an issue on the GitHub repository. Contributions via pull requests are welcome.

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
