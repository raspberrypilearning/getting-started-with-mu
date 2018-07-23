## Installing Mu

[Mu](https://codewith.mu) will work on most operating systems and you should follow the installation instructions for your operating system.

--- collapse ---

---
title: Raspberry Pi
---

--- task ---

Open the **Recommended Software** application from the **Preferences** menu.

![pi recommended software](images/pi-rec-software.png)

--- /task ---

**Note:** if your version of Raspbian doesn't include the **Recommended Software** application you should [update your Raspberry Pi](https://www.raspberrypi.org/documentation/raspbian/updating.md) by opening a terminal and running the commands:

```bash
sudo apt-get update
sudo apt-get dist-upgrade
```

--- task ---

Select Mu from the list of applications to install.

![pi select mu](images/pi-rec-software-select-annotated.png)

--- /task ---

--- task ---

Click **OK** to start the install.

![pi installing mu](images/pi-rec-software-install.png)

--- /task ---

--- task ---

Start Mu by going to the menu and selecting **Programming** > **Mu** from the menu.

![pi open mu](images/pi_open_mu.PNG)

--- /task ---

--- /collapse ---

--- collapse ---

---
title: Windows
---

The Mu Installer contains all you need to get started programming with Python.

--- task ---

Download the windows installer from the (codewith.mu/en/download)[https://codewith.mu/en/download] page and follow the (Mu install instructions for Windows)[https://codewith.mu/en/howto/install_windows].

![download mu](images/download_mu.PNG)

![mu windows install instructions](images/windows_install_instructions.PNG)

--- /task ---

--- task ---

Start Mu by opening it from the start menu.

![windows start mu](images/windows_start_mu.png)

--- /task ---

--- /collapse ---

--- collapse ---

---
title: macOS
---

--- task ---

Download the windows installer from the (codewith.mu/en/download)[https://codewith.mu/en/download] page and follow the (Mu install instructions for macOS)[https://codewith.mu/en/howto/install_macos].

![download mu](images/download_mu.PNG)

![mu macos install instructions](images/macos_install_instructions.PNG)

--- /task ---

--- task ---

Start Mu by opening it from the applications menu.

![macos start mu](images/macos_start_mu.png)

--- /task ---

--- /collapse ---

--- collapse ---

---
title: Linux
---

--- task ---

Open a terminal window.

--- /task ---

--- task ---

Enter this command to install Mu:

```bash
sudo pip3 install mu-editor
```

![linux install mu](images/linux_install_mu.gif)

--- /task ---

--- task ---

Run Mu by entering `mu` in the command prompt window.

--- /task ---

--- task ---

To create desktop and application menu shortcuts for Mu, install and use the shortcut utility using these commands:

```bash
sudo pip3 install shortcut
shortcut mu
```

--- /task ---

--- /collapse ---

--- collapse ---

---
title: Advanced - Windows / macOS install using pip
---

If you already have Python 3 installed you can use `pip` to install Mu.

--- task ---

### Windows

Open a command prompt by clicking **Start** > **Windows System** > **Command Prompt**, or typing 'command' into the Start menu's search bar.

### MacOS

Open a terminal by clicking **Applications** > **Utilities** > **Terminal**, or type ‘terminal’ into Spotlight Search.

--- /task ---

--- task ---

Enter this command to install the Mu editor:

```bash
pip3 install mu-editor
```

![windows pip install mu](images/windows_install_mu.gif)

![macos pip install mu](images/macos_install_mu.gif)

--- /task ---

If you have problems, have a look at our [_Using pip on Windows_](https://projects.raspberrypi.org/en/projects/using-pip-on-windows) resource.

--- task ---

Run Mu by entering `mu` in the command prompt window.

```bash
mu
```

--- /task ---

--- task ---

To create desktop and Start menu shortcuts for Mu, install and use the shortcut utility by entering the following into the command prompt:

```bash
pip3 install shortcut
shortcut mu
```

--- /task ---

--- /collapse ---

--- /collapse ---