# TikTok Video Timestamp Extractor

A small Python tool that determines the exact upload time of a TikTok
video.

The script follows the redirect from a TikTok share link, retrieves the
real video URL, and extracts the timestamp embedded in the video ID. It
then shows the upload time in both your local timezone and UTC.\
No TikTok API, no tokens, no login --- just a link to the video.\
The tool also supports multiple interface languages through simple
language modules.

This can be helpful for OSINT work, technical analysis, or simply
checking when a video first appeared online.

------------------------------------------------------------------------

## Requirements

-   Python 3
-   `requests` library

Install dependencies:

``` bash
pip install requests
```

------------------------------------------------------------------------

## Usage

Run the script and paste a TikTok share link (for example the one copied
from the app):

    https://vt.tiktok.com/ZSfXTxq8F

Example output:

    ====================
    == Account:  dragonstarszn
    == Day:     26
    == Month:   February
    == Year:    2021
    == Time in current timezone:  05:10:56
    == Time in Greenwich (UTC):   02:10:56
    ====================

    Press Enter to exit...

------------------------------------------------------------------------

## Language Selection

When starting the script, choose the interface language (e.g., albanian,
arabic, belarusian, bulgarian, catalan, etc.).\
Default: **english**.

------------------------------------------------------------------------

## License

This project is licensed under the MIT License.\
[View
License](https://github.com/SakuraSquirrelLab/TikTok-Timestamp-Extractor/blob/main/LICENSE)
