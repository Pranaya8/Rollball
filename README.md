Rollball is a mobile-optimized, path-drawing puzzle game contained within a single HTML file. Powered by the Matter.js physics engine, the game challenges players to draw custom geometric paths to guide a ball through a series of hazardous, forest-themed obstacle courses to shatter a glowing glass target.
✨ Features

    Draw-to-Play Mechanics: Click and drag (or touch and swipe) to draw platforms, ramps, and bridges directly into the world. These lines instantly become static physics bodies.

    Matter.js Physics: Features realistic gravity, friction, and multi-body collisions using the lightweight Matter.js 2D physics engine.

    Variable Materials: Change the physical properties of your ball on the fly. Choose between:

        Plastic: Lightweight and bouncy.

        Rubber: Extreme bounce (high restitution) and low density.

        Metal: Heavy, low bounce, and highly affected by gravity.

    10 Dynamic Levels: Play through progressively difficult puzzles featuring swinging pendulums, windmill mazes, and floating islands.

    Rich Obstacles: Navigate around deadly red spikes, utilize color-coded teleportation portals, and ride invisible updrafts and wind tunnels.

    Procedural Audio & FX: Ambient piano notes, velocity-based bounce sounds, and glass-shattering effects are entirely generated via the Web Audio API. Visuals are enhanced by floating firefly particles and glowing targets.

    Mobile Ready: Features a responsive layout, touch-action protections to prevent accidental browser refreshing, and large UI elements tailored for phone screens.

🎮 How to Play

Your objective is to guide the ball from its starting point to the glowing hexagonal glass target.
Controls

    Choose Material: Select Plastic, Rubber, or Metal from the top-left dropdown menu depending on what the puzzle requires.

    Draw Paths: Click/touch and drag across the screen to create green platforms and ramps. Note: You cannot draw above the UI or after the ball has been launched.

    Launch: Tap the pulsing orange/yellow LAUNCH button to unfreeze the ball and let physics take over.

    Reset/Skip: If your ball hits a red spike or falls off the screen, the level will automatically reset. You can also manually reset your drawings or skip to the next level using the top-left buttons.

🚀 Installation & Usage

    Clone or download this repository.

    Open Draw Path.html in any modern web browser (Chrome, Safari, Firefox, Edge).

    Note: You will need an active internet connection the very first time you load the game so it can fetch the matter.min.js library from Cloudflare's CDN.

    Click the "🔊 Audio" button to initialize the audio engine for ambient music and sound effects.

💻 Technical Details

    Rendering: Uses a combination of Matter.js's built-in physics rendering and custom HTML5 Canvas rendering for 3D ball gradients, fireflies, portal animations, and glowing shadows.

    Audio: 100% synthesized audio. No external .mp3 or .wav files are used. The shatter effect utilizes white noise bursts and high-pass filters.
