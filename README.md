**README.md Description:**

# Doggo Fetch - Guess the Dog Breed Game

Doggo Fetch is a fun web-based game where players have to guess the breed of a dog in a randomly fetched image. The game is built using HTML, JavaScript, and CSS (styles defined in the `<style>` tag). It uses the Dog API to fetch random dog images and displays them to the players along with multiple-choice options to guess the correct breed.

## How to Play

1. Open the `index.html` file in your web browser.
2. The game will load, and you will see a header with the title "Guess the Doggo" and a prompt asking you to guess the breed of the dog in the image.
3. The game will fetch a random dog image using the Dog API and display it in the "image-frame" section.
4. You will also see a list of multiple-choice buttons (three choices) with different dog breed names.
5. Your task is to select the correct breed name from the provided options and click on the corresponding button.
6. If you choose the correct breed, the button will turn green, indicating that your answer is correct. If you choose the wrong breed, the button you selected will turn pink, and the correct breed button will turn green.
7. After providing an answer, the game will fetch another random dog image, and the process will repeat with new breed options.
8. Continue playing and test your knowledge of dog breeds!

## Game Logic (JavaScript Overview)

1. The game uses the Dog API (`https://dog.ceo/api/breeds/image/random`) to fetch a random dog image URL.
2. The JavaScript code selects three random dog breeds from a predefined list of breeds (`BREEDS` array) and includes the correct breed among the choices.
3. The game displays the fetched dog image along with the multiple-choice buttons for the breed options.
4. When the player clicks on a button, the event handler compares the chosen answer with the correct breed and highlights the buttons accordingly (green for correct, pink for incorrect).
5. The game then fetches a new random dog image and repeats the process for the next round.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
