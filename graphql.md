# Setup for GraphQL classes

This is the setup document for Speeding Planet's GraphQL course. 

Courses can be conducted on Windows 8 or later, MacOS X Mojave (10.18) or later, and Linux (most modern versions). We recommend running any course on a computer with a modern processor, 8GB+ of RAM and at least 250GB of disk space.

Some software for this course may require Administrator/root access to install. 

Courses are **not** intended to run on a tablet, such as an Apple iPad or a Windows Surface or similar.

## Quick Checklist

Use this as a checklist to make sure your install is correct. Details follow below the checklist:

- [ ] Current Node.js (>=24) is [installed and configured](#nodejs-setup)
- [ ] A Git client (>=2.25) is [installed and usable](#source-control-using-git)
- [ ] A web browser is [installed, usable, and can access the internet](#web-browser)
- [ ] An Integrated Development Environment (IDE) or editor is [installed and usable](#editor--ide)
- [ ] Project setup as [below](#project-setup)

## Node.js setup

The class runs on the long-term support (LTS) version of Node.js, currently Node v24. You can download and install Node.js from https://nodejs.org/en/download. 

Once you have installed Node.js, test that it works at a command prompt. Open a terminal window/command prompt/Powershell window and enter the following:

```shell
node -v
```

It should report back the current version of Node. 

While you are there, also run this command:

```shell
npm -v
```

Which will check that `npm`, the Node Package Manager, is installed. As above, it should report back the current version of npm (v11 as of this writing).

### What if I need an older version of Node?

There are two possible solutions. The best solution is to use a Node version manager. Which one to use depends on your operating system:

- Windows, without/not using Windows Subsystem for Linux: use [nvm for Windows](https://github.com/coreybutler/nvm-windows)
- MacOS, Linux, Windows Subsystem for Linux: use [nvm](https://github.com/nvm-sh/nvm) 

## Source control using Git

We will be using [Git](https://git-scm.com/) for source control in class. You can install a basic version from the homepage, or use a graphic client if you prefer. 

Please use Git version 2.25 or later.

Your instructor should provide you with a URL for a repository. Please test whether you can pull from the repository before class.

## Web browser

- [Firefox](https://www.mozilla.org/en-US/firefox/browsers/)
- [Chrome](https://www.google.com/chrome/)
- [Edge](https://www.microsoft.com/en-us/edge)
- Other browsers (Internet Explorer, Safari, Brave, Opera, etc.) may work in class but are not supported and may lack critical features

## Editor / IDE

- [Visual Studio Code](https://code.visualstudio.com/) is strongly preferred, but others are available
  - Check out some [recommended extensions](vs-code-extensions.md) for VS Code.
- [WebStorm](https://www.jetbrains.com/webstorm/) or [IntelliJ](https://www.jetbrains.com/idea/), also by JetBrains
- SublimeText, Emacs, or vi/vim: if you like configuring your editor yourself
- Notepad++, TextMate, etc.: if you can't install any of the above
- The following editors are unacceptable:
  - Eclipse is not a viable choice. JavaScript support on Eclipse is a disaster.
  - Notepad is not a viable choice. It does not have enough features for you to be a productive developer

### What about using artificial intelligence (AI)?

Please read [A Note On AI](a-note-on-ai.md).

## Project setup

1. Using Git, download the class repository from the URL proivded by your instructor.
1. Open up a command prompt in the repository directory
  1. Run `npm install`. There should be no errors, though there may be some audit warnings.
  1. Run `npm test`. All tests should pass.
1. If your editor or IDE supports projects, open the repository directory as a project. 

## Questions?

Please contact your instructor!


