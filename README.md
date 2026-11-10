# Linux Learning Journal

This repository documents my progress learning Linux system administration and networking using Arch Linux.

My goal is to understand how my system works, solve problems methodically, and explain technical concepts clearly.

## Learning Approach

For each exercise, I follow five steps:

1. **Observe:** Gather information about the system.
2. **Form a hypothesis:** Predict what a command or change will do.
3. **Test:** Run a focused, safe experiment.
4. **Verify:** Compare the result with my prediction.
5. **Document:** Explain what I learned, including mistakes and corrections.

## Environment

- Operating system: Arch Linux
- Tools used so far: terminal, man, cat, and uname
- Documentation: local manual pages, ArchWiki, and official manuals

## Completed Lessons

| Lesson | Topics | Status |
|---|---|---|
| [01 — Know Your System](lessons/01-know-your-system.md) | Distribution identification, kernel information, architecture, and manual pages | Completed |

## What I Have Learned So Far

- How to identify the distribution using `/etc/os-release`.
- How to inspect the running kernel and machine architecture using `uname`.
- How to consult command documentation using `man` and `--help`.
- Why the kernel name alone cannot identify the Linux distribution.

One correction I made during the first exercise was distinguishing
`uname -v`, which displays kernel version information, from `uname -s`,
which displays the kernel name.

## Planned Topics

- Files, paths, and searching
- Permissions and ownership
- Processes and system resources
- Package management with pacman
- Services and logs with systemd
- Storage and backups
- Bash scripting
- Networking, DNS, and SSH
- Practical troubleshooting

## Personal Development

Alongside technical practice, I am working on explaining what I learn
clearly and accurately.

Each lesson includes commands, observations, a practical challenge,
and a reflection on what I understood and what needs more practice.
