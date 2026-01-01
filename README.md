# Video to Word – Vibe Coding Experiment

A small Python utility vibe-coded to solve a real problem:
converting noisy lab videos into readable test documentation.

This script:
- Extracts one frame per second from a video
- Inserts frames into a Word document
- Adds timestamps above each image
- Generates a review-friendly `.docx` file in seconds

Built using **vibe coding** — intent first, implementation by AI.

---

## Prerequisites
- Python installed on your machine

---

## Install dependencies
```bash
pip install -r requirements.txt
```  
**## Run**

Place your video file in the project folder and run:

```bash
python video_to_word.py sample.mp4

```

## Output
The script generates:

- `video_frames.docx`
- One frame per second
- Timestamps above each frame



