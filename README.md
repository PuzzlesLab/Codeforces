Codeforces
============

This repo is to store answers of Codeforces questions.

If you are interested in Codeforces, please visit [here](https://codeforces.com/)

## Updates

## Notes

+ How to start (ONLY FOR THOSE WHO USE COMMAND LINE):
   ```
   $ git clone https://github.com/PuzzlesLab/Codeforces
   ```

+ How to update this repo (if you are one of the team) [__UPDATE SOURCE CODE ONLY__]:
   + (assume you've cloned this repo)
   + Pull all changes first
   
      ```
      $ git pull origin master
      ```
   + Make your changes (DO NOT TOUCH OTHER'S CODE)
   + Commit your changes
   
     ```
     $ git add -A
     $ git commit -m "<your message>"
     ```
   + Push your commit
   
     ```
     $ git push origin master
     ```

+ How to write and use a shell script for updating repo (For command line only) [This little tool will create unique commit description and leave others changes alone:
   + Write a shell script for updating repo (assume your script is `update-<yourname>.sh` [e.g. `update-duguyue100.sh`])
     ```
     git pull origin master
     
     now="$(date): update all by <yourname>"
     
     git add -A README.md
     git add -A <your-folder>/*
     git add -A update-<yourname>.sh
     
     git commit -m "$now"
     
     git push origin master
     ```
     Copy above code to `update-<yourname>.sh`.
   + Use a shell script for updating repo
   
     ```
     $ sh update-<yourname>.sh
     ```

## Contacts

Puzzles  
Email: amy.theia.knuth@gmail.com
