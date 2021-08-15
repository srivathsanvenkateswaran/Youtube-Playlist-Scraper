# Youtube-Playlist-Scraper
A Program that scrapes details about the given Youtube playlist

## Requirements
Selenium </br>
Firefox geckodriver </br>
Beautiful Soup </br>

## Usage

Clone the repository.
```
git clone https://github.com/srivathsanvenkateswaran/Youtube-Playlist-Scraper
```

Then navigate into the directory
```
cd Youtube-Playlist-Scraper
```
Create a directory with the name of data.
```
mkdir data
```
Create a python file. Inside your file,
```
import playlist_scraper as ps

PLAYLIST_URL = 'https://www.youtube.com/playlist?list=PLzMcBGfZo4-nK0Pyubp7yIG0RdXp6zklu'

ps.playlist_scraper(ps.playlist_id_from_link(PLAYLIST_URL))
```

Feel free to contact me in case of any doubts :)
