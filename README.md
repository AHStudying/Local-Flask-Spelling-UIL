# Local-Flask-Spelling-UIL

**This is the localhost development version! Use [Flask-Spelling-UIL](https://github.com/AHStudying/Flask-Spelling-UIL)**

This is a project to help you study for Spelling UIL. It allows you to select what section you can study (or you can study all of the words at once) and randomly picks 70 words from that selection. It has two different voices that you can use to pronounce the words. To play the first pronunciation, press **shift + enter**. Type in how you think it's spelled, and then press enter. It will give feedback if you get it wrong.

## Features

- Select what set of words you want to study
- Live scoring
- Two different voices for pronunciation
- Immediate feedback for what you get wrong

## Screenshots

![App Screenshot](https://i.imgur.com/i2IpqrN.png)
![App Screenshot](https://i.imgur.com/aCtIDmg.png)

## FAQ

#### Why is this separate from Flask-Spelling-UIL?

~~The reason that this is separate from regular Flask-Spelling-UIL is because that one is currently broken. This is the one that works, but it only works on my localhost. The reason it doesn't work on online hosting currently is because they are serverless functions, and don't use Windows. That immediately broke pywin32 and pypiwin32, but that was okay, that was fixable. The issue I ran into was with a library called 'pygame'. Pygame evidently doesn't like being run serverless because it immediately threw errors that I couldn't seem to fix. I tried lots of other libraries but still can't seem to get it to actually play audio on the browser aside from just~~

This is the localhost version. I figured out how to fix the other version.

## Badges


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Authors

- [@Calc-oholic](https://www.github.com/Calc-oholic)
- [@A-Singh-er](https://www.github.com/A-Singh-er)
