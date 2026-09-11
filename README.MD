<p align="right">
  <a href="Instructivo_ES.md">Español</a>
  &nbsp;•&nbsp;
  <strong>English</strong>
</p>

# Onimusha: Way of the Sword — AI Difficulty Mod

A difficulty mod for **Onimusha: Way of the Sword** that makes combat more aggressive and dynamic.

The mod allows multiple enemies to attack simultaneously instead of waiting their turn, making encounters more intense and challenging.

## Features

* ⚔️ Multiple enemies can attack simultaneously.
* 🚫 Removes the vanilla attacker limit.
* ⚡ Reduces enemy pressure system wait times.
* 🔥 Reduces combat rhythm intervals.
* 🎮 Requires no configuration.
* 📦 Only requires **REFramework** to work.

---

# Installation

## 1. Install REFramework

This mod requires **REFramework** to work.

Download the latest version from the official repository:

<p align="center">
  <a href="https://github.com/praydog/REFramework-nightly/releases">
    <strong>⬇️ Download REFramework</strong>
  </a>
</p>

Download the `REFramework.zip` file corresponding to the latest available version.

Extract `dinput8.dll` into the main folder where **Onimusha: Way of the Sword** is installed.

The folder structure should look approximately like this:

```text
Onimusha Way of the Sword/
├── dinput8.dll
├── reframework/
└── ...
```

Launch the game once to make sure REFramework has been installed correctly.

---

## 2. Install the mod

Download the mod's Lua file:

<p align="center">
  <a href="https://github.com/Camilo-tsx/Onimusha-mod/blob/main/Onimusha_AI_MOD.lua">
    <strong>⬇️ Download Onimusha AI Mod</strong>
  </a>
</p>

Then go to the folder where **Onimusha: Way of the Sword** is installed and open:

```text
reframework/
```

Then open:

```text
reframework/autorun/
```

Place the `Onimusha_AI_MOD.lua` file inside that folder.

The final structure should look like this:

```text
Onimusha Way of the Sword/
├── dinput8.dll
└── reframework/
    └── autorun/
        └── Onimusha_AI_MOD.lua
```

### That's it!

The mod **does not require any additional configuration**.

Simply launch the game and REFramework will automatically load the mod.

---

# How to check if it works

Open the **REFramework** menu while in-game.

You should see:

```text
Mod activado
```

If this message appears, the mod has been loaded successfully.

---

# Source Code

Don't want to download the file directly?

You can inspect the complete source code of the mod directly on GitHub:

<p align="center">
  <a href="Onimusha_MOD_lua">
    <strong>📄 View Full Source Code</strong>
  </a>
</p>

The mod is written entirely in **plain-text Lua**.

It contains no executables or compiled files.

You can open the source file, review the entire code, and copy it directly from GitHub if you prefer to install it manually.

---

# Manual Installation

If you prefer not to use the downloadable `.lua` file, you can create the file manually.

Create a file named:

```text
Onimusha_AI_MOD.lua
```

Copy the source code from `Onimusha_MOD_lua` into the file and place it in:

```text
reframework/autorun/
```

The final structure should be:

```text
reframework/
└── autorun/
    └── Onimusha_AI_MOD.lua
```

No code configuration or value changes are required.

---

# Uninstallation

To uninstall the mod, simply delete:

```text
reframework/autorun/Onimusha_AI_MOD.lua
```

There is no need to uninstall REFramework.

---

# Compatibility

This mod is designed for:

**Onimusha: Way of the Sword**

Requires:

**REFramework**

---

If you found the mod useful, consider leaving a ⭐ on the repository.

  ⭐ <strong>If you like the mod, consider leaving a star!</strong> ⭐
</p>
