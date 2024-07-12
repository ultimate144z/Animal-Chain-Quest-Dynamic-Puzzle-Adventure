# Animal-Chain-Quest-Dynamic-Puzzle-Adventure (UBUNTU)

Created a puzzle game where players form chains of animals to advance through levels. Implemented Normal and Time Trial modes with unique objectives. Designed a scoring system rewarding longer chains and combos. Focused on user-friendly design, responsive controls, and engaging graphics. Enhanced skills in level design and efficient coding.

## How to Compile and Run

1. **Game.cpp** is the main file.
2. All other files are included in the main file.
3. Use the following commands to compile and link the project:

    ```bash
    # Compile all .cpp files
    g++ -c *.cpp -DSFML_STATIC

    # Link the object files to create the executable
    g++ *.o -o sfml-app -lsfml-graphics -lsfml-window -lsfml-system
    ```

4. **Note:** You will need to change the `workin_dir` variable in the `game.cpp` file to the location of the project directory for the images to load properly.
