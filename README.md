# HangmanC-
1. Introduction
We have developed an interesting and mind game called “The Hangman” in
C++. In this project of game, the computer program randomly chooses a
target string from the built-in file that is added in the project which is made
by the programmer. The program asks the user to suggest letters that occur
in the string. After each guess, the program compares each letter by that
string which is choose by the computer itself. When the targeted letter is
correct, the control moves to the next letter. If the targeted letter is incorrect,
the control will draw a hangman by giving nine (9) tries to enter a letter until
the complete hangman is drawn. When the complete hangman is drawn or
the user couldn’t be able to give correct answers for nine times, the user will
lose the game and “Game Over” will be printed in the console screen. And
when if the user gives all the correct answers of the targeted string, he/she
will win the game, and “victory” statement will be printed. Note that the
guessed letters would be in uppercase. And also, when the user entered the
wrong guess, he/she will lose 1 try at a time until he will give a correct
answer and move to the next letter, but he will have the same remaining tries
until he/she will guess the entire string correctly.
2. Project Idea
Hangman is a popular paper and pencil word guessing game, where one
player thinks of a word and other tries to guess that word which can be in
that certain number of blanks. And at each correct letter, the player moves to
the next letter. And if the guessed letter is incorrect, the other player will
draw a hangman face, if again the letter is incorrect in the second try, he will
draw the arms of the hangman and so on until the complete hangman is
drawn and the player will lose the game.
We have made this project in C++ with this similar idea, where the computer
chooses the word and the user have to guess. We have used different built-in
and user defined functions, control structures, file handling, string,
structures, classes, and control statements in this project.
The scope of this project is to teach us how to implement the theory and
structures we had learned in class as vectors and to polish our skills,
entertainment purpose, and making the minds stronger and sharper.
3. Main Functionality/ Features
 Word Guessing Mechanism
The user has to guess the targeted string, that is choose by the
computer from the file that is defined by the programmer.
 Header file iostream
We made use of iostream library in visual C++ to allow us to ask user
input word guesses and send messages to the console screen.
 Header file vector
Vectors in C++ are the dynamic arrays that are used to store data,
whose size can be initialized and altered in the run time by the user.
Vectors provide more flexibility to the program. And in this project,
we have used it to change the size of the targeted string every other
time when the computer chooses that string from the file.
 Header file fstream
This class is the combination of both ofstream and ifstream. It
provides the capability of creating, writing, and reading a file.
ifstream is used to read data from file. And ofstream is used to write
data in file. In this project we have used ifstream in it.
In this project, the programmer defined and built a file in which he has
write the words that will be asked from the user on the output screen.
The control then asks the user about the guess words and compares
them with the targeted word, which is choose by the computer from
that file, that the programmer have defined.
 Header file time.h
This header file contains definitions of functions to get and
manipulate date and time function. In this project, we have used it to
decrease the times of guesses/tries , whenever user gives the incorrect
output. And when the seven number of guesses will no more, the user
will lose the game.
 User Defined Functions
We have defined different functions in our project that fulfil the needs
of the game. And are called in the main() function.
 Header file string
We have included this header file to use strings in the project and to
define them in the function. And also, to read strings from the file.
 Control Structures
In this project, we have used some control structures to check whether
the entered guessed letter is the choose targeted letter or not.
 windows.h header file
We have used this header file to change the color of the program text
in the console and to give colors to the console background.
