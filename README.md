# English Accent Analyzer

Analyze English accents from video interviews with ease.

## Features

- Accepts direct MP4 video URLs or file uploads
- Extracts audio from video files
- Transcribes speech to text using Google's Speech Recognition API
- Detects and classifies English accents (American, British, Australian, Indian, Canadian)
- Provides confidence scores for accent detection
- Displays accent characteristics, explanations, and vocabulary markers
- Interactive and user-friendly Streamlit interface

## Supported Accents

- American English
- British English
- Australian English
- Indian English
- Canadian English

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/kennedy-273/Accent-Analyzer.git
    cd Accent-Analyzer
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Start the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

2. **Open your browser:**  
   Visit [http://localhost:8501](http://localhost:8501) (or the URL shown in your terminal).

3. **Analyze an accent:**
   - Enter a direct MP4 video URL, upload a video file, or use demo data.
   - Click **"Analyze Accent"** to process the video and view results.

## Demo

Try the live demo:  
[https://accent-analyzer-j6grkhdz4igjatn4qu9tj8.streamlit.app/](https://accent-analyzer-j6grkhdz4igjatn4qu9tj8.streamlit.app/)

**Tip:**  
To test with your own video, pick a short video from YouTube, then go to [ytmp3.cc](https://ytmp3.cc/5Hcs/) and convert it to MP4. Use the resulting MP4 link or file in the app.

## How It Works

- **Video Input:** Accepts direct MP4 links or file uploads.
- **Audio Extraction:** Extracts audio from the video using MoviePy.
- **Speech Recognition:** Converts audio to text via Google's Speech Recognition API.
- **Accent Analysis:** Uses linguistic markers, vocabulary, and phrases to classify the accent.
- **Results:** Displays detected accent, confidence score, and characteristic details.

## Deployment

Deploy easily to Streamlit Cloud:

1. Push your code to GitHub.
2. Sign in to [Streamlit Cloud](https://streamlit.io/cloud).
3. Create a new app and point it to your repository.
4. Set the entry point to `app.py`.

## Limitations

- Only supports direct MP4 URLs for video input.
- Accuracy depends on audio quality and clarity.
- Detects a limited set of English accents.
- Demo mode provides simulated results for testing.

## Future Improvements

- Support for more video sources (e.g., YouTube, Vimeo)
- Integration with advanced ML-based accent classification
- More granular regional accent detection
- Real-time/live interview analysis
- Customizable vocabulary and phrase detection

## License

MIT License