# Streamer.bot Auto-Welcome and Auto-Shoutout
Code for Streamer.bot Question of the Day System

## Install Instructions:

 1. Download both of these files.
 2. Place "QuestionOfTheDay.txt" somewhere safe, as this is the file to
    hold your random questions. This comes pre-loades with around 40 questions. Feel free to edit it and add more. Get creative and make it your own!
 3. Import "QuestionOfTheDay.sb" into Streamer.bot
    (Click the import button and drag the file to the top section of the
    import dialog box).
 4. On your Actions tab, look for the "QOTD Init" Action and edit
    the "Read Random Line" sub-action to point to the folder you put
    "QuestionOfTheDay.txt".
 5. Lastly, go to your Commands tab and enable the following two commands: "!initqotd" and "!questionoftheday"

At the start of every stream, while you're getting ready, make sure you run "!initqotd" which will pull a random question fro mthe text file and store it in a variable. Whenever you want the question to be displayed, simply run !questionoftheday or !qotd and it wil display the question in chat. Whenever it's time to use a new question (next stream, maybe, or if it picked a duplicate), simply re-run "!initqotd" and a new question will be pulled and stored.

This is a very simple system and has no duplicate protection or anything fancy like that. You're free to expand on this if you like. Anyway, that's all there is to it! Happy streaming!
