# selinux-denial-fixer

Generate Fixes for your SELinux Denials.
Updated with *love* by me.
*Cuz I'm also a lazy noob trying to fix his broken enforcing build*.

## Usage

Run into WSL/your preferred Linux terminal: `python3 denials.py`.

- `-c` cleans up your working directory from unnecessary files.
- `-d file` enables the dmesg parsing mode. Acts like logcat mode.
- `-h` shows the help page.
- `-l file` enables the logcat parsing mode.
- `-s` sanitizes log file encoding before processing it.
- `-v` enables verbose mode. It'll output every denial into its respective file.

## Troubleshooting

- If `-s` doesn't work, run `dos2unix` over your file to fix its encoding.

## Credits

@baalajimaestro for the initial base, StackOverflow *cuz why not lol*

## Original license

Raphielscape Public License, version 1.c.
