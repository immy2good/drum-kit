# Drum Kit

A browser-based drum kit application that lets you play drum sounds by clicking pads or pressing corresponding keys on your keyboard. Built with vanilla JavaScript as part of the University of London BSc Computer Science coursework.

## Table of Contents

* [Demo](#demo)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Installation](#installation)
* [Running the App](#running-the-app)
* [Accessing the Front End](#accessing-the-front-end)
* [Project Structure](#project-structure)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## Demo

Try the live version here:

**GitHub Pages:**

```
https://immy2good.github.io/drum-kit/
```

## Features

* **Interactive Drum Pads**: Click or press keys (`A`, `S`, `D`, `F`, `G`, `H`, `J`) to play different drum sounds.
* **Animation Feedback**: Pads animate on activation to provide visual feedback.
* **Responsive Design**: Works seamlessly on desktop and mobile devices.
* **Audio Playback**: High-quality `.wav` samples for an immersive experience.

## Tech Stack

* HTML5 & CSS3
* Vanilla JavaScript (ES6+)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/immy2good/drum-kit.git
   cd drum-kit
   ```
2. No external dependencies required.

## Running the App

* **Open directly in browser:**

  * Double-click `index.html` in the project root.

* **Serve with a simple HTTP server (recommended):**

  ```bash
  # Python 3
  python3 -m http.server 8000

  # Node.js
  npx http-server -p 8000
  ```

  Then navigate to `http://localhost:8000`.

## Accessing the Front End

* **Local:** Follow the steps under [Running the App](#running-the-app) to launch locally at `http://localhost:8000` or open `index.html` directly.

* **Online (GitHub Pages):**

  ```
  https://immy2good.github.io/drum-kit/
  ```

## Project Structure

```plaintext
drum-kit/
├── images/          # Button visuals/icons (if any)
├── sounds/          # Drum sound samples (.wav files)
├── index.html       # Main HTML file with drum pad layout
├── styles.css       # CSS styling and responsive layout
├── index.js         # JavaScript logic for event handling and animations
├── .gitattributes   # Git configuration
└── README.md        # This file
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to your branch: `git push origin feature/my-feature`
5. Open a pull request.

Be sure to follow the existing code style and include clear commit messages.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

Developed by Immy (immy2good).

* GitHub: [immy2good](https://github.com/immy2good)
* Email: [imran2good@hotmail.com](mailto:imran2good@hotmail.com)
