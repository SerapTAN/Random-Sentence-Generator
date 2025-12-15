# Random-Sentence-Generator
C++ console application that generates random sentences using predefined word lists.

## Description
This project is a C++ console application that generates random sentences by combining words from predefined arrays. Each sentence follows a simple grammatical structure and begins with a capitalized article. The program uses random number generation to create different sentences every time it runs, demonstrating core C++ programming concepts in a fun and practical way.

## Features
- Generates random sentences using predefined word lists
- Capitalizes the first word of each sentence
- Produces multiple sentences in a single run
- Simple and readable console output
- Easy to extend with additional words or sentence patterns

## Technologies Used
- C++
- Standard Input/Output
- Arrays
- Functions
- Random number generation (`rand`, `srand`)
- Time-based seeding

## How It Works
The program stores articles, adjectives, nouns, verbs, and prepositions in separate arrays. It randomly selects one word from each array and combines them into a grammatically structured sentence. The random number generator is seeded using the current time to ensure different results on each execution.

## How to Run
1. Compile the program: g++ main.cpp -o sentence_generator
2. Run the program: ./sentence_generator

## Example Output
The bright dog runs over a small cat.
A fast boy jumps beside the dark house.
One big tree sleeps under a slow car.

## Learning Outcomes
- Practiced using arrays to store and access data
- Learned how to generate random values in C++
- Improved understanding of functions and loops
- Gained experience building a complete console application
