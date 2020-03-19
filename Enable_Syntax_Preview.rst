*************************************************************************************************
How to Enable Syntax Highlighting and the Preview Pane for HTML, Markdown, and RST Files
*************************************************************************************************

After installing the appropriate packages, it's easy to enable both syntax highlighting and the preview pane.

Syntax Highlighting (Color-Coded Syntax)
---------------------------------------------
To enable syntax highlighting (color-coded syntax), the only thing you need to do is to save your document with the appropriate file extension for the language you're writing in.

**Instructions:**

#. Open a new file.
#. Start typing as much of your file as you want.
#. Save your document with the appropriate file extension:

   - HTML = filename.htm or filename.html
   - Markdown = filename.md
   - RST = filename.rst

After you save the file with its extension, Atom knows what language you're writing in and "turns on" appropriate the syntax highlighting. You do **not** need to re-enable syntax highlighting after the initial file save.


Preview Pane
-----------------
The preview pane allows you to see a preview of what you're writing while you're writing it ("live preview").

The Preview Pane is a toggle -- you turn it on and off with the same command. For RST and Markdown, you can use either hotkeys or a drop-down menu. For HTML, you use only a drop-down menu.

When you enable the preview pane, you get a split screen: your code screen appears on the left side and the preview pane appears on the right.

**Instructions:**

#. Open your file (make sure it's already been saved with the appropriate file extension).
#. Follow one of the preview pane toggle commands in the table below to open the preview pane. The preview pane appears on the right side of your screen.

.. note::

	#. You must enable the preview pane every time you open your file.
  #. The code you're writing on the left side of the screen does **not** automatically wrap. To enable text wrapping: From the top menu, click **View < Toggle Soft Wrap**.
  #. You can use the hotkey and drop-down menu commands interchangeably. In other words, you can use one method to open the preview pane and the other method to close it.

.. list-table:: Preview Pane Toggle Commands
  :widths: 20 50 30
  :header-rows: 1

  * - Language
    - Drop-Down Menu
    - HotKey Command
  * - HTML
    - Packages < Preview HTML < Enable Preview
    - Control + Shift + H
  * - Markdown
    - Packages < Markdown Preview < Toggle Preview
    - Control + Shift + M
  * - RST
    - Packages < reStructuredText < Toggle Preview
    - Control + Shift + R
