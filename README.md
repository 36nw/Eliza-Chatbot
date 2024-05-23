# Eliza Chatbot w/ GUI

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Example Dialogue](#example-dialogue)
- [Code Structure](#code-structure)
- [Repository Structure](#repository-structure)
- [License](#license)
- [Additional Information](#additional-information)

## Overview

Eliza is a simple chatbot that simulates a conversation with a psychotherapist. This program, written in Python, uses regular expressions to identify key words and phrases in the user's input, responding in a way that mimics a therapist's conversational style. The goal is to transform user statements into questions and engage the user in a dialogue that feels personal and natural.

## Features

- Word Spotting: Eliza recognizes specific keywords in the user's input and responds based on the presence of these words.
- Sentence Transformation: The chatbot can transform simple statements from the user into questions, encouraging further conversation.
- Personalization: Eliza asks for and uses the user's name throughout the dialogue to create a more personalized experience.
- Robustness: The program handles unexpected or complicated inputs gracefully, providing plausible responses to keep the conversation flowing.

### Example Dialogue

python eliza.py
-> [eliza] Hi, I'm a psychotherapist. What is your name?

=> [user] My name is Ozlem.

-> [eliza] Hi Ozlem. How can I help you today?

=> [Ozlem] I want to rule the world.

-> [eliza] Ozlem, why do you want to rule the world? [transform statement into question]

=> [Ozlem] I don't know, I think I crave power.

-> [eliza] Why don't you tell me more about your cravings? [word spot "crave" and respond.]

=> [Ozlem] ...

## Code Structure

Chatbot_Eliza.ipynb: The main program file containing the implementation of the Eliza chatbot.

## Repository Structure

Explore the repository to find resources and documentation that guide contributors in enhancing the accuracy of Avyuct Intellidetect:

- **README.md:** Introduction and overview of the Eliza Chatbot project.
- **Code files:** The main program file containing the python code for implementation of the Eliza chatbot.
- **LICENSE:** MIT License file.

## License

This project is licensed under the [MIT License](LICENSE). Your commitment to collaboration aligns with the open-source spirit of this project.

## Additional Information

Eliza is inspired by Joseph Weizenbaum's original ELIZA program, which was one of the first examples of natural language processing. While this implementation is simplified, it demonstrates the basic concepts of pattern matching and response generation in chatbots.
