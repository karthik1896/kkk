# selinux-denial-fixer

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/64b12db392b2496bb1ac45a735ce1a75)](https://www.codacy.com/gh/Giovix92/selinux-denial-fixer/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Giovix92/selinux-denial-fixer&amp;utm_campaign=Badge_Grade)

Generate Fixes for your SELinux Denials. Updated with *love* by me.

*Cuz I'm also a lazy noob trying to fix his broken enforcing build*.

## Usage

Run into WSL/your preferred Linux terminal: `python3 denials.py`.

You can also run it as a normal executable: `./denials.py`.

### Options allowed

- `-1 denial` outputs only the fix for the inserted denial.
- `-c` cleans up your working directory from unnecessary files.
- `-d file` enables the dmesg parsing mode. Acts like logcat mode.
- `-h` shows the help page.
- `-l file` enables the logcat parsing mode.
- `-s` sanitizes log file encoding before processing it.
- `-v` enables verbose mode. It'll output every denial into its respective file.

## General rules

Please, **do not address random things**. (see untrusted_apps, system_server...)

If you need to do something like that, refer to the [LineageOS guide](https://lineageos.org/engineering/HowTo-SELinux/).

## Troubleshooting

- If `-s` doesn't work, run `dos2unix` over your file to fix its encoding.

## Credits

@baalajimaestro for the initial base, StackOverflow *cuz why not lol*

## Original license

Raphielscape Public License, version 1.c.
