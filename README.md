An Espanso package to type Hungarian accents using a letter-first paradigm (type the base letter before the accent modifier).

# Installation

Assumptions:

* Basic familiarity with installing software on your system

Prerequisites:

* [Espanso](https://espanso.org/install/)

> [!NOTE]
> Git is not required on the target system.

**Step-by-step installation:**

1. Open your terminal:
   * **Windows:** Press the Windows button, type `terminal` or `powershell`, and press Enter
   * **macOS:** Press `Cmd + Space`, type `terminal`, and press Enter
   * **Linux:** Press `Ctrl + Alt + T` or search for "Terminal" in your applications

2. Copy and paste the following command into your terminal (right-click and select "Paste", or press `Ctrl + Shift + V` on Linux, `Cmd + V` on macOS, or right-click in Windows terminal):

```bash
espanso install hungarian-accents --git https://github.com/magyariakos/espanso-hungarian-accents --external
```

3. Press `Enter` to run the command

# Usage

Type the base letter followed by an accent modifier. For example:

* `a'` → á
* `e'` → é
* `o:` → ö
* `u:` → ü
* `o"` → ő
* `u"` → ű

**Example:**
Typing `U:dv, vila'g!` produces `Üdv, világ!`
