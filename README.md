## MP3 Player
A simple command-line MP3 player written in Python, using the audio mixer built into pygame.

## Features
- Lists every .mp3 file found in Music_Folder
- Plays a song by its number in the list
- Pause, resume and stop controls while a song is playing

## Setup
- Install the dependencies:
```bash
pip install -r requirements.txt
```
- Put your own .mp3 files into the Muisc_Folder. No music is included in this repository.
- Start the player from inside the project folder:
```bash
python mp3_main.py
```

## Usage
```bash
**** MP3 PLAYER ****
My song list:
1. first_song.mp3
2. second_song.mp3

Enter the song # to play (or 'Q' to quit): 1

Now playing: first_song.mp3
Commands: [P]ause, [R]esume, [S]top
```