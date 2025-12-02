#  terminal Python Music Player 🎵

A simple command-line music player built using Python. I built this project following a tutorial to practice working with file handling and audio libraries.

## Overview
This program scans a local directory for MP3 files and creates an interactive playlist in your terminal. You can select songs to play and control playback directly from the command line.

## Features
- 📂 **Auto-Scan:** Automatically detects `.mp3` files in the `music` folder.
- 🔢 **Interactive Menu:** Select songs by typing their index number.
- ⏯️ **Playback Controls:**
  - `P` to Pause
  - `R` to Resume
  - `S` to Stop (and go back to the menu)
- 🚫 **Error Handling:** Gracefully handles missing files or invalid inputs.

## Prerequisites
You need Python installed on your machine. This project relies on the `pygame` library for audio handling.

1. **Install dependencies:**
   ```bash
   pip install pygame

 ### Add your music
1. Create a folder named `music` in the same directory as the script.
2. Drop your `.mp3` files into that folder.

## How to Use
Once the program is running:
1. You will see a list of your songs with numbers.
2. Type the **number** of the song you want to hear and hit Enter.
3. While listening, use the keys `P` (Pause), `R` (Resume), or `S` (Stop) to control the audio.
4. Press `Q` at the main menu to quit the application.
   
