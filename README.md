# Project Name: Balloon Popping Game

## Description
This project is a simple balloon popping game created using HTML, CSS, and JavaScript. When the user hovers over a balloon, it pops and plays a sound. The game ends when all balloons are popped.

## Development Process
1. **Initial Setup**: Created index.html, style.css, and script.js files.
2. **HTML Structure**: Implemented the basic structure of the game in index.html, including the balloon elements and the container.
3. **CSS Styling**: Styled the balloons and container layout in style.css to make the game visually appealing.
4. **JavaScript Functionality**: Wrote the JavaScript code in script.js to handle balloon popping, sound effects, and game-end conditions.
5. **Testing and Debugging**: Tested the game, encountered and resolved various errors related to event handling and game logic.

## Encountered Errors and Resolutions
1. **Event Handling**: Initially, the balloons did not pop on mouseover.
   - **Resolution**: Revised the event listener in script.js to target the class name of the balloons and handle the mouseover event correctly.

2. **Game-end Condition**: The "All balloons popped" message was not displayed after all balloons were popped.
   - **Resolution**: Modified the checkAllPopped() function to correctly update the message and container display.

3. **Audio Playback**: The sound effect did not play when a balloon popped.
   - **Resolution**: Updated the play() function to instantiate and play the audio correctly.

4. **Styling Issue**: Balloons did not have the expected visual appearance.
   - **Resolution**: Adjusted the CSS properties for the balloon class to achieve the desired visual effect.

## Conclusion
Throughout the development of this project, I encountered and successfully resolved several errors related to event handling, game logic, audio playback, and styling. The game now functions as intended and provides an enjoyable user experience.
