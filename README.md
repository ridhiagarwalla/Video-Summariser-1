# Video Summarizer

This Python script allows you to summarize the content of a YouTube video using speech-to-text transcription and text summarization techniques.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Required Python packages:
  - `pytube`
  - `librosa`
  - `soundfile`
  - `huggingsound`
  - `torch`
  - `transformers`

You can install the required dependencies using the following command:

```bash
pip install pytube librosa soundfile huggingsound torch transformers
Usage
Steps:
Clone the repository or download the script file.

Open the script in your preferred Python environment (e.g., Jupyter Notebook, Google Colab).

Set the VIDEO_URL variable to the URL of the YouTube video you want to summarize.

Run the script. It will perform the following steps:

Download the audio from the YouTube video.
Convert the audio to WAV format.
Transcribe the audio to text using a pre-trained speech recognition model.
Summarize the text using text summarization techniques.
Output the summarized text.
Example
python
Copy code
VIDEO_URL = 'https://www.youtube.com/watch?v=h-JVjs9AAmQ'  # Example video URL
Output
The summarized text will be printed in the output of the script.

Contributors
Vinayak Gupta
Ridhi Agarwalla
Bhumika Roy
