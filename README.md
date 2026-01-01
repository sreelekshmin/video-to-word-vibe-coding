# Video to Word – Vibe Coding Experiment

A small Python utility built using **vibe coding with Cursor** to convert noisy lab videos into readable test documentation.

## 🧠 What is vibe coding?
Vibe coding is an intent-first way of building software:
- You describe the outcome
- AI handles the implementation
- You fix only what blocks execution

This experiment follows that approach end to end.

## 🎯 Problem
In a data lab setup, noisy videos of a physical clock device must be reviewed to create test documents.  
Manual review is time-consuming, error-prone, and hard to scale.

This script automates that process.
---

## 🧑‍💻 Vibe Coding with Cursor (From setup to prompt)

This script was built using **vibe coding with Cursor**, an intent-first way of writing code with AI assistance.

### 1️⃣ Install Cursor
Download and install Cursor from:
https://cursor.com/


---

### 2️⃣ Create a project folder
Create an empty folder anywhere on your machine, for example:
video-to-doc

This folder represents a fresh experiment with no pre-defined structure.

---

### 3️⃣ Open the folder in Cursor
- Open Cursor
- Go to **File → Open Folder**
- Select the project folder
- Trust the folder when prompted

Opening the folder gives Cursor full context of the project.

---

### 4️⃣ Create a single Python file
Inside the folder, create one file:
video_to_word.py


No boilerplate or setup is required.

---

### 5️⃣ The vibe coding step (Prompting)
- Click inside `video_to_word.py`
- Press **Ctrl + K**
- Describe the intent in plain English, for example:
 Write a Python script that:
- Takes a video file path as input
- Extracts one frame per second
- Creates a Word document
- Inserts each frame in order
- Adds timestamp above each image
- Saves the output as video_frames.docx


### 6️⃣ Run and iterate

Run the script
If an error appears, paste the error back into Cursor
Ask it to fix only what blocks execution
Run again
This loop continues until the script works as expected. It worked for me in the first trial.

## ✅ What this script does

- Takes a video file as input
- Extracts **one frame per second**
- Inserts frames into a Word document
- Adds a timestamp above each image
- Generates a review-friendly `.docx` file

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



