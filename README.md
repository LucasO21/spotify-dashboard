---
editor: 
  markdown: 
    wrap: 72
---

## 🎵 Spotify Dashboard: EDM Punk Playlist 🎶

A dynamic dashboard showcasing Spotify's EDM Punk Playlist, previously
updated with GitHub Actions.

🚨 Important Notice

Due to recent
[changes](https://developer.spotify.com/blog/2024-11-27-changes-to-the-web-api)
in the Spotify API, certain endpoints (such as those used to fetch audio
features and tempo data) have been deprecated. As a result, this
dashboard is no longer able to fetch and display updated data.

However, the codebase remains a valuable resource for learning about:

- 🎯 Spotify API integration.

- 🛠️ Building dashboard with R and the gt packag.

- 🚀 Automating workflows with GitHub Actions.

------------------------------------------------------------------------

📝 Project Overview

This dashboard was designed to display detailed insights from Spotify's
EDM Punk Playlist, including:

🎵 Track Information: Song name, artist, album art, and popularity.

🕒 Track Duration: Represented visually using custom icons.

🥁 Tempo Variations: Visualized as a line plot for different sections of
each song.

🛠️ Technologies Use: - Programming Language: R - Packages: tidyverse,
httr2, gt - Workflow Automation: GitHub Actions - Data Source: Spotify
Web API

------------------------------------------------------------------------

📊 Features

🎨 Beautiful and Interactive Dashboard

-   Integrated Spotify track embedding to listen directly to songs.

-   Rich visualizations including:

    -   🎨 Popularity Heatmap: Generated with custom SVG circles,
        dynamically scaled based on Spotify popularity scores.
    -   🕒 Duration Formatting: Tracks displayed in minutes and seconds.
    -   🥁 Tempo Analysis: Visualized tempo variations for different
        song sections.

🔄 GitHub Actions for Automation

-   Automated the dashboard's updates by pulling playlist data via the
    Spotify API on a schedule.

-   Utilized the Spotify Client Credentials flow for token-based
    authentication.

------------------------------------------------------------------------

🤝 Acknowledgments

Special thanks to:

Melissa Van Bussel for inspiring this project. You can find her work
below:

-   [Spotify
    Dashboard](https://melissavanbussel.github.io/spotify-dashboard/dashboard.html).

-   [GitHub
    Repository](https://github.com/melissavanbussel/spotify-dashboard/tree/main).
