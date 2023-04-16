# The Treasure Hunt

The treasure hunt is a type game that tests the verbal (or communication) and problem-solving skills of the players.
The game has a treasure box with a 6-digit code lock. The player has to find the code with the help of cards. thus they will have fun while playing the game.
The project is built using Django Framework(Python) along with some JavaScript used for timers. No Bootstrap css is used. All the codes are written from scratch, although some references are taken from some websites for debugging purposes.

The gameplay is very simple. The user has to sign up and log in. After that, the game will begin. In the game, there is a treasure box with a 6-digit lock, and the user has to find the unlock code.

There is an admin panel where the leader board and user data insights are also displayed.


## Skills Assessed

Through this game, the verbal or communicational and reasoning or problem-solving skills of the users are assessed, Thus this game assesses the soft skills of the user and helps them to improve their skills.
There are dead-ends in the project which will arise when users fail to get the correct logic required for solving the question.



## Possible ways To solve the puzzle

The First way is the simple way where the user is expected to give correct answers to all the questions and win the puzzle.

The Secound way is the way where the user need to find all the answers from the questions and win the puzzle.

The possible answers to the questions asked in the puzzle are:
```
Q1.  
Ans: fire

Q2.
Ans: 1845

Q3.
Ans: personification

Q4.
Ans: jbk

Q5.(dead end bridge question)
Ans: large (correct)
Ans: few (leads to dead end)

Q6.(dead end bridge question)
Ans: 36 (correct)
Ans: 31 (leads to dead end)
 
``` 

## Technology used
This project is made from scratch and no templated were used. This uses the Django framework which is one of the best-suited frameworks for these kinds of projects. Some javascript is also used for some functionalities to work such as timer and all.
The code is not much complicated and is easy to understand. The dead-ends are also linearly arranged and simple logic is applied for that.

## Tables used 

#### Users

| ATTRIBUTE | DATATYPE | INDEX   | DESCRIPTION|
| :-------- | :------- | :-------- | :-------------|
| `useremail` | `varchar(256)` | `primary key` | `stores user email`|
| `username` | `varchar(256)` | | `user name`|
| `userpass` | `varchar(256)` | | `stores user pass (using SHA256)`|

## Installation
Windows \
It is required to have Python installed in the system.\
It is necessary to check if your requirements are already installed, please refer requirements.txt file in the repository.\
you can install the dependencies as follows:
```
    >  pip install -r requirements.txt
```

For installation, It is recommended to create a virtual environment.
You can use the following command for creating a virtual environment:
```cmd
    > python -m venv {name}
``` 
now you can paste the files in this virtual environment, and then 
once you are ready you can activate the virtual environment as:

```cmd
    > {name}\scripts\activate  
```
Now enter into the directory (where you copied the repo.)
```cmd
    > cd {folder name}
```
Now you can run the server with the following command:
```cmd
    > python manage.py runserver
```
You will get the URL and the browser will be started automatically and the puzzle (website) will be hosted on your local server.

## 🚀 About Me
I'm always curious to learn new things and try new technologies... I m currently pursuing my Bachelor in Technology in Information Technology. My interests are in full stack.