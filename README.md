#Linux Plus Flashcards

These are my homemade .txt and .tsv files that I use to store what I've been learning from Shawn Powers' Linux+ course and other Linux+ study resources.

I import these files into Anki to create the actual flashcards I use for studying.

Using the Flashcards with Anki

The .tsv files are formatted so they can be imported directly into Anki.

1. Install Anki

If you don't already have Anki installed, download it from the official website:

https://apps.ankiweb.net/

2. Download a .tsv file or txt file (should still be tab separated)

Choose the topic you want to study and download the corresponding .tsv file from this repository.

For example:

commands.tsv
permissions.tsv
networking.tsv

The exact files and topics may change as I continue adding material.

3. Open Anki

Create a new deck, or choose an existing deck where you want to store the Linux+ cards.

For example:

Linux+

You can also create separate decks for different topics if that's how you prefer to organize your studies.

4. Import the .tsv file

In Anki:

Select File → Import.
Select the .tsv file you downloaded.
Make sure the file type is detected as Tab-separated values.
Set the appropriate Deck.
Make sure the fields are mapped correctly.

A typical card in these files uses two fields:

Front<TAB>Back

The first column becomes the Front of the card and the second column becomes the Back.

For example:

What command displays the current working directory?	pwd

This produces a card like:

Front:

What command displays the current working directory?

Back:

pwd

5. Check the import settings

Before importing everything, take a moment to look at Anki's preview.

Make sure:

The separator is set to Tab.
The first column is mapped to the Front field.
The second column is mapped to the Back field.
Any HTML or formatting is handled as expected.
You are importing into the deck you intended to use.

If everything looks correct, proceed with the import.

.tsv vs .txt

I use both .tsv and .txt files in this repository.

Studying

Once the cards have been imported, I recommend letting Anki's spaced-repetition system determine when cards should be reviewed rather than trying to memorize everything in one sitting.

The goal of this repository isn't to provide a complete replacement for Linux+ study material. These are my personal study notes and flashcards, shared in case they are useful to someone else preparing for Linux+ or simply learning Linux.

I will continue adding and refining cards as I learn more.

Disclaimer

These flashcards are unofficial and are not affiliated with, endorsed by, or produced by CompTIA or Shawn Powers.

The content is based on my own studies, notes, and understanding of Linux and Linux+ topics. Always refer to official documentation and current exam objectives when preparing for a certification exam.
