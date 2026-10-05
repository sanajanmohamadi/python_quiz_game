
# Python Quiz Game

![Static Badge](https://img.shields.io/badge/python-3.12-pink)

A simple quiz game built with Python

## Table of contaxt
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Example Output](#example-output)
- [screenshot](#screenshot)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Licence](#licence)
- [Author](#author)

## Features

- Quiz System
  - Asks the player multiple questions 
  - Checks if the password is correct
  - Keeps the private information outside the main Python file
  - Loads the password from `.env`
  
## Project Structure

## Project Structure

```text
python_quiz_game/
│
├── .env.example
├── .gitignore
├── main.py
├── question.py
├── README.md
├── requirements.txt
│
├── gifs/
│   └── demo.gif
│
└── pictures/
    ├── 1.png
    ├── 2.png
    └── 3.png
```
### File Description

| file | description |
| --- | --- |
| `main.py` | main file used to run quiz game |
| `question.py` | stores questions and answers |
| `requirements.txt` | lists the python packages needed for the project |
| `.env.example` | shows the environment variables needed by the project |
| `.gitignore` | tells git which files and folders should not be tracked |
| `README.md` | contains the project documentation |
| `pictures/` | stores project screenshots |
| `pictures/1.png` | screenshot of the game start |
| `pictures/2.png` | screenshot of the quiz section |
| `pictures/3.png` | screenshot of the final result |
| `gifs/` | stores demo GIF files |
| `gifs/demo.gif` | shows the project demo |

## Requirements
Before running the project, make sure you have:
- `Python 3`
- `python-dotenv`


## Installation
1. open a terminal in the project folder.
2. check that python is installed:
```bash
python --version 
```
3. install the python packages:
```bash
pip install -r requirements.txt
```

## Environment Setup
1. Create a `.env` file frome `.env.example`:
```bash
cp .env.example .env
```
2. open the new `.env` file
3. replace the example value with your own password
```text
QUIZ_ADMIN_PASSWORD=your_password_here
```
4. save the file.

> Do not your `.env` file bacause it may contain private information
## Usage
1. Open the terminal in the project folder
2. Run the quiz game
```bash
python main.py
```
3. choose `yes` or `no` for admin mode
4. if you choose `yes` , enter the password from yor `.env` file
5. enter your name
6. enter the questions
7. see your final score and message
8. your result is saved in `results.txt`

## Example Output
```text
do you want to open admin mode? yes/no: no
whats your name?sana
welcome
what language are we using?c++
wrong
what comand start a git?git init
correct
what comand shows git status?git status
correct
your score is:  2 out of 3
good job sana
``` 
## screenshot

### start game
![start game](pictures\3.png)

### quiz
![start game](pictures\2.png)

### final score
![start game](pictures\1.png)

## Demo

![quiz gamedemo](gifs\Animation.gif)
## Roadmap
‌
- [x] add multiple quiz questions
- [x] calculate the final score
- [x] save results to a file
- [x] add admin mode
- [ ] add more quiz questions
- [ ] add difficulty levels
- [ ] add a timer
## Contributing

## Licence

## Author
create by [sana janmohamadi](https://github.com/sanajanmohamadi)