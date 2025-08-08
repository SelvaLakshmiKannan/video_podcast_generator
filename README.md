# 🎙️ AI-Powered Video Podcast Generator

This project is an AI-based system that generates a short 2–3 minute talk-show-style podcast video from a single-line topic. It automatically creates a script, generates voice audio using text-to-speech, adds visuals, and compiles everything into a video. The project is designed to run on **Google Colab** with no API key requirements.

---

## 🚀 Features
- Accepts a user-input topic
- Converts the script into audio using gTTS (Google Text-to-Speech)
- Adds images and visuals
- Produces a complete video using MoviePy

---

## 🛠️ How to Run

1. Open the notebook in **Google Colab**.
2. Run the cells in order.
3. Enter a topic when prompted.
4. Wait while the script, audio, images, and video are generated.
5. Download the final video output.

---

## 📦 Dependencies

Install the following Python packages (already handled in Colab if using `!pip install`):

```bash
!pip install gTTS moviepy pillow imageio imageio-ffmpeg

📚 What Each Package Does
gTTS: Google Text-to-Speech. Converts the generated script text into spoken audio in .mp3 format.

moviepy: A powerful video editing library. Used to combine audio, text, and images into a final video.

pillow: Python Imaging Library. Used for image creation, manipulation, and adding text on images.

imageio: Handles image and video file I/O operations, used by MoviePy internally.

imageio-ffmpeg: FFmpeg support for imageio, enables reading/writing video files.
