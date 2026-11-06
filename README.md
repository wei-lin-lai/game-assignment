# Guess the Movie

Players answer 30 questions from film stills and clues.

The ending song is made with Google's Lyria 3 music model.

## How to play

1. Type your name and press **Start**.
2. Each question shows a movie screenshot or a clue, with 4 options. Click the right movie.
3. A right answer gives 1 point. A wrong answer shows the right answer in red, then the next question starts.
4. After 30 questions, the game shows your name and score, and plays an ending song:
   - 0 to 10 right: a mocking song
   - 11 to 20 right: a congratulations song
   - 21 to 30 right: a heavenly "legendary" song
5. The next player types a new name and presses **Play again**.

## Screenshots and clues

Each question is picked at random. About 4 out of 5 questions show a film still, and about 1 out of 5 shows a written clue. It does not depend on right or wrong answers. If a film still can not be downloaded, that movie always gets a clue.

## Setup

A Google Cloud service account key file is needed to use Lyria. Put it at `keys/service.json`. This file is not in the repo, because the `keys/` folder is in `.gitignore`.
