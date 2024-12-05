# Audio2Text and AI Image Generator: A Multimodal Chatbot


## **Project Description**


Audio2Text and AI Image Generator: A Multimodal Chatbot is an interactive web application that integrates advanced AI models to offer two primary functionalities: converting audio input into text and generating AI-powered images from text prompts. By leveraging OpenAI's Whisper model for speech-to-text conversion and the DALL·E model for image generation, this chatbot delivers a seamless and creative experience. Users can either speak or type their requests, and the application will process them accordingly, either transcribing speech into text or generating corresponding images based on user input.

This multimodal chatbot can be used for a variety of creative and accessibility-related tasks, including generating artwork from ideas, transcribing spoken content, and more.

## **Features**


- **Audio to Text**: Convert spoken words into text using OpenAI's Whisper model.
- **Text to Image:** Generate AI images based on text prompts with OpenAI's DALL·E model.
- **Interactive Chatbot:** A web-based interface to interact with the AI seamlessly.
- **Real-time Processing:** Instant transcription and image generation based on user input.



## **Technologies Used**

## **OpenAI API:**
- **Whisper Model:** For speech recognition, converting audio into text.
- **DALL·E Model:** For generating AI images from textual prompts.
## **Frontend:**
HTML, CSS, JavaScript (or React for more interactive UIs)
## **Backend:**
- **Node.js** (for creating the server-side logic, managing API calls, and handling user requests)
- **Web Audio API**: For capturing and processing audio input from users' microphones.


## **Concepts and Tools**


- **Speech Recognition:** Using OpenAI's Whisper model, this application is capable of transcribing spoken language into text.
- **AI Image Generation:** Leveraging OpenAI's DALL·E model to generate creative images based on user-provided descriptions.
- **RESTful API:** Built using Node.js and Express to handle HTTP requests and responses between the frontend and backend.
- **Web Audio API**: Used to capture and manage audio input from the user's microphone for real-time transcription.
  
## **How to Run the Project Locally**

- **Clone the repository:**
[git clone https://github.com/your-username/Audio2Text-AI-Image-Generator.git](https://github.com/DivyaMuruganIBM/Audio2Text-and-AI-Image-Generator-A-Multimodal-Chatbot.git)
- **Install dependencies:**
Navigate to the project directory and run the following command to install all the necessary dependencies:
npm install
- **Set up your OpenAI API key**:
Create a .env file in the root directory and add your OpenAI API key:
OPENAI_API_KEY=your-api-key
- **Start the server**:
Run the following command to start the application:
npm start
The application should now be accessible on http://localhost:3000. 
