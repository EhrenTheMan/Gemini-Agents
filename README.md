# Gemini-Agents
A small list of Gemini CLI Agents I have worked on. Most of which are for note-taking and helping with homework
## Gemini-Scribe: an all-in-one note-taking assistant for Obsidian.
  -  Obsidian Scribe is a specialized, autonomous note-taking assistant for Obsidian that executes complex file manipulation commands based on specific tags within your markdown notes. It prioritizes rigorous brevity in its output while managing your Obsidian vault's content.

# Prerequisites
  - GeminiCLI
    - Can be installed with: `npm install -g @google/gemini-cli`

# Installation
## To install all agents
  - Navigate to the green Code button
  - Select the bottom option "Download ZIP."
  - When downloaded, open the file, or extract it somewhere temporary
  - navigate into "Gemini-Agents-Main."
  - Copy the ".gemini" folder
  - Paste the folder into "C:\Users\{youruser}."
  - Done!

# How to enable/use a skill
  ## Obsidian-Scribe
  ### How to enable
  - Open Obsidian on your machine
  - In the bottom left of Obsidian, right-click on the vault dropdown and select "Open in System Explorer."
  - From there,
    -  On Windows:
      - Click on the location of your Vault, and type `cmd`.
      - When the Command Prompt window opens, type gemini to start GeminiCLI in your working directory (your vault).
      - If the skill is not automatically enabled, type `/skills enable obsidian-scribe' into the gemini commandline.
  ### How to use Obsidian Scribe
  - Obsidian-Scribe supports several commands that fall under two categories. Commandline commands and Note commands.
  - **Before you use those**, make sure you tell the agent where you are working (if you are working in a specific directory).
    e.g., "I am currently in Work/Meeting-notes."

    ### In-Note Commands
      - 

    ### Commandline Commands
      - `rescan` - This command tells the agent to rescan the Note you are currently working on. **ONLY scans the note you told it you are working on.**
