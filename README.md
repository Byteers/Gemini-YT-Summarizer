# YouTube Transcript to Detailed Notes Converter

This project is a Streamlit web application that converts YouTube video transcripts into detailed notes using a generative AI model. The application takes a YouTube video URL as input, fetches the video's transcript, summarizes the transcript, and displays the summary.

## Features

- Input a YouTube video URL
- Fetch and display the video's thumbnail
- Extract the transcript of the video
- Generate a summary of the transcript using a generative AI model
- Display the summarized notes

## Requirements

- Python 3.7+
- Streamlit
- dotenv
- google-generativeai
- youtube-transcript-api

## Installation and Setup

### 1. Clone the Repository


git [clone](https://github.com/Byteers/Gemini-YT-Summarizer.git)
cd Gemini-YT-Summarizer


### 2. Create and Activate a Virtual Environment

#### On Windows:


python -m venv venv
venv\Scripts\activate


#### On macOS/Linux:


python3 -m venv venv
source venv/bin/activate


### 3. Install Dependencies


pip install -r requirements.txt


### 4. Set Up Environment Variables

Create a `.env` file in the root directory of the project and add your Google API key:


GOOGLE_API_KEY=your_google_api_key


### 5. Run the Streamlit App


streamlit run app.py


## How to Use

1. Open the web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).
2. Enter the YouTube video link in the provided input box.
3. Click on the "Get Detailed Notes" button.
4. The video thumbnail will be displayed, and the summarized notes will be generated and shown below.

## File Structure

├── app.py
├── requirements.txt
└── .env


- `app.py`: The main application file.
- `requirements.txt`: Contains the list of dependencies.
- `.env`: Environment variables file (not included in the repository, needs to be created).


## Dependencies


## License

This project is licensed under the MIT License. See the LICENSE file for details.


### Steps to Run the Program with `venv`

1. **Clone the Repository**: Download the project code from the repository.

   git [clone](https://github.com/Byteers/Gemini-YT-Summarizer.git)
   cd Gemini-YT-Summarizer
   

2. **Create a Virtual Environment**:

   ###On Windows:
   
   python -m venv venv
   venv\Scripts\activate
  

   ##On macOS/Linux:

   python3 -m venv venv
   source venv/bin/activate
 

3. **Install Dependencies**: Install the necessary libraries using `pip`.

   
   pip install -r requirements.txt
  

4. **Set Up Environment Variables**: Create a `.env` file in the root directory and add your Google API key.

   
   GOOGLE_API_KEY=your_google_api_key
   

5. **Run the Streamlit App**: Start the Streamlit application.

  
   streamlit run app.py
  

6. **Use the Application**: Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`). Enter the YouTube video link and click "Get Detailed Notes" to see the summarized notes.

