# DodgeUp Classic — Java Arcade Game

An early version of a **2D obstacle-dodging game** built with Java and the Processing library. Move horizontally with the mouse, avoid falling blocks, and collect items to improve your score.

## Gameplay
- Mouse-controlled player movement
- Random falling obstacles and collectible items
- Collision detection and a limited number of lives
- End-of-round win/game-over states
- Player name and high-score logic in the source

## Tech stack
Java, Processing, Maven.

## Run requirements
1. Install a JDK and Maven.
2. Ensure the Processing Core library is available to the project (the `pom.xml` may need a proper dependency declaration).
3. Open the project in a Java IDE and run `Main.java` once its missing dependencies have been addressed.

```bash
git clone https://github.com/mahdiramezanif/firstDodgeUp.git
cd firstDodgeUp
mvn compile
```

**Current blocker:** `src/main/java/Main.java` calls `Database.read()` and `Database.write()`, but the `Database` class is missing from the public repository tree. Add that implementation or remove those calls before a successful compilation.

## Controls
Move left/right with the **mouse** to avoid colored blocks and collect the white items.

## Project status
Early educational game prototype. For another version of this arcade concept, see [graphical-game](https://github.com/mahdiramezanif/graphical-game). Screenshots and a short gameplay GIF would make this README clearer.
