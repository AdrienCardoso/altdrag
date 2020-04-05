---
layout: subpage
title: Hotkeys
---

You can use the configuration window to easily enable the Alt keys, the Windows keys and the Ctrl keys. For other keys, you have to manually edit `AltDrag.ini`.

Configuring the `Hotkeys` option in the ini file is not easy. You have to specify the hex values that represent the keys on the keyboard.

You can find these hex values on [this Microsoft documentation page](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes). To add a key, simply append its hex value to the list. Even though there are hex values for mouse buttons listed on that page, they will not work!

You actually don't need a space between the hex values, but it makes it easier to read. Removing all the keys makes it impossible to alt-drag windows, but you can still use `HookWindows`.

Some have requested the ability to only use the mouse to drag windows. I will consider this.


## Common keys

Here are some commonly used keys.

| Key                | Hex value |
| ---                | --------- |
| Left Alt Key       | `A4` |
| Right Alt Key      | `A5` |
| Left Windows Key   | `5B` |
| Right Windows Key  | `5C` |
| Left Ctrl Key      | `A2` |
| Right Ctrl Key     | `A3` |
| Left Shift Key     | `A0` |
| Right Shift Key    | `A1` |
{: class="table"}

Note that if you assign one of the shift keys to alt-drag windows, that shift key can no longer be used to snap windows together. If you assign the left shift key, you can still use the right shift key, and vice versa.


{% include improve-me.md %}
