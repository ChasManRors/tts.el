# macOS TTS for Emacs (`tts.el`)

An Emacs Lisp extension for smooth, continuous text-to-speech on macOS Apple Silicon using the built-in `say` command.

# macOS TTS for Emacs (`tts.el`)

An Emacs Lisp extension for smooth, continuous text-to-speech on macOS using the built-in `say` command.

## Features
- Continuous paragraph reading (`C-c S`)
- Single-paragraph reading (`C-c s`)
- Instant stop (`C-c x`)
- Automatic scrolling and highlighting
- Works fully asynchronously — no freezing Emacs

## Installation
Copy `tts.el` into `~/.emacs.d/` and add to your `init.el`:
```elisp
(load "~/.emacs.d/tts.el")

## Usage
| Key     | Action                            |
| ------- | --------------------------------- |
| `C-c s` | Speak current paragraph/region    |
| `C-c S` | Continuous reading through buffer |
| `C-c x` | Stop speech immediately           |


