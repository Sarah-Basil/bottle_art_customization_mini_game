# bottle_art_customization_mini_game
This is a small game (in progress) that I had made to accompany my main bottle art website project for my 12th grade senior capstone. The website itself was an effort to promote recycling as an environmental conservation effort, my own bottle art (as a small attempt at running my own store), and to inspire others to recycle and re-use bottles to make art. While the game is currently not fully implemented, it was my first dive into creating my own customization game from scratch, utilizing javascript, HTML, and CSS. Below, I've detailed some instructions on how to set up the game locally, and how to use it (again, it's not thoroughly fleshed out, but here are instructions on how to use it as of now!) 


## Setup Instructions
To run this Bottle Art Game locally, follow these steps:

1. **Clone the Repository:**
   On your local command line/terminal, you can do the following to clone the repository: 
    ```bash
    git clone https://github.com/Sarah-Basil/bottle-art-game.git
    cd bottle-art-game
    ```

3. **Open the Project:**
   I tried to do this two ways: 
    - If you have python installed, you can do the following to start a local host:
    ```bash
    python -m http.server 8000
    ```
    After that, you can open your web browser and go to http://localhost:8000/index.html
    - Alternatively (and the method I use for its simplicity): you can use a local server (like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code) to run the game. In VSCode, after you install the Live Server extension, you can simply open the html file, and click on the live server button below to open the mini game in a web browser. 

5. **Game Files:**
    - The project contains the following files:
      - `index.html`: The main HTML file.
      - `styles.css`: The CSS file for styling the game.
      - `script.js`: The JavaScript file for the game's logic.
      - `assets/`: A folder containing SVG images and other assets used in the game.

## Usage Instructions
1. **Start the Game:**
   - Open the `index.html` file in a web browser.
   - Click the "Play" button to begin.

2. **Select a Bottle:**
   - Choose one of the bottle shapes from the selection screen.

3. **Customize the Bottle:**
   - Select a color using the preset options or the color picker.
   - Apply patterns to the background of the bottle in the pattern selection screen.

4. **Enjoy Your Design:**
   - Once you're satisfied with your design, you can admire your custom bottle and restart the game.

## Project Demonstration
A video demonstration of the what's available of the mini game is available [here](https://drive.google.com/file/d/1Rd1P94m-9oChDdugMonJaE65Q6-I1uxw/view?usp=sharing)

## Future Improvements
I understand that as of now, it's not the shiniest or most polished game, but I believe it was a good start and was able to serve its purpose for the capstone project. Of course, if given the opportunity, I would love to: 
- Implementing the ability to save or share the custom bottle designs.
- Adding more shapes, colors, and patterns for increased customization options.
- Improving the user interface for a more engaging experience.
- Potentially add machine learning & artificial intelligence (like personalized design recommendations, NLP or chatbots to create or generate designs automatically, highlight trendy designs, etc.... a lot can be done) 







