# [Xcode](https://developer.apple.com/xcode/) _(macOS only)_

_Recommendation:_ [**use inside a virtual machine**](/solutions/use-in-virtual-machine.md)

![security: high](https://img.shields.io/badge/security-high-blue) ![usability: low](https://img.shields.io/badge/usability-low-red)

Xcode, like most [developer tools](/use-cases/development.md), likes to litter your system with state and binaries. I prefer to keep it contained and out of sight. As a bonus, this makes switching between Xcode versions simpler!

_I hacked together a virtualization app, [Microverse](https://github.com/jspahrsummers/Microverse), to support running Xcode inside a VM. Unfortunately, due to limitations of `Virtualization.framework`, Microverse only supports Apple Silicon._