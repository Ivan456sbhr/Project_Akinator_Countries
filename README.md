## Ministry of Education and Science of Ukraine

## STEPAN GZHYTSKYI NATIONAL UNIVERSITY OF VETERINARY MEDICINE AND BIOTECHNOLOGIES LVIV

## Individual Project "Akinator Countries" for Educational Practice

Prepared by: Ivan Svyrydiuk, student of group KN-11

Supervisor: Senior Lecturer N. Zaplatynskyi

## Dubliany 2026

## Project idea:
The project aims to create a console game based on the principle of the "Akinator" application. The user will think of any country from the available list, and the program will attempt to guess it through a series of questions. After each answer, the program will analyze the received information and gradually eliminate countries that do not match the specified conditions. As a result, the number of possible options will decrease until the program can suggest the most probable answer.

## Functionality
The program will include a main menu with the following options: "Play", "Statistics", "Achievements", "Country List", "Game Rules", "Restart", and "Exit". During gameplay, the user will think of a country and answer questions using one of the following options: "Yes", "No", "Partially", "I Don't Know", or "Good Evening, We Are from Ukraine". Based on the user's answers, the program will eliminate unsuitable countries and, after a certain number of questions, attempt to guess the selected country. The Statistics section will display a table containing the twenty most frequently guessed countries, as well as information about the fastest and longest guessing sessions. The Achievements section will contain special rewards for various user actions, such as "Master" for discovering all countries from the list or "Blitzkrieg" for having a country guessed in fewer than ten questions. The Game Rules section will provide a complete description of the game's mechanics and principles.

## Implementation
The project will be developed in the C++ programming language using Microsoft Visual Studio. Data will be stored using structures, text files, and vectors. The files will contain information about countries, questions, statistics, and achievements. The program will utilize loops, conditional statements, functions, and file-handling features provided by the fstream library.

## Work plan

#### 1. Create a repository for the project
GitHub repository will be created to store and manage the project's development process, allowing all code changes to be tracked.

#### 2. Create a README file
README file will be prepared containing the project description and basic information about the program.

#### 3. Develop the initial project structure and menu
Basic menu system will be implemented to allow users to interact with the application.

#### 4. Implement data structures for countries and questions
Structures and arrays will be created to store information about countries and questions used in the game.

#### 5. Implement the core game logic
Algorithm for guessing countries through questions and gradual elimination of incorrect options will be developed.

#### 6. Add additional console functionality
Statistics, achievements, and records will be added to expand the game's functionality.

#### 7. Implement data saving and loading
File handling will be configured to save and load information between program sessions. A reset function for stored data will also be developed.

#### 8. Test the final version of the console application
The program will be thoroughly tested to ensure the correct operation of all implemented features.

#### 9. Finalize the project and prepare for presentation
The project documentation and presentation materials will be completed in preparation for the final defense.

## Notes
At the initial stage of development, the project will contain a limited number of countries and questions to verify the functionality of the guessing algorithm. Later, the database will be expanded to approximately one hundred countries and a large number of characteristics, improving the accuracy of the guessing process. All project updates will be gradually uploaded to the GitHub repository as separate commits to demonstrate the development process.
