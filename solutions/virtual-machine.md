# Virtual machine

![security: high](https://img.shields.io/badge/security-high-blue) ![usability: low](https://img.shields.io/badge/usability-low-red)

When security is critical—or the usability hit is acceptable—putting something into a [virtual machine](https://en.wikipedia.org/wiki/Virtual_machine) is second only to putting it on its own physical machine. Depending on the platform, [Docker](containers.md) may even be using a virtual machine under the hood.

For maximum performance, make sure you are [virtualizing](https://en.wikipedia.org/wiki/Virtualization) the host architecture, and not [emulating](https://en.wikipedia.org/wiki/Emulator) a different one.

_I hacked together a virtualization app, [Microverse](https://github.com/jspahrsummers/Microverse) for running macOS-inside-macOS on Apple Silicon specifically, which is otherwise not available._