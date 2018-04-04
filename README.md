## Synopsis
The autocomplete module allows you to import a data set, which will be organized into a trie. You can then search for a string in that trie and return every word in the trie that starts with that string. 

## Code Example
* Use `insert()` to add words individually.
* Use `populate()` to add a data set.
* Use `suggest()` to return an array of words that include the string you pass in as an argument.
* Use `delete()` to remove words from your trie.
* Use `count()` to return the number of words in your trie.

## Motivation
Because who wants to type out a full word when computers can do the work for us? `¯\_(ツ)_/¯`


## Installation
Run `npm install https://github.com/danielafcarey/autocomplete.git -S` on your command line.

In the file you wish to use the module in, add: `const autocomplete = require('autocomplete')`