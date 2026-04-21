# Cursor-setup-task
How I setup Cursor with extensions
# Cursor Setup Task

## Tools Installed
* **Cursor IDE**: AI-powered code editor.
* **Claude Code Extension**: Terminal based agentic AI tool.
* **Codex Extension**: AI agent on the side bar.
* **Git**: Command-line application for Windows that provides a Bash terminal emulator environment.


## Steps Completed
1. Installed Cursor IDE.
2. Created GitHb account 
3. Logged in Cursor IDE with GitHub account.
4. Installed Claude Code for VS Code extension.
5. Installed Codex extension.
6. Logged in to Claude Code.
7. Logged in to Codex.
8. Created this GitHub repository.
9. Installed Git Bash.
10. Cloned the repository locally and initialized the documentation.
11. Opened this Github repository in Cursor.
12. Edited the README.md file.
13. Pushed the README.md to GitHub.

## Issues & Solutions
* **Issue 1:** Could not login to Claude.
* **Solution:** Closed the web browser windows and re-entered the web links to login
* **Issue 2:** `Identity provider mismatch` popup appeared during login to Codex OpenAI.
* **Solution:** Searched on web browser how to login to OpenAI when encountering this error. Then I created a project and generated API key.
* **Issue 3:** Could not clone GitHub repository in Cursor by command palette.
* **Solution:** Ran the clone command in terminal using the following command:  `cd Users\hp\OneDrive\Documents\cursor\Cursor-setup-task`.
* **Issue 4:** When trying to clone the repository, I received an error stating that `'git' is not recognized as a cmdlet or function.`
* **Solution:** Asked Gemini AI Pro what was the meaning of this error and how to solve it. and then I downloaded and installed Git from the official [git-scm.com](https://git-scm.com/) website and restarted Cursor to refresh the terminal path accordingly.
* **Issue 5:** When attempting to commit my changes, a popup appeared saying: `Make sure you configure your "user.name" and "user.email" in git.`
* **Solution:** I opened the terminal and provided my identity to Git using the following commands: 
  * `git config --global user.name "Trulylaf13"`
  * `git config --global user.email "trulyaf@gmail.com"`