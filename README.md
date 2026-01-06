# Project overview

Wordly Dictionary is a Single Page Application  built with HTML, CSS, and JavaScript. The application allows people to search for words and instantly view definitions, pronunciation, examples, and synonyms without refreshing the page. It uses the Free Dictionary API to retrieve real-time word data

## What it does

- Search Search for words using a simple input form
Phonetic spelling
Part of speech
Definitions
Synonyms
 Audio pronunciation playback
 Graceful error handling for invalid searches
Single Page Application
## project structure

- `index.html` - The main webpage structure
- `styles.css` - Makes the page look nice with colors and layout
- `script.js` - JavaScript logic and API handling
- `README.md` - This file explaining the project

## How to use it

1. Open the `index.html` file in your web browser
2. Type a word in the search box
3. Click the Search button or press Enter
4. Look at the results that show up

## What I learned

- How to use HTML forms and input elements
- CSS styling with colors, padding, and layout
- JavaScript event listeners for button clicks
- How to use fetch() to get data from APIs
- DOM manipulation to update the webpage
- Error handling for when things go wrong

## API used

I used the Free Dictionary API from https://dictionaryapi.dev/ to get word data.

## Problems I solved

- Making the search work when you press Enter 
- Showing loading messages while waiting for results
- Handling cases when words are not found
- Making synonyms clickable to search for new words
- Playing audio pronunciation when available

## Future improvements

- Add a favorites list to save words
- Make it work on mobile phones better
- Add more languages besides English
- Save search history
