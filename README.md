# TikTok-Timestamp-Extractor
A simple TikTok timestamp decoder for OSINT and metadata checking.

This project is a small Python script that helps you find out the exact upload time of a TikTok video.
It works by following the redirect of a TikTok share link, pulling the real video URL, and extracting the timestamp that TikTok hides inside the video ID. The script then shows the time both in your local timezone and in UTC.

The tool doesn’t use any TikTok API and doesn’t require tokens or accounts — just a link to the video.
There’s also support for multiple interface languages through simple language modules.

It can be useful for anyone who needs to check when a TikTok video was originally posted — whether for OSINT work, personal curiosity, or technical research.

Requirements are minimal: only Python 3 and the requests library.
