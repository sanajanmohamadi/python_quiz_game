# Python Quiz Game
A simple quiz game built with python

## Table of contaxt
- [Table of contaxt](#table-of-contaxt)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Example Output](#example-output)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Licence](#licence)
- [Author](#author)

## Features

- Quiz System
  - Asks the player multiple questions
  - Checks the answers automatically
  - Calculates the final score

- Results storage
  - Saves quiz results in `results.txt`

- Admin Mode
  - Asks for the admin password
  - Checks if the password is correct
  - Keeps the private information outside the main Python file
  - Loads the password from `.env`
  
## Project Structure

```text
mini_store/
│   .env.example
│   .gitignore
│   main.py
│   prouduct.py
│   requirements.txt
│   README.md

```
### File Description 
- ` main.py ` - main file used to run mini shop
- ` prouduct.py ` - varios products store
- ` requirements.txt ` - list the python packages meeded for the project
- `.env.example ` - shows the envoiment variables needed by the project
- `.gitignore ` - tells git which files and folders shold not be tracket
- `.README.md ` - contains  the project documentation
  
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
## Roadmap
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