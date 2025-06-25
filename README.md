# Echoes of a Life


**Echoes of a Life** is a poignant, narrative-driven puzzle game created as a single HTML file. It combines the strategic depth of a "match-three" puzzle with a powerful, real-life theme: the fight to hold onto memories against the encroaching fog of dementia.

---

## Live Demo

<div align="left">
  <a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/tin2tin/dementia_game/master/index.html">PLAY</a><br><br>
</div>

![Echo of a Life](https://github.com/user-attachments/assets/f164e181-21e9-4cda-9164-9a0c9bed53dd)

## The Concept: The Polaroid Projector

> The mind is a projector, full of memories like slides in a tray. But **Dementia**, like a broken slide, threatens to darken the screen.

In **Echoes of a Life**, you don't just match tiles; you piece together the fading fragments of a lifetime. Each move is an attempt to restore a memory to clarity, letting its light push back the encroaching dark. The game is designed to feel tactile, nostalgic, and deeply personal, using the metaphor of a vintage slide projector to tell its story.

- **The Grid** is a slide carousel, with empty slots waiting for a memory.
- **Dementia Tiles** are broken, shattered slides that block your progress.
- **Memory Fragments** are faded Polaroids of cherished moments.
- **A Match** restores a memory to its full, brilliant clarity, unleashing a powerful effect.

## How to Play

The goal is to survive as long as you can by preventing the grid from being completely filled with Dementia or memory fragments.

1.  **Choose a Memory:** Below the grid, you will be offered a choice of two memory fragments.
2.  **Place it on the Grid:** Drag your chosen Polaroid onto any **empty, recessed slot** on the board.
3.  **Form a Memory Echo:** Line up **three fragments of the same color/category** in a row or column to form a match.
4.  **Push Back the Dementia:** A successful match will create a powerful "Memory Echo" that clears Dementia tiles in a specific pattern.

### The Memories

As you score points and reach new levels, you will delve deeper and unlock new, more complex types of memories:

| Level | Memory Type                                            | Effect                                                       |
| :---- | :----------------------------------------------------- | :----------------------------------------------------------- |
| **1** | <strong style="color:#c78a44">Pets (🐶🐱🐰)</strong>      | Clears a single row or column.                               |
| **2** | <strong style="color:#5a9a93">Occasions (🎂🎄🏖️)</strong> | Clears a 3x3 area.                                           |
| **3** | <strong style="color:#8c6b99">Relatives (👨👩👧)</strong> | Clears a massive cross-pattern of three rows OR three columns. |
| **4+** | <strong style="color:#d17b7b">The Heartstone (❤️)</strong> | A rare, lucid memory that clears a 5x5 area and can be placed on **any** tile. |

### The Threat

- **Dementia:** Black, shattered tiles that block placement.
- **Stubborn Dementia:** A darker, more fractured tile that requires **two** Memory Echo hits to be fully cleared. On the first hit, it will downgrade to a regular Dementia tile.

---

## Features

-   **Deeply Thematic Gameplay:** Every element, from the art style to the mechanics, serves the central narrative of memory and loss.
-   **Dynamic Difficulty:** The game becomes progressively more challenging as you level up. The rate of Dementia spread increases, and "Stubborn" tiles become more common.
-   **Strategic Depth:** A carefully balanced, weighted system for fragment generation makes players choose between making a quick, simple match or holding out for a rare, powerful memory.
-   **Fully Responsive Design:** Using a `vmin`-based layout, the game looks and feels great on any screen, from a mobile phone to a widescreen desktop.
-   **Frame-Rate Independent Game Loop:** Built with `requestAnimationFrame`, the game's timing is consistent across all devices, ensuring a fair experience for everyone.
-   **Custom Synthesized Audio:** Sound effects are generated in real-time using the Web Audio API, providing tactile feedback without the need for external asset files.
-   **Atmospheric Music:** A looping background track enhances the gentle, introspective mood.

---

## How to Run

This game is built as a single, self-contained HTML file.

### Playing Locally

1.  **Clone or Download:**
    -   Simply download the `index.html` file.

2.  **Change Music (Optional):**
    -   In the same directory as the HTML file, create a folder named `audio`.
    -   Place an MP3 file inside this folder and name it `background_music.mp3`.
    -   The final file structure should be:
        ```
        /your_game_folder/
        ├── echoes_of_a_life_final.html
        └── /audio/
            └── background_music.mp3
        ```

3.  **Open in Browser:**
    -   Open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).

---

## A Note on the Theme

This game touches on the sensitive and deeply human experience of dementia. It was designed with care and respect, not as a direct simulation, but as a metaphorical exploration of the struggle to hold onto one's identity, the power of cherished memories, and the quiet beauty of a life lived. We hope it resonates with players in a meaningful way.
