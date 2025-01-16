# Intermediate Apollo

This is a front-end focused class, accessing Apollo Client via React.

## General setup for Front-end JavaScript classes

Courses can be conducted on Windows 8 or later, MacOS X Mojave (10.18) or later, and Linux (most modern versions). We recommend running
any course on a computer with a modern processor, 8GB+ of RAM and at least 250GB of disk space.

Courses are intended to be run on a computer with Administrative access, at least at the point of install of the software below.

Courses are **not** intended to run on a tablet, such as an Apple iPad or a Windows Surface or similar.

### Required Software

- [Node.js](https://nodejs.org): the engine for most JavaScript classes. Node version 16 or later should be sufficient for class. Older versions are possible, with advanced notice and development time.
- [Git](https://git-scm.com/): Source control management, also used by many tools; version 2.25 or later strongly preferred
- A web browser, can be any of
  - [Firefox](https://www.mozilla.org/en-US/firefox/browsers/)
  - [Chrome](https://www.google.com/chrome/)
  - [Edge](https://www.microsoft.com/en-us/edge)
  - Other browsers (Internet Explorer, Safari, Brave, Opera, etc. may work in class but are not supported and may lack critical features)
- An editor
  - [Visual Studio Code](https://code.visualstudio.com/) is strongly preferred, but others are available
    - Check out some [recommended extensions](vs-code-extensions.md) for VS Code.
  - [WebStorm](https://www.jetbrains.com/webstorm/) or [IntelliJ](https://www.jetbrains.com/idea/), also by JetBrains
  - SublimeText, Emacs, Vi(m): if you like configuring your editor yourself
  - Notepad++, Atom, TextMate, etc.: if you can't install any of the above
  - Eclipse is not a viable choice. JavaScript support on Eclipse is a disaster.
  - Notepad is not a viable choice. It does not have enough features for you to be a productive developer
- Class source code. A GitHub repository for the class source code will be set up in time for class. It will include demos, labs, and other materials as appropriate.

### Optional Software

These will make your development experience better.

#### Windows

- Command prompt: [Cmder](https://cmder.app/) or [Hyper](https://hyper.is/)

#### MacOS

- Terminal: [iTerm2](https://www.iterm2.com/) or [Hyper](https://hyper.is/)
- Shell: [Fish](https://fishshell.com/) or [zsh](http://zsh.sourceforge.net/), though bash is fine

## Visual Studio Code Extensions

A list of Visual Studio Code extensions we use in courses. Not intended to be exhaustive. All of these are optional.

### General

#### Required

These will actually make your experience in VS Code better:

- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

#### Optional

- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
- [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser) Handy lightweight utility for opening files in a browser. Does not use a web server, unlike Live Preview or similar extensions.
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) Fancy, if overly complicated, git interface; great for comparing branches

### Themes

None of these are required. But folks sometimes ask what I'm using.

- [Cobalt2 Theme Official](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) I sometimes use the vivid version in course
- [Overnight](https://marketplace.visualstudio.com/items?itemName=cev.overnight)
- [LubnaDev-Theme](https://marketplace.visualstudio.com/items?itemName=lubnadev.lubnadev-theme)
- [Tomorrow Night Blue](https://marketplace.visualstudio.com/items?itemName=gerane.Theme-TomorrowNightBlue) Easy on the eyes

### Decoration

These make the experience of using VS Code nicer. Not required.

- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) Colors VS Code according to your project (red for Angular, blue for React, etc.; can customize according to prefs)

### JavaScript

#### Required

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) code style enforcer (and also formatter)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) code formatter
  - To configure these two together, look at [this doc](linting-configuration.md).

#### Optional

- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
- [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) Run npm scripts inside the editor

## React configuration

Additional configuration for classes which cover or use React

- Visual Studio Code setup
  - We don't have a recommended extension for GraphQL at the moment. All the available extensions are mediocre at best. We will talk about options when class starts.
