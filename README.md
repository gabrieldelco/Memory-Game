## Memory Game
Built a tech memory game using vanilla javascript and vanilla CSS, as well as an endgame screen and play again feature.

### Aplication Sctructure

    - **game.js**: creates the game objetc, and manages the rules of the game.
    - **script.js**: manages the game inferface using `game.js` features. Used the CSS animation trick `{transform: rotateY(180deg)}`, and `{backface-visibility: hidden}` in order to flip the cards . That being said, script.js is able to flip cards by toggling the `'.flip'` CSS class on elements.


