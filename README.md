# Kadr TV / Кадр TV

A personal, non-commercial Android TV / Google TV application for browsing films and TV series, saving favorites, and opening selected video files in VLC through a local TorrServer instance.

This repository is the public project information page. The application is an early personal-use prototype; source code and APK releases are not published here.

## Current prototype

- Remote-control-friendly interface for Android TV and Google TV (Android 8.0+).
- RuTor torrent search with text suggestions and pagination.
- Local favorites for individual releases.
- Video-file selection through a user-configured TorrServer instance.
- Playback in the separately installed VLC application.
- No advertising or analytics SDKs.

Search availability depends on the selected source and the user's network. Device testing is ongoing.

## Planned movie and TV cards

TMDB integration is planned, but is not yet implemented or approved. The intended use of the TMDB API is to retrieve movie and TV show titles, original titles, release dates, descriptions, and poster images for display in the application.

The first stage will add:

- Movie and TV search with posters and release years.
- A shared title-details screen, separate from individual torrent releases.
- Local favorites for movies and TV shows.
- An action that searches the separate RuTor source for releases of the selected title.

TMDB would provide metadata and images only. Torrent search and playback use separate integrations. The project is not endorsed by or affiliated with TMDB. Required TMDB attribution will be included when the integration is added.

## Data and playback

The project does not host or distribute video files. TorrServer and VLC are separate applications installed and configured by the user. Current favorites and application settings are stored locally on the device. Search and playback requests are sent to the corresponding configured services.

## О проекте

«Кадр TV» — личное некоммерческое приложение для Android TV / Google TV с управлением пультом. Сейчас доступны поиск раздач RuTor, избранные раздачи, выбор видеофайла через TorrServer и запуск VLC.

Следующий этап — общие карточки фильмов и сериалов: постер, название, год, описание и избранное. Для этих данных планируется подключить TMDB. Интеграция пока не реализована. Поиск раздач и воспроизведение останутся отдельными функциями.

Эта страница описывает проект; исходники и установочные файлы здесь не публикуются.