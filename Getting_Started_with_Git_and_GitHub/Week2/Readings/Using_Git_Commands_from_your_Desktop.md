# Using Git Commands from your Desktop

In the previous lab you used a Cloud-based IDE to work with Git commands. In many cases, you will be developing code on your own workstation on your desktop/laptop. Linux systems  typically come pre-installed with Git commands or if needed you can install them using **dnf** on rpm based distributions (e.g. Red Hat / Fedora):

```bash
sudo dnf install git-all
```

or, apt on Debian-based distributions (e.g. Ubuntu):

```bash
sudo apt install git-all
```

On MacOS you can activate Git by typing:

```bash
git version
```

However if it is not installed, or if you want to update it, you can download and install the latest version of the [MacOS Git Installer](https://sourceforge.net/projects/git-osx-installer/files/git-2.23.0-intel-universal-mavericks.dmg/download?use_mirror=autoselect), and run the above command to verify the version.

On Windows based systems, you can install **Git Bash** by downloading the [Git for Windows](https://gitforwindows.org/) installer. Git Bash includes popular Linux Bash shell commands (such as ls, pwd, cat, etc.) as well as Git commands.

You can also get the [GitHub desktop](https://desktop.github.com/) for Windows and MacOS, which provides a UI for GitHub on your desktop.

When you are working with GitHub repositories from your desktop you will also need to setup an ssh key. 

**The remaining labs in this module are optional however recommended for those with a Windows desktop.** In the following labs you will install Git Bash on your Windows machine, and configure an ssh key to work with your GitHub repo using Git commands on your system.