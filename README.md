# Cymatic Visualizer with Musical Notes

This project is an interactive **Cymatic Visualizer** that displays evolving wave patterns based on audio frequencies, allowing users to visualize sound vibrations in real-time. It also includes a set of musical note buttons that adjust the frequency to specific musical notes.

## Features

- **Dynamic Cymatic Patterns**: Watch real-time visualizations of cymatic patterns that change with frequency and time evolution.
- **Interactive Frequency Controls**: Adjust the frequency using a slider or manual input, with a range of 20 Hz to 5000 Hz.
- **Musical Note Buttons**: Quickly switch between predefined musical notes (C4 to C5), which will update the frequency and visual pattern.
- **Real-Time Tone Generation**: Play a sine wave tone that matches the selected frequency.
- **Responsive Design**: The visualizer adapts to different screen sizes and resolutions.
- **Accessibility Features**: All input elements are keyboard accessible.

## How to Use

1. **Start the Tone**: Click the `Start Tone` button to begin generating a sine wave at the current frequency.
2. **Adjust the Frequency**:
    - Use the **slider** or **input box** to change the frequency value.
    - The frequency range is from **20 Hz** to **5000 Hz**.
    - The cymatic pattern will update in real-time based on the selected frequency.
3. **Stop the Tone**: Click the `Stop Tone` button to stop the sine wave generation.
4. **Select a Musical Note**: Use the provided buttons to quickly set the frequency to predefined musical notes (C4, D4, E4, etc.).
5. **Responsive Canvas**: The canvas automatically adjusts to the screen size, ensuring optimal viewing on all devices.

## Project Structure

- **HTML**: The visualizer uses the `<canvas>` element to display cymatic patterns.
- **JavaScript**:
    - **Audio Generation**: Uses the Web Audio API to generate sine wave tones.
    - **Pattern Rendering**: Real-time rendering of cymatic patterns using trigonometric functions.
    - **Responsive Controls**: The frequency can be adjusted via a slider, input field, or note buttons.
- **CSS**: Simple styling for layout, accessibility, and responsiveness.

## Notes on Functionality

- The canvas renders **concentric wave patterns** that expand from the center, with points oscillating in response to the audio frequency.
- The **time variable** is used to animate the patterns in real-time, simulating the movement of sound waves.
- **Wave Count**: Increased to **10** concentric waves for better visual detail.
- **High-Resolution Support**: Automatically detects and adjusts for high-resolution screens.

## Installation

This project runs in any modern browser. Simply open the `cym.html` file in your browser to start the visualizer.

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.
3. Start experimenting with frequencies and enjoy the cymatic visualizations.

## License

GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007

