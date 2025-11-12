# Auto Whisk - Prompt Automator for Whisk [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 

A Chrome extension to automate your entire workflow with Google's Whisk (on `labs.google`). Batch-send prompts, save time, accelerate creativity, and take full control of your process!

[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/auto-whisk-prompt-automat/gedfnhdibkfgacmkbjgpfjihacalnlpn)

## Key Features

* **Batch Prompting:** Input a list of prompts directly or upload from a `.txt` file.
* **Auto Image Download:** Automatically scans for and downloads newly generated images to a folder you specify.
* **Full Control:** Start, Pause, Resume, and Stop the automation at any time.
* **Two Start Modes:**
    * `Create New Project`: Automatically navigates and creates a new Whisk project.
    * `Run on This Project`: Starts the automation on the Whisk project you currently have open.
* **Advanced Customization:**
    * Set wait times (fixed or random) between prompts to manage generation speed.
    * Set a repeat count for *each* prompt in your list.
    * Start from a specific prompt number (e.g., start from prompt #50).
* **Smart Error Handling:** Automatically detects when the Whisk queue is full (send button is disabled), waits, retries, and even auto-refreshes the page to ensure the process continues.
* **History & Logging:** Track progress in the "History" tab and easily copy any prompts that failed.

## How to Use

1.  Install the extension from the Chrome Web Store.
2.  Go to the [Google Labs Whisk tool](https://labs.google/fx/tools/whisk).
3.  Click the extension icon (the duck) in your Chrome toolbar to open the Side Panel.
4.  **"Control" Tab:**
    * Paste your list of prompts (one per line) into the textarea.
    * Alternatively, click "Import from file" to load prompts from a `.txt` file.
5.  **"Settings" Tab:**
    * Enable **"Auto-download images"** and set a **"Download Folder"** name (e.g., `Whisk Downloads`).
    * Set the **Wait time** (e.g., 10-20 seconds) to give Whisk time to generate images.
    * Set **"Runs per prompt"** if you want each prompt to run multiple times.
6.  **Return to "Control" Tab:**
    * Click the **"Start"** button.
    * You will see two options: "Create New Project" or "Run on This Project". Choose one.
    * The tool will begin processing your prompts.

## Important Notes

* **Keep Panel Open:** Always keep the Whisk tab and the extension's Side Panel open while the tool is running.
* **Use Separate Window:** For best stability, run the tool in a separate browser window.
* **Disable Download Prompt:** If using "Auto-download", go to your browser's download settings (`chrome://settings/downloads`) and turn off **"Ask where to save each file before downloading"** for a seamless experience.
