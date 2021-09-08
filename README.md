# Sandbox everything

Inspired by [**@alexdavid**](https://github.com/alexdavid), I became obsessed with [sandboxing](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) everything on my computer—constraining applications to the minimum number of privileges they need to perform their job, limiting their data access as much as possible, and preventing any kind of modifications to other apps or the overall system.

The most obvious reasons to do this are, of course, security and privacy. Limiting the surface area for each application will significantly reduce the likelihood of data leakage and data theft (something especially important as a software engineer, given how frequently we have to run untrusted code). No solution is going to be 100% effective, but sandboxing is a relatively easy, low-overhead way to build [defense in depth](https://en.wikipedia.org/wiki/Defense_in_depth_(computing)).

[This guide](#this-guide) offers suggestions for sandboxing **Mac and Windows** applications and workflows to improve security, while [balancing usability](#balancing-security-and-usability).

## Balancing security and usability

The **most** secure machines aren't even connected to the internet, and definitely don't run _"apps"_ as we would know them. Consequently, to have a _useful_ machine, we can't focus only on security—we need to to make some accommodation for usability too.

I think of [the solution space for sandboxing](solutions/) sort of like this:

![Different sandboxing options plotted in terms of their relative security and relative usability](https://jspahrsummers.com/wp-content/uploads/2021/09/sandboxing-security-vs-usability.png)

In written form:

| | ![security: low](https://img.shields.io/badge/security-low-red) | ![security: medium](https://img.shields.io/badge/security-medium-yellow) | ![security: high](https://img.shields.io/badge/security-high-blue) |
|-|-|-|-|
| ![usability: low](https://img.shields.io/badge/usability-low-red) | |  [Separate user accounts](solutions/install-under-separate-user.md) | [Virtual machines](solutions/virtual-machine.md) |
| ![usability: medium](https://img.shields.io/badge/usability-medium-yellow) | | | [Web browser](solutions/browser.md)<br />[Containers](solutions/containers.md) |
| ![usability: high](https://img.shields.io/badge/usability-high-blue) | [Native app (no sandbox)](solutions/install-native-app-no-sandbox.md) | [App stores](solutions/install-from-app-store.md) |

Each of the solutions involves tradeoffs, and there isn't always a clear winner.

## This guide

I've experimented with all of the above solutions, in varying combinations. In this guide, I'll share my **preferences** for how _I_ prefer to use macOS and Windows while avoiding unnecessary risk.

**These recommendations are just my opinion, and certainly not authoritative!** I'm not responsible for any negative consequences you suffer if you apply my ideas here.

This guide is divided into three unordered sections:

* A non-exhaustive list of [sandboxing solutions](solutions/)
* Examples of [how to sandbox specific apps](apps/)
* Examples of [how to sandbox some general workflows and use cases](use-cases/)

Hopefully it's useful.

## Contributing

This guide is primarily an attempt to evangelize sandboxing and share some of my personal recommendations/opinions on the matter; however, I would love any and all contributions:

* Correcting me on matters of fact
* Suggesting additional [sandboxing solutions](solutions/) that I haven't thought of
* Suggesting how to sandbox [applications](apps/) or [use cases](use-cases/) that I haven't listed here

Just please keep in mind that this is not meant to be an authoritative reference—as such, I may decline changes that I personally disagree with (on matters of opinion).

## License

All contents of this repository are released under the [CC0 1.0 Universal](LICENSE) license (effectively public domain).