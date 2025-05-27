
---

````markdown
# 🧠 Core Package – InfoSnap CLI Web Scrapper

This package provides the core functionality for the `InfoSnap` CLI tool. It includes a helper function `showHelp()` that displays a styled help menu with all available commands for managing and interacting with data scraping sessions.

---

## 📦 Overview

The `core` package is designed to offer a built-in command-line help system for users of the `InfoSnap` tool. This tool allows you to start, view, manage, and delete scraping sessions, making it easy to extract and interact with structured web data using the browser extension.

---

## ✨ Features

- Styled and readable terminal help output
- List of supported CLI commands
- Descriptions for all major actions: starting, stopping, exporting, and viewing sessions

---

## 🛠️ Usage

 `--help` all how to use will show:


---

## 🚀 Commands Available

| Command                 | Description                                                              |
| ----------------------- | ------------------------------------------------------------------------ |
| `--start`               | Start the main scraping process. Requires the InfoSnap Chrome extension. |
| `--stop`                | Stop execution and exit the program.                                     |
| `--restart`             | Restart the application.                                                 |
| `--help`                | Display this help menu.                                                  |
| `--sessions`            | List all saved sessions.                                                 |
| `--session export <id>` | Export fine-tuned scraped data for the given session ID.                 |
| `--session view <id>`   | View filtered scraped data for the given session ID.                     |
| `--session raw <id>`    | View raw scraped data for the given session ID.                          |
| `--session delete <id>` | Delete a specific session by ID.                                         |
| `--session delete all`  | Delete all sessions and data.                                            |
| `--version`             | Display the current version of the tool.                                 |

---

## 🧪 Example

```bash
>>>>>> --start
```

---

## 📎 Notes

* Ensure the **InfoSnap Chrome Extension** is installed and active to collect data.
* This package assumes CLI interaction and is part of a larger scraping toolkit.

---

## 📁 Location

all result will be in results/

---

## 👤 Author

Maintained by timAdurah telegram @the_incognitus

```

Contact me if you need your copy @the_incognitus on telegram or check our telegram channel @consolesoft
```
