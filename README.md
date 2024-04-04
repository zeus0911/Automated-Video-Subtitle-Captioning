# Automated Video Subtitle Captioning with Whisper AI

This project utilizes OpenAI's Whisper model to automatically generate subtitles for videos. It takes a video file as input, transcribes the audio content, and then overlays the generated subtitles onto the video. 
It utilizes Gradio library for building the user interface.

## Installation

You can install the required dependencies using pip:

```bash
pip install openai-whisper==20230117 gradio==3.41.2
```

## Usage

1. Run the main script.

2. Upload the original video file for which you want to generate subtitles.

3. Click the "Generate Subtitle Video" button.

4. The script will transcribe the audio, generate subtitles, and overlay them onto the video.

5. Once the process is complete, the subtitled video will be available for download.

The Gradio app may take time to generate the subtitle.


