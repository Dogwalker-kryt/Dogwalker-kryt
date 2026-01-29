# Hey, I'm Dogwalker-kryt 

Self-taught programmer focused on **low-level systems work** in C/C++, Rust, and Python. I spend most of my free time building useful open-source tools for Linux. I upload source-only (most of the time) so you can compile it yourself. That way you know exactly what's running.

---

## What I Do

I build practical utilities that solve real problems. Most of my projects involve:
- **Linux kernel operations** (modules, filesystems, device management)
- **Systems programming** (direct hardware interaction, minimal abstractions)
- **Command-line tools** (fast, efficient, no bloat)
- **DIY approach** (prefer understanding the system over using abstractions)

---

## Current Projects

### [Drive Manager for Linux](https://github.com/Dogwalker-kryt/Drive-Manager-for-Linux) *My best work*
**What it does:** Complete drive management utility for Linux—format, encrypt, clone, analyze, benchmark, recover, and forensics operations on physical drives.

**Tech Stack:** C++, OpenSSL (libssl/libcrypto), lsblk, parted, cryptsetup, dd, smartctl, e2fsck

**Key Features:**
- Format and partition drives
- Full-disk encryption/decryption
- Disk cloning with verification
- Drive fingerprinting & forensics
- Disk space analysis & benchmarking
- Metadata extraction and recovery
- Dry-run mode for safety
- Centralized command execution abstraction

**Status:** Feature-complete, ~3200+ lines of production C++

---

### [Linux Kernel Module Manager (KMM)](https://github.com/Dogwalker-kryt/Linux-Kernel-Module-Manager--KMM-)
**What it does:** Clean CLI for managing kernel modules—load, unload, list, and verify module status. Built with libkmod for a modern approach to kernel operations.

**Tech Stack:** C, libkmod, Linux kernel API

**Key Features:**
- List all loaded modules with dependencies
- Load/unload modules with parameters
- Check module status instantly
- Clean 3-layer architecture (CLI → API → libkmod)
- Error handling with user-friendly messages
- Memory safe and leak-free

**Status:** Phase 1 complete, tested and working

---

## Currently Learning

- **x86 Assembly** — Understanding how the CPU actually works
- **Advanced C/C++** — Memory models, optimization techniques
- **Kernel internals** — Device drivers, syscalls, module loading mechanisms

---

## Skills

**Languages I use:**
- **C** — System-level work, kernel operations
- **C++** — System-level work and Complex applications
- **Rust** — Trying Memory safety without overhead 
- **Python** — Scripting, automation and prototyping
- **Kotlin** — Trying to make applications for Android

**Linux & Systems:**
- Comfortable at the command line (and yes, I can exit vim)
- Kernel module development and debugging
- Shell scripting and build systems (Make, autotools)
- Filesystem operations and encryption
- Performance analysis and optimization

**Philosophy:**
- **Low-level first** — Understand the system before abstracting
- **Minimal dependencies** — Less bloat, more control
- **User-friendly** — Even system tools should be easy to use
- **Open source** — Code that anyone can compile and audit

---

## How I Work

- Self-taught through documentation and hands-on experimentation
- testing before release
- Backup branches and careful version control

---

## Language Stats
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dogwalker-kryt&layout=compact)

---

## What's Next?

Working on expanding my systems programming toolkit:
- More kernel module projects
- Embedded systems 
- Performance profiling tools

If you're interested in systems programming or Linux development, feel free to explore my repos and suggest improvements. I'm always open to feedback and collaboration.
