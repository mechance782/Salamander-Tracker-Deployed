# Salamander Tracker Deployment
Developed by [Kim Mageary](https://github.com/kimageary) and [Madeleine Chance](https://github.com/mechance782)
## Overview
This repository contains everything needed to start using the Salamander Tracker application.

Salamander Tracker is a React web app that tracks salamanders with custom video processing software and saves the found locations to a CSV file. The application allows users to select a video to process, then colorpick a color from the video thumbnail, and choose a threshold level. These settings are what allows the software to locate and track the target. The user can tell if their inputs are valid via the preview thumbnail, which displays what areas of the video are highlighted (and then tracked).

## Getting Started
> **Before Anything:** <br>
> Make sure you have **Docker** installed on your machine. <br>
> If it's not, download it [here](https://www.docker.com/get-started/)

- Once Docker is installed, you will start by cloning this repository.
- After cloning the repository to your machine, you will want to open your terminal, and navigate to the repository folder.
- Now, in the terminal you will run this command:
```bash
VIDEO_DIR="$Video-Folder" docker compose up
```
(Note that **$Video-Folder** should be replaced with an absolute path to a folder of mp4 videos on your machine.)

- After running the command, the Salamander Tracker app will be located here: [http://localhost:3001](http://localhost:3001)
- Now you're ready to process some salamander videos! Feel free to add more mp4 files to your video folder, the app will detect them and make them avaliable for processing.
   
