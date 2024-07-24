# Spotify Playlist Generator

This is a command-line tool that generates a Spotify playlist based on a user prompt using OpenAI and Spotify APIs.

## Features

- Generate a playlist based on a text prompt.
- Add generated songs to your Spotify account.
- Future plans to create a web app interface.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/spotify-playlist-generator.git
cd spotify-playlist-generator
```
2. Create and activate a virtual environment:
```bash
python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
4. Create a .env file in the root directory and add your environment variables:
```bash
OPENAI_API_KEY=your-openai-api-key
SPOTIPY_CLIENT_ID=your-spotify-client-id
SPOTIPY_CLIENT_SECRET=your-spotify-client-secret
```

## Usage

Run the script with the required arguments:
```bash
python app.py -p "songs for a rainy day" -n 5
```
-p: The prompt describing the playlist.
-n: The number of songs to be added (default is 12)

## Future Plans
Develop a simple web app interface using Flask, HTML, CSS, and JavaScript.

## License
This project is licensed under the MIT License. See the <a href="https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt">LICENSE file</a> for details.



