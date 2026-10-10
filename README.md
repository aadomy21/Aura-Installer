# AURA AI

AURA AI is a Windows desktop assistant with a quick-access overlay, AI chat, and a browser extension for supported Chromium browsers.

## Download and install

1. Open the [AURA AI Releases](https://github.com/aadomy21/Aura-Installer/releases) page.
2. Download and run **`AURA-Setup.exe`** from the latest release.
3. Follow the setup instructions and enter your own Ollama Cloud API key when prompted.

You only need to download **`AURA-Setup.exe`** to install the app. Setup downloads and verifies the app runtime during installation

AURA requires your own Ollama Cloud API key for cloud AI features. Setup stores the key in Windows Credential Manager; it is not included with the download. You get the ollama cloud api key from [Here](https://ollama.com/settings/keys) **DONT SHARE IT OR ELSE YOUR APP WILL BE SLOWER**

## Optional offline AI

During setup, you can optionally install Ollama and download a local AI model. This requires additional disk space, memory, and an internet connection for the initial downloads. You can skip this option and use cloud AI.

## Browser extension

The browser extension is optional and is not installed automatically. To add it:

1. Download `AURA_Browser_Extension.zip` from the same release and extract it.
2. Open your Chromium browser’s extensions page, enable **Developer mode**, and select **Load unpacked**.
3. Choose the extracted extension folder and pair it through AURA Settings.

## Release files

The Releases page may include:

- **`AURA-Setup.exe`** — Installer to download and run.
- **`AURA_Browser_Extension.zip`** — Optional browser extension.
- **`README.txt`** — Release-specific installation notes.

## Updates

AURA checks for newer releases and prompts before installing an update. Updates require an internet connection.
