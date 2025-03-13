# MuJo: Multimodal Joint Feature Space Learning for Human Activity Recognition

This repository contains the data for the paper "MuJo: Multimodal Joint Feature Space Learning for Human Activity Recognition".

## Repository Structure

The repository is organized into the following directories:

- `data/`: Contains the most important data files of the FiMAD dataset used in this project.
  - `youtube_links.txt`: A list of YouTube links to the 1388 videos used in this study.
  - `train_val_split.json`: Text file containing the train and validation video IDs used for training our MuJo models. Video IDs follow the format $youtubeID___$chapterID, where $youtubeID is the YouTube ID of the video and $chapterID specifies the chapter within that video.
  - `language_data.json`: A JSON file mapping each video ID to its chapter, normalized chapters, subtitles, and descriptions generated with GPT-3.5 Turbo.
  - **To obtain full access to the FiMAD dataset, please send an email to stefan_gerd.fritsch@dfki.de.**

- `src/`: Coming soon ...
