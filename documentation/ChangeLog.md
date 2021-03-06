## RustDT release ChangeLog

### 0.2.0
 * Added: Open Definition functionality using Racer.
 * Added: Content Assist functionality using Racer.
  * Added: Content Assist auto-insert of function arguments for function proposals.
  * Added: Content Assist code snippet proposals. Configurable in `Preferences/Rust/Editor/Code Snippets`. (needs more defaults)
  * [Doc] Added [Content Assist / Open Definition](documentation/UserGuide.md#content-assist--open-definition) section.
 * Added: Automatically set up Rust GDB pretty-printers for debug launches. (#6)
  * [Doc] Added [GDB pretty-printers](documentation/UserGuide.md#gdb-pretty-printers) section.
  * Note: I couldn't get this to work on any Windows GDB (Cygwin, TDM-GCC, MinGW-w64) .
 * Upgraded minimum CDT version to 8.6.0.
 * [Doc] Added [Editor auto-indentation](documentation/UserGuide.md#editor-newline-auto-indentation) section.
  

### 0.1.1
 * Added: Source menu with shift right/left operations.
 * Added: Toggle Comment action (shortcut: Ctrl+/) to Source Menu.
 * Added: Editor Go To Matching Bracket action (shortcut: Ctrl+Shift+P).
 * Fixed #2: Lifetimes are incorrectly highlighted as char
 * Fixed: "Attribute" syntax highlighting option missing from Source Coloring preference page.
 * Added: Syntax highlighting for lifetime token.
 * Added: Syntax highlighting for strings inside attribute region.
 * Fixed minor bug with block comments syntax highlighting.
 * [Doc] Fixed: missing UserGuide screenshot of debug launch configuration.
 * [Doc] Added: Installation guide note for users in China.

### RustDT 0.1.0 - Initial release 
 * Added: Rust source code editor, with:
   * Syntax highlighting. Configurable in `Preferences/Rust/Editor/Source Coloring`. 
   * Automatic indent/de-indent and brace completion on certain keypresses (Enter, Backspace). Configurable in `Preferences/Rust/Editor/Typing`.
 * Added: Rust/Cargo Project wizard.
 * Added: Rust/Cargo project builder.
   * With in-editor build errors reporting.
 * Added: Debugging support using [CDT](https://eclipse.org/cdt/)'s GDB integration. 
 
