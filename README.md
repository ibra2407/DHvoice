# Demonstration of Uncanny Text-to-Speech with Genetic Algorithm

This code demonstrates the utilization of text-to-speech (TTS) technology alongside a genetic algorithm to simulate evolution towards a target string. The purpose of this demonstration is to showcase how TTS can create an uncanny experience, especially when coupled with the disembodied voice reading out evolving strings generated by the genetic algorithm.

A demo can be found [in a YouTube video here.](https://www.youtube.com/watch?v=JeCQDRNJoLA&ab_channel=reservoir247) Please lower the volume, it's pretty loud ;<

## Code Overview

The Python code provided in this repository simulates a genetic algorithm to evolve a population of strings towards a target string. Here's an overview of the key components:

- `Individual` class: Represents an individual in the population. Each individual has a chromosome (string), fitness score (based on how close it is to the target string), and methods for generating offspring and calculating fitness.
- `main()` function: Implements the genetic algorithm loop. It initializes a population of random strings, evolves them over generations through selection, crossover, and mutation, and stops when the target string is reached.
- `speak()` function: Uses the `pyttsx3` library to convert text strings into spoken words.

## Uncanny Experience

The uncanny experience arises from the combination of TTS technology and the evolution of strings towards a target. As the genetic algorithm progresses, the evolving strings are read aloud by the TTS engine, creating a surreal and somewhat eerie sensation. The disembodied voice narrating the incremental changes in the strings adds a layer of abstraction and unpredictability to the evolutionary process.

## How to Use

1. Install Python if not already installed.
2. Install the `pyttsx3` library using pip: `pip install pyttsx3`.
3. Copy the provided Python code into a `.py` file.
4. Run the Python script.

Upon execution, the program will start the genetic algorithm process. The evolving strings will be printed to the console, and the TTS engine will read them aloud. The disembodied voice will highlight the incremental changes in the strings as they evolve towards the target.

## Notes

- This demonstration underscores the capabilities and limitations of TTS technology.
- The eerie nature of the experience serves as a reminder of the potential societal impacts of advanced AI technologies.

## Credits

To implement the genetic algorithm, I referred to the tutorial on [GeeksforGeeks](https://www.geeksforgeeks.org/genetic-algorithms/). I then adapted the code to include the use of the PyTTSX3 library to speak out the voice.

