# Know Your System

## Part 1 – Identify Your System

### Observe

```bash
# Display information about the Linux distribution
cat /etc/os-release

# -r displays the kernel release
uname -r

# -m displays the machine's hardware architecture
uname -m

# -v displays the kernel name
uname -s
```

### What I Learned Today

Today, I learned how to identify active kernel information about my system and how to differentiate from the distribution.

I also discovered a new option, `-s`, which displays information about the kernel name.

One challenge I noticed is that I struggle to put into words what I've learned and practiced. I want to improve my ability to explain technical concepts clearly and accurately.

### Micro challenge

*** Ejecute uname -s and explain why is not enought to know if your using Arch or Ubuntu

> Ejecuting uname -s returns 'Linux' with is the kernel not the distribution, not giving you enough information to tell if is Arch or Ubuntu
