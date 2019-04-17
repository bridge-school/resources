# Bridge School Resources
### A community-led repo of config files and other useful setup tips for Bridge development students
*Contribution guidelines and full README in progress*
***
&nbsp;
## I. Command-line text editors
**What they are:** Tools for editing plain-text files from the command line.

**Why they're useful:** For creating and editing the various config files in this repo. Moreover, many git commands will open a text editor for further input.

**Available options:** (We could link to another md file to discuss options for different systems.)

*Note to contributors: Whenever we need step-by-step instructions throughout this repo, we could perhaps use nano commands, since it seems to be a good introductory editor. I think it can also be used on a variety of systems.*

**Essential skills/commands:**
In your text editor of choice, learn to open/create a file, copy, paste, delete a line, quit (i.e. exit without save), save and exit. (We could outline how to do these things in nano.)

**Essential setup:**
How to set up your favourite text editor for use with git.

**If you want to know more:**
Intro to advanced text editors such as vim and emacs.

&nbsp;
&nbsp;
***
&nbsp;
&nbsp;
## II. .gitconfig
**What it is:**

**Why it's useful:** For a variety of git customization, such as adding colours to make git diffs easier to read, and for creating aliases, which are short versions of frequently-used git commands.

**Essential setup:** Git aliases don't have to live in a `.gitconfig` file — we could also put them in a `bash_profile`, for instance. But for the sake of organization, it makes sense to start by keeping them in a `.gitconfig` along with other git-related setup.

**Starter config file:** Available [here](https://github.com/bridge-school/resources/blob/master/gitconfig_example_files/starter_gitconfig_example/.gitconfig).

**How to install and use this config file:**
(Should we mention that a `.gitconfig` file could be installed in different places?)

**If you want to know more:**
* A more advanced example of a `.gitconfig` is [here](https://github.com/bridge-school/resources/blob/master/gitconfig_example_files/intermediate_gitconfig_example/.gitconfig).
* You can also update a `.gitconfig` file from the command line with the `git config` command.

&nbsp;
&nbsp;
***
&nbsp;
&nbsp;
## III. Shell management tools and configuration files
*Note to contributors:*

*These are such big topics that I hope we can start by focusing on examples of a few practical things that Bridge students could start with to improve their daily workflow — i.e. creating aliases to avoid typing out full commands, and shortcuts for navigating to common directories.*

*We should clarify how many of these files are really needed. If Bridge students have a .zshrc, do they also need a .bashrc or bash_profile? If they have more than one, how do we set up the files so they interact? i.e. at one point I had to put `source ~/.bash_profile` at the end of my `./zshrc`*.

*We should also cover Mac/Linux/Windows.*

## i. Bash
### a) .bashrc
**What it is:**

**Why it's useful:**

**Starter config file:**

**How to install and use this config file:**

&nbsp;
&nbsp;
### b) bash_profile
**What it is:**

**Why it's useful:**

**Starter config file:**

**How to install and use this config file:**

&nbsp;
&nbsp;
## ii. Z shell (zsh)
### a) oh-my-zsh
**What it is:**

**Why it's useful:**

**Essential setup:**
Link to instructions for theme setup and customizing the prompt.

**If you want to know more:**
Using oh-my-zsh plugins.

&nbsp;
&nbsp;
### b) .zshrc
**What it is:**

**Why it's useful:**

**Starter config file:** Available [here](https://github.com/bridge-school/resources/blob/master/zshrc_example_files/starter_zshrc_example/.zshrc).

**How to install and use this config file:**

**If you want to know more:**

&nbsp;
&nbsp;
***
&nbsp;
&nbsp;
## IV. Code editor configuration and efficiency tools
## i. VS Code
### a) Settings and Extensions
*Should Settings and Extensions be two separate headings?*

**What they are:**

**Why they're useful:**

**Starter config file:** Available [here](https://github.com/bridge-school/resources/blob/master/vscode_example_files/starter_settings_example/settings.json).

**How to install and use this config file:**

**If you want to know more:**

&nbsp;
&nbsp;
### b) Efficiency tools
**What they are:**

**Why they're useful:**

**Available options:**
* Keyboard shortcuts/customizing keybindings.json
* Emmet expanders/customizing Emmet
* Snippet extensions
* Building custom snippets