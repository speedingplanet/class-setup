# Node.js setup

This is the setup document for Speeding Planet's Node.js course. 

Courses can be conducted on Windows 8 or later, MacOS X Mojave (10.18) or later, and Linux (most modern versions). We recommend running
any course on a computer with a modern processor, 8GB+ of RAM and at least 250GB of disk space.

Courses are intended to be run on a computer with Administrative access, at least at the point of install of the software below.

Courses are **not** intended to run on a tablet, such as an Apple iPad or a Windows Surface or similar.

## Required Software

### Node.js

You can download Node.js one of two ways: either download a binary directly or use a Node version manager. We STRONGLY recommend using a version manager, if the option is available. This has the benefit of preserving your current Node configuration while allowing alternate configurations for the class, experimentation, prototyping, etc. 

#### Direct download

- [Node.js](https://nodejs.org/en/download): the engine for the course. Please use at least the most recent long term support (LTS) version (currently 22.x). Older versions are possible, with advanced notice and development time.

#### Version manager

- Mac and Linux: Install and use [nvm](https://github.com/nvm-sh/nvm). Install Node 22 using nvm.
- Windows: Install and use [nvm-windows](https://github.com/coreybutler/nvm-windows). Install Node 22 using nvm. 

#### Other options

You could use a package manager like homebrew, ports, apt, chocolatey, etc. to install the latest version of Node. 

### Editor or IDE

- Your instructor will be using [Visual Studio Code](https://code.visualstudio.com/) 
- There are other editors and IDEs out there that will work well in class. VS Code is not required.
- There are also some editors that will not work in class:
  - Eclipse is not a viable choice. JavaScript support on Eclipse is a disaster.
  - Notepad is not a viable choice. It does not have enough features for you to be a productive developer

#### Visual Studio code configuration

If you are using Visual Studio Code, please install the following extensions:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) code style enforcer (and also formatter)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) code formatter
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) lightweight enhancement of code suggestions

### Other software

- [Git](https://git-scm.com/): the course relies on a repository stored in git and assumes you are conversant with it. 

## Optional Software

- Terminal software: 
	- Mac: Usually [iTerm2](https://www.iterm2.com/) or something similar
	- Windows: [Windows Terminal](https://aka.ms/terminal) or [Cmder](https://cmder.app/) or similar