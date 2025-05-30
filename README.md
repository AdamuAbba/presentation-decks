# presentation-decks

This repository contains all my open-source presentations. Every talk, lecture, or meetup slide deck I create in Markdown will live here.

I prefer writing Markdown over using tools like Google Slides or Canva. My workflow is entirely terminal-based and keyboard-agnostic so markdown is just convenient for me.

## Terminal Slides Renderer

Slides are rendered in the terminal using [`presenterm`](https://github.com/mfontanini/presenterm) a TUI markdown terminal slideshow tool written in rust.

### Install `presenterm`

- Visit the repo: [mfontanini/presenterm](https://github.com/mfontanini/presenterm)
- Follow the build and install instructions provided there.

### Recommended Terminal

- I use [`wezterm`](https://github.com/wezterm/wezterm), which supports modern graphics protocols required to render images directly in the terminal but you can use any modern terminal emulator that supports images.
- You can install it from [wezterm/wezterm](https://github.com/wezterm/wezterm) and use it with `presenterm` for best results.

## Folder Structure

```text
presentation-decks/
│ 
├── <domain>/
│   └──<topic>/
│      │── speaker_notes.md  # detailed  slide decks
│      │── slide_deck.md     # Markdown slide decks
│      └── assets/           # Images used in slides 
│          └── <image1.png>
├── demo/
│   └── <screenshot.png>
├── LICENSE
└── README.md
```

## Clone and Use

```bash
git clone https://github.com/AdamuAbba/presentation-decks.git
cd presentation-decks
presenterm nostr/intro/slide_deck.md
```

## Dotfiles / Setup

<img src="./demo/Screenshot 2025-05-31 at 12.15.30 AM.png" alt="My terminal setup" width="80%">

If you're interested in how my terminal environment is configured:

- Visit my dotfiles: [github.com/AdamuAbba/dotfiles](https://github.com/AdamuAbba/dotfiles)

## License

MIT License. See [LICENSE](LICENSE) for full details.
