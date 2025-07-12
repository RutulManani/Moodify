# Moodify - Music Mood Analyzer

## 1. Project Overview
Moodify is an interactive web application that leverages music to match users' emotions. By combining Spotify's music catalog with song lyrics, Moodify creates a seamless experience for users to discover music tailored to their current mood.

### Key Features
- **Mood-Based Recommendations**: Users input an emotion (e.g., "happy," "melancholic") to receive curated song suggestions.
- **Lyrics Integration**: Display lyrics alongside songs for deeper engagement.
- **Minimalist UI**: Clean, intuitive design focused on usability.

## 2. APIs & Data Sources

| API | Purpose | Documentation |
|-----|---------|---------------|
| Spotify Web API | Fetch songs/playlists by mood | [Spotify API Docs](https://developer.spotify.com/documentation/web-api) |
| Lyrics.ovh API | Retrieve lyrics for recommended songs | [Lyrics.ovh Docs](https://lyricsovh.docs.apiary.io/#reference/0/lyrics-of-a-song/search) |

## 3. MVP Scope

### Core Features
✅ Mood input → Song recommendations (Spotify API)  
✅ Lyrics display (Lyrics.ovh API)  

### Single-page application with:
- Mood input field
- Results display showing:
  - Song cards (title, artist, album art)
  - Lyrics section
- Basic styling and responsive layout

### Pages:
- **Main Page** (only page for MVP)
  - Input form
  - Results display
