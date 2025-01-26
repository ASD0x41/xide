# XIDE - An Online x86 Assembly IDE

Welcome to **XIDE**, an online x86 Assembly Integrated Development Environment (IDE)! This tool allows students and developers to code, assemble, debug, and emulate x86 assembly language programs directly in their browsers without the need to install separate tools.

## Features
- **Netwide Assembler (NASM)** for assembling x86 code.
- **Advanced Fullscreen Debugger (AFD)** for debugging assembled programs.
- **em-dosbox** to emulate the assembled programs in a browser environment.

## Usage
1. Open a `.asm` file or start writing code directly in the editor.
2. Click **Assemble** to assemble your code into an executable.
3. Click **Execute** to assemble and run your program in the DOSBox Emulator.
4. Click **Debug** to assemble and load the program into AFD for debugging.
5. Use **Restart** to restart the emulator if needed, or to stop an infinite loop in your program.

## Upcoming Features
- Support for handling multiple `.asm` files.
- Persistence of files across browser sessions.
- More customization options for debugging and emulation.

## Installation
You don’t need to install anything! Just head to [https://xide.nullprime.com/](https://xide.nullprime.com/) to use XIDE directly from your browser.

## Project Structure
- **Editor**: Write or modify your assembly code.
- **Emulator**: A WASM port of DOSBox used to run and debug programs.

## GPL Licensing
XIDE uses [em-dosbox](https://github.com/dreamlayers/em-dosbox), which is licensed under the [GNU General Public License v2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

XIDE is also released under the GPL license. You can find a copy of the GPL license in the `LICENSE` file.

### Acknowledgements
- [em-dosbox](https://github.com/dreamlayers/em-dosbox): Special thanks to [dreamlayers](https://github.com/dreamlayers) for the WASM port of DOSBox used in this project.
- [Netwide Assembler (NASM)](https://www.nasm.us/): The assembler used to compile the assembly code.
- [Advanced Fullscreen Debugger (AFD)](https://sourceforge.net/projects/ald/): The debugger integrated into this tool.

## Contributing
Feel free to contribute to the project by submitting issues or pull requests via this GitHub repository.

For any questions or feature requests, contact me at [contact@nullprime.com](mailto:contact@nullprime.com).
