# Playlist Bot

Discord Bot that automatically adds Spotify links to a playlist.

## Setup

```bash
cp example.env > .env
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Fill out the .env file with the correct credentials.

If you have multiple channels, they should be separated with `,`.

Example: `CHANNELS=123,456,789`

## Run

```
python -m playlist
```
or using Docker

```
docker-compose build
docker-compose up
```

