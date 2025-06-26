# FlashCards
📘 1. Flashcard CLI App (Python)
File: Flashcard code.py
Description: A terminal-based flashcard management system for studying, built with nested categories (Subject → Topic → Subtopic → Flashcard).

Features
Add flashcards under structured hierarchy.

Search and display flashcards interactively.

Delete specific subjects, topics, subtopics, or individual flashcards.

Handles user input with fuzzy matching for similar entries.

Nice text-based card layout for flashcard display.

Requirements
Python 3.x

fuzzywuzzy library
Install using:

bash
Copy
Edit
pip install fuzzywuzzy
How to Run
bash
Copy
Edit
python "Flashcard code.py"
Usage
On running, a menu will be shown:

1. Add flashcard: Enter subject, topic, subtopic, question, and answer.

2. Search flashcard: Navigate hierarchy and view cards.

3. Delete flashcard: Delete a node or card.

4. Exit: End the program.

Notes
Uses a recursive dictionary tree for data storage.

Data is lost on exit (not persistent to file/database)
