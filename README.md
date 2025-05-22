# English Accent Analyzer

A tool for analyzing English accents from video interviews, built for REM Waste's hiring process.

## Features

- Accepts video URLs (direct MP4 links) or file uploads
- Extracts audio from videos
- Transcribes speech to text
- Analyzes and classifies English accents
- Provides confidence scores for English proficiency
- Displays accent characteristics and explanations

## Supported Accents

- American English
- British English
- Australian English
- Indian English
- Canadian English

## Installation

1. Clone this repository:
```
git clone https://github.com/your-username/english-accent-analyzer.git
cd english-accent-analyzer
```

2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install the required packages:
```
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:
```
streamlit run app.py
```

2. Open the app in your browser (default: http://localhost:8501)

3. Enter a video URL (MP4 link), upload a video file, or use the demo data

4. Click "Analyze Accent" to process the video and see results

## Demo

For quick testing, check out the live demo at:
[https://accent-analyzer-demo.streamlit.app/](https://accent-analyzer-demo.streamlit.app/)

## Technical Details

- Speech recognition powered by Google's Speech Recognition API
- Accent analysis based on linguistic patterns and markers
- Built with Python and Streamlit for easy deployment
- Processes include:
  - Video download and audio extraction
  - Speech-to-text transcription
  - Natural language processing for accent detection
  - Confidence scoring algorithm

## Deployment

The app can be easily deployed to Streamlit Cloud:

1. Push your code to GitHub
2. Sign in to [Streamlit Cloud](https://streamlit.io/cloud)
3. Create a new app pointing to your repository
4. Configure the app to run `app.py`

## Limitations

This demo version has some limitations:
- Only supports direct MP4 URLs for video inputs
- Performance depends on audio quality and clarity
- Limited number of English accents detected
- Demo mode shows pre-configured results for testing

## Future Improvements

- Support for more video sources (YouTube, Vimeo, etc.)
- Integration with sophisticated ML accent classification models
- More detailed accent analysis with regional specificity
- Real-time analysis for live interviews
- Custom vocabulary and phrase detection

## License

MIT License