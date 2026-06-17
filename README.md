# Word Hunt

Java Swing word game inspired by Boggle. The app generates a 4x4 board and checks submitted words against `words.txt`.

## Requirements

- JDK 11+

## Run

From the repository root:

```bash
javac -d out src/*.java
java -cp out Main
```

Run the command from the repository root so the game can load `words.txt`.

## Project Layout

- `src/Main.java` starts the Swing UI.
- `src/WordHuntGame.java` contains the game window and interaction flow.
- `src/Board.java`, `src/Letter.java`, and `src/Dictionary.java` contain the board and word lookup logic.
- `words.txt` is the dictionary file used for validation.
