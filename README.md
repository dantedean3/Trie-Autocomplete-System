Overview

This project implements an autocomplete engine using a Trie (prefix tree) data structure.

The system stores words in a Trie and efficiently returns suggestions based on user input prefixes. Trie-based autocomplete is commonly used in:

search engines

text editors

command-line tools

mobile keyboard prediction

This project demonstrates how prefix trees can be used to build fast lookup systems for large word datasets.

Features

Insert new words into the Trie

Delete existing words

Search for exact word matches

Generate autocomplete suggestions from prefixes

Display statistics about stored words

Example Usage

Start the application:

python -m src.application --data data/words.txt

Example interaction:

> search app
Found word: app

> autocomplete ap
apple
application
apply
apt

> add apex
Word added successfully

> delete apt
Word removed
