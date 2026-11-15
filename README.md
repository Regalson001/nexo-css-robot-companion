
# NEXO — CSS-Only Animated Robot Companion

A futuristic animated robot companion built using semantic HTML5 and advanced CSS3 — without JavaScript, external animation libraries, or image assets.

NEXO features independently animated mechanical joints, expressive LED facial details, a floating body, glowing energy core, interactive hover reactions, and a futuristic digital environment.

## Preview

The character is designed to:
- Float continuously.
- Blink its LED eyes.
- Animate its antenna and chest energy core.
- Wave its right arm when hovered.
- Show glowing cheeks and a bigger smile on hover.
- Squish and react when clicked and held.

## Features

### Character Animation
- Nested arm and leg transform hierarchies.
- Independent shoulder, elbow, wrist, hand, knee and ankle elements.
- Floating body animation.
- Animated antenna and signal pulse.
- Blinking eyes and glowing chest reactor.

### CSS Interaction
- `:hover` triggers a friendly wave and facial reaction.
- `:active` triggers a playful squish response.
- `:focus-visible` provides a visible keyboard focus indicator.
- `prefers-reduced-motion` reduces animation for users who request it.

### Visual Engineering
- CSS gradients and metallic surfaces.
- Radial and linear lighting effects.
- Layered shadows and glow effects.
- CSS pseudo-elements.
- Custom border radii and rounded mechanical components.
- Responsive layouts.

## Technologies

- HTML5
- CSS3
- CSS Custom Properties
- CSS Keyframes
- CSS Transforms
- CSS Transform Origins
- CSS Gradients
- CSS Pseudo-elements
- CSS Hover and Active States
- CSS Grid and Flexbox
- Responsive Web Design

## Project Structure

```text
nexo-css-robot-companion/
├── index.html
├── styles.css
├── README.md
├── LICENSE
└── .gitignore
```

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Regalson001/nexo-css-robot-companion.git
   ```

2. Open the project folder:

   ```bash
   cd nexo-css-robot-companion
   ```

3. Open `index.html` in your browser.

Alternatively, open the folder in Visual Studio Code and use the Live Server extension.

## Interaction Guide

| Interaction | Result |
|---|---|
| Hover over NEXO | Waves, smiles and blushes |
| Click and hold NEXO | Performs a playful squish |
| Watch the character | Eyes, antenna and reactor animate |
| Use keyboard focus | Shows a visible focus outline |

## Engineering Concepts

This project demonstrates how nested HTML elements can create a mechanical character with articulated movement.

For example, the arm follows this hierarchy:

```text
Shoulder
└── Upper Arm
    └── Elbow
        └── Forearm
            └── Wrist
                └── Hand
```

Rotating a parent element moves its nested child elements naturally, allowing the arm to behave like a connected mechanical structure.

## Important Notes

- The character is built entirely from HTML and CSS.
- No JavaScript is required.
- The character does not use external image assets.
- Google Fonts are loaded externally; system font fallbacks are available.
- Hover reactions are primarily designed for pointer devices. Touchscreens may not support the same hover behavior.
- The animations are visual demonstrations, not a physics simulation.

## Author

**Stephen Oyugi**

Front-End Developer | AI Automation Engineer

- GitHub: [@Regalson001](https://github.com/Regalson001)
- LinkedIn: [Stephen Oyugi](https://linkedin.com/in/stephenoyugi001)

## License

This project is licensed under the MIT License.
