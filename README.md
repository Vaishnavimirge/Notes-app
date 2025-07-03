# Notes App

## Description

This is a simple Notes App built with plain HTML, CSS, and JavaScript. It allows users to write notes, save them locally in the browser using `localStorage`, and delete them when no longer needed. Notes persist even if the page is refreshed or the browser is closed and reopened.

---

## Features

* Write notes in a text area.
* Save notes by clicking the "Save Note" button.
* View all saved notes listed below the input.
* Delete individual notes.
* Notes are saved in browser `localStorage` so they persist across page reloads.

---

## Project Structure
Notes-App/
    ├── index.html — Main HTML file containing the user interface
    ├── style.css — CSS stylesheet (linked but optional)
    ├── script.js — JavaScript file handling note saving, display, and deletion
    └── README.md — Project documentation (this file)




## How to Use

1. Open `index.html` in your web browser.
2. Type your note in the text area.
3. Click the **Save Note** button to save the note.
4. Your saved notes will appear below the input area.
5. To delete a note, click the **Delete** button next to it.
6. Notes are saved automatically in your browser and remain after refresh.

---

## Code Explanation

* Notes are stored as an array of strings in `localStorage` under the key `"notes"`.
* On saving a note, the text is added to this array and saved back to `localStorage`.
* The `displayNotes` function reads notes from `localStorage` and updates the displayed list dynamically.
* Each note displays its text and a Delete button, which removes the note from storage and UI.

---

## Technologies Used

* HTML5
* CSS3 (linked stylesheet, optional)
* Vanilla JavaScript
* Browser `localStorage` for persistent data storage

---

## License

This project is free to use and modify.

