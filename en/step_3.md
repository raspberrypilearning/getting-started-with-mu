## Installing Mu

Follow the Mu installation guide for your operating system.

--- collapse ---

---
title: Raspbian (Raspberry Pi)
---

+ Open a terminal window.

![pi open terminal](images/pi-open-terminal.PNG)

+ Type in the following command to install Mu.

```bash
sudo apt-get install mu
``` 

![pi install mu](images/pi_install_mu.gif)

+ Start Mu by going to the menu and selecting **Programming** > **Mu** from the menu.

--- /collapse ---

--- collapse ---

---
title: Windows
---

Mu can be installed on Windows using either:

+ A pre-built installer — really useful if Python isn't installed on your computer or your don't have permissions to use the command prompt

+ The command line and `pip` — recommended if you already have Python installed

#### Pre-built installer

The Mu Installer contains all you need to get started programming with Python.

+ Download the installer - TODO - this needs changing when there is a direct link from the Mu website.

[Windows 64-bit installer](https://s3-eu-west-2.amazonaws.com/mu-builds/windows/mu_2018-03-16_18_52_master_9b119d5_64bit.exe)

[Windows 32-bit installer](https://s3-eu-west-2.amazonaws.com/mu-builds/windows/mu_2018-03-16_18_56_master_9b119d5_32bit.exe)

+ Run the installer and click **Next** to start.

+ Review the license agreement, and then click **Agree**.

+ Choose whether you want Mu to be available for all users or just you, and click **Next**.

+ Select an installation location and click **Next**.

+ Mu will now install — click **Finish** when the process is complete.

![windows install mu](images/windows_mu_installer.gif)

+ Run Mu by selecting **Mu** from the Start menu.

#### Install using pip

+ Open a command prompt by clicking **Start** > **Windows System** > **Command Prompt**, or typing 'command' into the Start menu's search bar.

![windows command prompt](images/windows_command_prompt_app.PNG)

+ Enter this command to install the Mu module:

```bash
pip3 install mu-editor
```

![windows pip install mu](images/windows_install_mu.gif)

If you have problems, have a look at our [_Using pip on Windows_](https://projects.raspberrypi.org/en/projects/using-pip-on-windows) resource.

+ Run Mu by entering `mu` into the command prompt.

```bash
mu
```

+ To create desktop and Start menu shortcuts for Mu, install and use the shortcut utility by entering the following into the command prompt:

```bash
pip3 install shortcut
shortcut mu
```

--- /collapse ---

--- collapse ---

---
title: macOS
---

+ Open a terminal by clicking **Applications** > **Utilities** > **Terminal**, or type 'terminal' into Spotlight Search.

+ Enter this command to install Mu:

```bash
pip3 install mu-editor
```

![mac install mu](images/mac_install_mu.gif)

+ Run Mu by entering `mu` into the terminal window.

```bash
mu
```

+ To create desktop and Launcher shortcuts for mu, install and use the shortcut utility using these commands:

```bash
pip3 install shortcut
shortcut mu
```

--- /collapse ---

--- collapse ---

---
title: Linux
---

+ Open a terminal window.

+ Enter this command to install Mu:

```bash
sudo pip3 install mu-editor
```

![linux install mu](images/linux_install_mu.gif)

+ Run Mu by entering `mu` in the command prompt window.

+ To create desktop and application menu shortcuts for Mu, install and use the shortcut utility using these commands:

```bash
sudo pip3 install shortcut
shortcut mu
```

--- /collapse ---
