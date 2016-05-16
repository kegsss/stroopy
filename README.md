# Stroopy
A simple Stroop Task programmed using PsychoPy

## Instructions
- [x] Swedish
- [x] English


Instructions (both English and Swedish) are found in the file "INSTRUCTIONS". This file is read and parsed by some
functions. The set up of the functions is that Swedish - SwedishEnd words will mark where the swedish instructions are.
The words ending with START and END marks where the scripts (i.e., the functions) will find instructions:

- instructions - The instructions on how to perform the task - the first that will show
- practice - How to start the experiment (i.e., press SPACE) - the first that will show (on the bottom of the screen
- test - After practice trials - informing that the test part starts and questions should be asked now
- done - Telling participants that the experiment is done

## Stimuli
- [x] English (Not tested, yet)
- [x] Swedish (translated in the script)
- [] More languages?

Feel free to contribute with other languages.

As for now to add more languages add a language in the list on line 21 (['Swedish', 'English']). After this is done
you need to follow how the INSTRUCTIONS file is set-up (as described above).
