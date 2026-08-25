# Inside a Computer System (TryHackMe)

Link: https://tryhackme.com/room/insideacomputer

What it was: A theory room about the basic components of a computer (CPU, RAM, disk, etc.) and what happens during system boot-up, from pressing the power button to the desktop appearing.

What I learned:
1. The main components of a computer are explained through an analogy with the human body (for example, CPU is the "brain", RAM is the "short-term memory")
2. The computer boot process consists of several steps: power → firmware (UEFI/BIOS) → self-test of components (POST) → selection of boot device → bootloader launch → transfer of control to the operating system
3. UEFI is a modern replacement for the old BIOS, responsible for the initial launch of all components
4. The boot process is an important topic in cybersecurity, because it is at this stage that hackers sometimes attack the system (for example, through bootloader vulnerabilities)

What I learned: to protect or attack a system, you first need to understand what it consists of and how it works at a basic level - this is the foundation for further study of security.
