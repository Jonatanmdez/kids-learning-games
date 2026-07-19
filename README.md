# Kids Learning Games

A collection of simple, touch-friendly learning games designed for a four-year-old. Each game is a standalone HTML file containing its own HTML, CSS, and JavaScript, with no external runtime dependencies.

> [!CAUTION]
> # VIBE-CODING DISCLAIMER
>
> **This project was created through vibe coding with AI assistance.** The code, educational content, translations, accessibility behavior, Chinese vocabulary, pronunciation prompts, and game mechanics have not been professionally audited or validated by educators, linguists, child-development specialists, accessibility experts, security professionals, or native speakers.
>
> The games are provided as an experimental personal project, not as certified educational software. They may contain bugs, inaccurate translations, unsuitable difficulty choices, inconsistent pronunciation, accessibility limitations, or behavior that varies between browsers and Apple devices. Speech output depends on voices installed on the device and may not always be available or accurate.
>
> **An adult should review and supervise the games before and during use.** Do not rely on this project as a child's sole learning resource. Independently verify educational and language content, especially Chinese vocabulary and pronunciation, before teaching from it. Use the software at your own discretion and risk.

## Games

- `index.html` — multilingual launcher menu for all games.
- `juego-chino-panda.html` — introductory Chinese listening and picture-matching game.
- `juego-chino-panda-v2.html` — expanded Chinese game with categories and difficulty levels.
- `cuenta-los-objetos.html` — count objects from one to ten.
- `completa-el-patron.html` — complete simple visual patterns.
- `busca-el-intruso.html` — find the picture that does not belong.
- `ordena-la-secuencia.html` — arrange everyday events in the correct order.
- `laberinto-de-caminos.html` — guide an animal through short grid mazes.
- `prepara-la-mochila.html` — choose suitable objects for different activities.
- `elige-la-ropa.html` — choose clothing for weather and everyday situations.
- `empareja-las-sombras.html` — match objects and animals to their silhouettes.
- `memoria-de-parejas.html` — turn over cards and find matching pairs.
- `mezcla-los-colores.html` — learn the results of simple color mixtures.
- `semaforo.html` — practise when to stop, wait, and go at traffic lights.

## Languages

The interface supports:

- Spanish
- English
- Simplified Chinese

The selected language is stored locally when the browser permits it. It is also included in the page URL as a fallback for locally opened files.

## Running the games

Open `index.html` to use the game launcher, or open any individual `.html` file directly in Safari or another modern browser. No installation, package manager, build step, web server, or internet connection is required.

For example:

```text
file:///path/to/cuenta-los-objetos.html?lang=en
```

Available language parameters are `es`, `en`, and `zh`.

## Intended devices

The games are designed primarily for:

- iPhone
- iPad
- Mac

Layouts use large touch targets, responsive sizing, Apple safe-area insets, and reduced-motion preferences where applicable.

## Audio

Spoken instructions use the browser's Web Speech API and therefore depend on the voices installed on the device. Safari may require the user to start the game or press the speaker button before speech can play. If a matching Spanish, English, or Mandarin voice is unavailable, spoken output may be missing or inconsistent.

## Privacy and dependencies

- No advertising or analytics.
- No user accounts.
- No external JavaScript frameworks.
- No network requests required by the games.
- Progress and language preferences may be stored only in the browser's local storage.

## Development

The project intentionally keeps each game in one portable HTML file. Changes should preserve offline operation, touch usability, multilingual behavior, and compatibility with Safari on Apple devices.
