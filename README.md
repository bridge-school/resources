
## Bridge School Resources
### A community-led repo of config files and other useful setup tips for Bridge development students
*Contribution guidelines and full README in progress*

### I. Command-line text editors
**What they are:**
**When they're useful:** For creating and editing the various config files in this repo. Also, many git commands will open a text editor for further input.
**Available options:**
- Many options are available, and some
- *Note to contributors: We could maybe use nano for step-by-step examples throughout this repo, since it is a basic and widely-available editor*
**Essential skills/commands:**
- In your text editor of choice, learn to open/create a file, copy, paste, delete a line, quit (i.e. exit without save), save and exit.
**Essential setup:**
- How to set up your favourite text editor to use with git
**If you want to know more:**
- Advanced text editors such as vim and emacs

### II. .gitconfig
**What it is:** A text file that
**When/why it's useful:** For a variety of git customization: adding colours to make git diffs easier to read, and creating aliases, which are short versions of common commands.  **Essential setup:**
- A `.gitconfig` file can live in different places...
- Git aliases don't have to live in a `.gitconfig` file — they could also live in a `bash_profile`, for instance. But for the sake of organization, it makes sense to start by keeping them in a `.gitconfig` along with other git-related setup.
**Starter config file:**
**How to install and use this config file:**
**Intermediate config file:**
**If you want to know more:**
- You can also update a `.gitconfig` file from the command line with the `git config` command.

### III. Shell management tools and configuration files
*Notes to contributors:*
* *These are such big topics that I hope we can start by focusing on examples of a few practical things that Bridge students could start with to improve their daily workflow — i.e. creating aliases to avoid typing out full commands, and shortcuts for navigating to common directories.*
* *We should clarify how many of these files are really needed. If Bridge students have a .zshrc, do they also need a .bashrc or bash_profile? If they have more than one, how do the files interact? i.e. at one point I had to put `source ~/.bash_profile` at the end of my `./zshrc`*
* *We should cover different systems*

####i. Bash
#####a) .bashrc
**Starter config file:**
**How to install and use this config file:**

#####b) bash_profile
**Starter config file:**
**How to install and use this config file:**

####ii. Z shell (zsh)
#####a) oh-my-zsh
**What it is:**
**When/why it's useful:**
**Essential setup:**
* Link to instructions for theme setup and customizing the prompt
**If you want to know more:**
- Using oh-my-zsh plugins

#####b) .zshrc
**What it is:**
**When/why it's useful:**
**Starter config file:**
**How to install and use this config file:**
**If you want to know more:**


### IV. Code editor configuration and efficiency tools

####i. VS Code
#####a) settings.json
**What it is:**
**When/why it's useful:**
**Starter config file:**
**How to install and use this config file:**
**If you want to know more:**

#####b) Efficiency tools
* keyboard shortcuts
* Emmet expanders
* snippets
* building custom snippets