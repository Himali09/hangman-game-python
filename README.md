# Hangman Game in OpenCV

**This repository contains the code for the Hangman game implemented using OpenCV, based on the [Hangman: Creating games in OpenCV](https://learnopencv.com/hangman-creating-games-in-opencv/) blog post.**

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/q5xa2wiv8a93aps/AADZyd3Wf11qzDMSCT03yjnPa?dl=1)

## Overview

This repository provides the code implementation for the Hangman game using OpenCV. The game challenges players to guess a hidden word by suggesting letters. It utilizes various features of OpenCV to create an interactive and engaging gaming experience.

## Game Outline

1. Data Preprocessing:
   - Utilize the **pandas** library to process the **IMDb database**.
   - Remove irrelevant columns and filter out non-English movie titles.
   - Prepare a clean dataset for the game.

2. Game Initialization:
   - Read the cleaned dataset and store it in a dictionary format: `movie_title:[year, list of keywords, tagline, director, list of cast]`.

3. Gameplay:
   - Select a random movie and display a hangman template.
   - Choose three features from the movie's details to provide hints.
   - Allow players to guess characters and update the hangman display accordingly.
   - Determine the game outcome based on the player's guesses.

4. End of Game:
   - Reveal the movie name and prompt the user to press a key to quit.

## Instructions

To play the Hangman game, execute the following command:

```bash
python main.py
