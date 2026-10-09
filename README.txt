AURA AI — Windows release package

Install:
1. Download and run AURA-Setup.exe on Windows 10/11, 64-bit.
2. Enter your own Ollama Cloud API key. It is saved in Windows Credential
   Manager on this PC; it is not included in this download.
3. Optionally select Offline AI. Setup installs Ollama with Windows Package
   Manager and downloads the chosen Qwen 2.5 VL model. Model-size and RAM
   figures shown by setup are estimates. Ensure you have enough free disk
   space and memory before selecting a model.

Offline AI requires an internet connection during the initial Ollama/model
download. After installation, local inference can run without internet.
Cloud AI and automatic updates require internet. The Cloud API key is required
by this release even when Offline AI is selected.

The installer contains the packaged AURA application and browser extension,
not the project source tree. The browser extension is separately installable:
extract AURA_Browser_Extension.zip, open your Chromium browser's extensions
page, enable Developer mode, choose Load unpacked, and select the extracted
folder. Pair it through AURA Settings.

Updates are not automatic in this initial package. Download and run the next
official AURA-Setup.exe release to update the installed application. Your
AURA settings and chat history are stored separately from the program files.

Only download these files from the official AURA release page. Check
SHA256SUMS.txt when hashes are provided. No API key is included in the
installer or this release package.