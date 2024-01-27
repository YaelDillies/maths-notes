# Part III Lectures Notes

This repository contains lecture notes for the Part III courses that I (Yaël) am attending during the 2023-24 Cambridge academic year.

## Michaelmas 2023

* Combinatorics, 16 lectures, lectured by Béla Bollobás
* Functional Analysis, 24 lectures, lectured by András Zsák
* Lattice Models, 16 lectures, lectured by Wendelin Werner
* Ramsey Theory on Graphs, 16 lectures, lectured by Julian Sahasrabudhe

## Lent 2024

* Additive Combinatorics, 16 lectures, lectured by Julia Wolf

## Anki cards

On top of the lecture notes, I am writing [Anki](ankiweb.net) cards. I type the notes in LaTeX and subsequently convert them to Anki decks using Marcus Zibrowius' [LaTeX Note Importer](https://tentativeconvert.github.io/LaTeX-Note-Importer-for-Anki/).

### Courses with notes

I currently have notes for the following courses:
* Additive Combinatorics (partial)
* Lattice Models (partial)

### How to use them

You need
* A working LaTeX install
* [Anki](ankiweb.net)
* the [LaTeX Note Importer](https://tentativeconvert.github.io/LaTeX-Note-Importer-for-Anki/) add-on for Anki

The header to use in your Anki card type is anki_header.tex

### How to modify them

You can add/change cards directly from the Anki interface. However a more principled approach is to edit the source .tex directly and then reimport it in Anki (using the `Update existing notes when first field matches` option). This way, you get to use your favorite editor and you have a better overview of all the cards in a deck.

The way Anki recognizes cards that have been modified is through their **UUID**. This is set by the `\xfield` command. It is advised you do not change the UUID of a card after creation so as to avoid Anki creating a duplicate. If you really want to change the UUID of a card, you should change it both in the .tex and in your Anki deck *before* reimporting the .tex in Anki.