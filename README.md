# Audio to Text Summarization

## Overview

This project converts audio files into concise text summaries using machine learning and natural language processing techniques. It leverages Whisper for transcription, spaCy for sentence segmentation, and TF-IDF for key sentence extraction, providing clear and coherent summaries of spoken content.

## Features

- Audio transcription using Whisper
- Text cleaning and processing
- Sentence segmentation with spaCy
- TF-IDF vectorization for key sentence extraction
- Concise summary generation

## Requirements

- Python 3.x
- Whisper
- spaCy
- scikit-learn
- numpy
- TextBlob
- nltk

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/audio-to-text-summarization.git
   cd audio-to-text-summarization
   ```

2. Install the required libraries:
   ```sh
   pip install whisper spaCy scikit-learn numpy textblob nltk
   ```

## Usage

1. Open the Jupyter notebook `T2_S2T+Cleaning+TF_IDF.ipynb`.
2. Run all cells to process the example audio file and generate a summary.
3. To use your own audio file, replace `audio.mp3` with your file name in the transcription cell:
   ```python
   name = 'your_audio_file.mp3'
   ```

## Project Structure

- `T2_S2T+Cleaning+TF_IDF.ipynb`: Main notebook with code for transcription, processing, and summarization.
- `audio.mp3`: Example audio file used for testing.

## Future Work

- Improve summarization accuracy and coherence.
- Add support for multiple languages.
- Develop a user-friendly interface for easier audio uploads and summary retrieval.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

For questions or suggestions, please open an issue or contact pathaktanmay98@gmail.com.

---

Feel free to customize the sections to match your project's specifics and preferences.
