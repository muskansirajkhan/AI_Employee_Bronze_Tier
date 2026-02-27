🤖 AI Employee Vault 📂

AI-Powered File Organizer & Processor ✨

This project helps you:

📝 Drop files in the Inbox folder

📂 Automatically move them to Needs_Action

🤖 Process metadata using OpenAI GPT

📄 Create .md files with AI responses

Folders included:

Vault/Inbox – Place new files here

Vault/Needs_Action – Files copied here for action

Vault/Done – Completed files (optional)

Watchers & Scripts:

watchers/filesystem_watcher.py – Monitors Inbox & triggers AI

watchers/process_md.py – Helper script for processing .md files

replacements.txt – Example file for replacements

💡 Usage:

Set your OpenAI API key in .env file (DO NOT push this!)

Run filesystem_watcher.py

Drop a file in Inbox → watch AI work magic!

⚠️ Note: Keep .env and venv/ out of GitHub.
