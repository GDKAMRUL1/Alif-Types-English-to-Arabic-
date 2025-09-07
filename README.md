# Alif - English to Arabic Transliterator

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Overview

Alif is a desktop application built with Python and Tkinter that allows users to transliterate English/Arabizi text into Arabic. It features live transliteration, editable mapping rules, right-to-left rendering, and convenient output management.

## Features

* Live transliteration as you type.
* Manual transliteration button.
* Swap input and output text.
* Clear, copy, and save output.
* View and export transliteration rules.
* Developer info accessible from the Help menu.

## Installation

1. Ensure Python 3.9+ is installed.
2. Clone this repository:

   ```bash
   git clone https://github.com/GDKAMRUL1/Alif.git
   ```
3. Navigate to the project directory and install dependencies:

   ```bash
   cd Alif
   pip install -r requirements.txt
   ```

## Running the App

Run the application using:

```bash
python app.py
```

## Usage

* **Live Transliteration:** Enable the checkbox to transliterate as you type.
* **Transliterate Now:** Convert input text manually.
* **Swap:** Exchange input and output text.
* **Clear:** Clear both input and output panes.
* **Copy Output:** Copy Arabic text to clipboard.
* **Save Output:** Save Arabic text as a `.txt` file.
* **View/Export Mapping:** View current mapping rules or export them to JSON.

## Build Executable (Optional)

To build a standalone Windows executable:

1. Install PyInstaller:

   ```bash
   pip install pyinstaller
   ```
2. Run:

   ```bash
   pyinstaller --name Alif --onefile app.py
   ```
3. The executable will be available in the `dist/` folder.

## Developer Info

* Name: KAMRUL MOLLAH
* Email: [mkamrulislam599@gmail.com](mailto:mkamrulislam599@gmail.com)
* GitHub: [GDKAMRUL1](https://github.com/GDKAMRUL1)
* Website: [kamrulmollah.com](https://kamrulmollah.com)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
