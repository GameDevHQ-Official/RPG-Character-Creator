# RPG Character Creator

## Objective

Create a RPG character creator program in C++ that collects and displays various character details using different data types. 

## Requirements

### Character Details Collection

The program should collect the following character details:
- Name (string)
- Class (string)
- Race (string)
- Strength (integer, 1-20)
- Dexterity (integer, 1-20)
- Constitution (integer, 1-20)
- Intelligence (integer, 1-20)
- Wisdom (integer, 1-20)
- Charisma (integer, 1-20)
- Age (integer)
- Height (double, in meters)
- Gender (char, 'M' or 'F')
- Has Familiar (bool)
- Initiative (short, 1-20)
- Speed (float, meters per second)

### Output

The program should display the collected character details in a structured format.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<string>`).

### 2. Define Variables

- Define variables for each character attribute using appropriate data types.

### 3. Prompt User for Input

- Use `std::getline` for string inputs (name, class, race).
- Use `std::cin` for numeric inputs (strength, dexterity, constitution, intelligence, wisdom, charisma, age, height, initiative, speed).
- Use `std::cin` for single character input (gender).
- Use `std::cin` for boolean input (has familiar).

### 4. Type Conversion

- Use `static_cast<type>()` to convert the height from meters (double) to centimeters (int).

### 5. Display Character Profile

- Format and display the character's profile using `std::cout`.

## Example User Interaction

```plaintext
*****************************************************************
*                    RPG Character Creator                      *
*****************************************************************

Enter your character's name: Aragorn
Enter your character's class: Ranger
Enter your character's race: Human
Enter your character's strength (1-20): 18
Enter your character's dexterity (1-20): 15
Enter your character's constitution (1-20): 17
Enter your character's intelligence (1-20): 14
Enter your character's wisdom (1-20): 13
Enter your character's charisma (1-20): 16
Enter your character's age: 87
Enter your character's height (in meters): 1.95
Enter your character's gender (M/F): M
Does your character have a familiar? (1 for Yes, 0 for No): 1
Enter your character's initiative (1-20): 12
Enter your character's speed (meters per second): 3.5

*****************************************************************
*                       Character Profile                       *
*****************************************************************
* Name:          Aragorn                                        *
* Class:         Ranger                                         *
* Race:          Human                                          *
* Strength:      18                                             *
* Dexterity:     15                                             *
* Constitution:  17                                             *
* Intelligence:  14                                             *
* Wisdom:        13                                             *
* Charisma:      16                                             *
* Age:           87                                             *
* Height:        195 centimeters                                *
* Gender:        M                                              *
* Has Familiar:  1                                              *
* Initiative:    12                                             *
* Speed:         3.5 meters/second                              *
*****************************************************************
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
