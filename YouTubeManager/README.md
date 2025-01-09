# YouTube Manager


<img src="readme-images/youtube_manager_logo.jpg" alt="YouTube Manager Logo" style="max-height: 400px;">

## Description
YouTube Manager is a console application that simplifies playlist management and tracks historical data.


**Application offers the following functionalities:**
- **Sync Playlists with a Database**

    Keep YouTube playlists synchronized with a local database to ensure data consistency.

- **Track Video and Channel Changes**

    Maintain a history of changes to video titles and channel names. This is particularly useful for identifying videos that become private or unavailable, as it records their details before they are inaccessible.

- **Export Video Links**

    Export all video links—or only newly added ones—to a .txt file, making it easy to download videos or MP3s using external software.

- **Import and Mark Links as Downloaded**

    Import a list of downloaded video links and mark them as downloaded to easily identify newly added videos that haven’t been downloaded yet.

- **Compare Playlists**

    Analyze differences between playlists to identify videos that are missing from the target playlist. This helps in deciding whether to add them.


## Technology & Tools used
- Python `3.10`
- SQLAlchemy
- MySQL
