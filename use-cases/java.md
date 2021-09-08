# Java applications

_Recommendation:_ [**use inside containers**](/solutions/containers.md)

![security: high](https://img.shields.io/badge/security-high-blue) ![usability: low/medium](https://img.shields.io/badge/usability-low%2Fmedium-red)

Cross-platform Java apps can be sandboxed (with minimal performance cost) by installing into a Linux-based container with an [X Server](https://en.wikipedia.org/wiki/X_Window_System), then connecting to use them over [VNC](https://en.wikipedia.org/wiki/Virtual_Network_Computing).

_[Here's an example](https://github.com/antequant/ib-tws-docker) of doing this for [Interactive Brokers' Trader Workstation](https://www.interactivebrokers.co.uk/en/index.php?f=38477)._

However, depending on the nature of the application, this may be quite limiting, so a second-best alternative would be to [install from an app store](/solutions/install-from-app-store.md) if available.