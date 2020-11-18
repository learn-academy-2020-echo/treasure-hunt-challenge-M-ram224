# React Treasure Hunt

### Remember:

- Pseudocode!!
- Ask clarifying questions

### User Stories

- As a user, I can see a page with a 3 by 3 grid board game with a question mark in each square. (DONE!!)\*\*\*

- Added a div to square with an `id="square"`
- added styling to the id of square

```css
#square {
  height: 200px;
  width: 200px;
  border: 2px solid black;
}
```

- import Square to App.js
- Call <square /> and this.state.squares.map that component in app.js render()
- Pass value as props
- Add styling to gameboard

---

- As a user, when I click on one of the question marks an alert appears with the index position of that question mark in the array. (DONE)\*\*\*

- git checkout -b alert-mark
- passed index to square
- Called index in square
- Created a method in App that got passed to square

---

- As a user, when I click on one of the question marks instead of the alert the question mark turns into a tree emoji.

-git checkout -b tree-functionality

- emogi keyboard: control, command, spacebar
- set the index to be a tree emoji and set state with the updated value

---

- As a user, if I select the winning square the question mark will become a treasure emoji.
- As a user, if I select the losing square the question mark will become a bomb emoji.
- As a user, I can see a counter that shows how many guesses I have left. The counter starts at 5 and decrements one every time I click on a square that is not the treasure nor the bomb.
- As a user, I can see a message informing me that I won the game if I select the square that contains the treasure.
- As a user, I can see a message informing me that I lost the game if I select the square that contains the bomb.
- As a user, I cannot continue to play the game after I win or lose.
- As a user, I can see a message informing me that I lost the game when I run out of turns (the counter reaches zero).
- As a user, I can click on a “Play Again” button that will restart the game.
