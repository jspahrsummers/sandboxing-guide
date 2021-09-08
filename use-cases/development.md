# Software development

_Recommendation:_ [**work inside containers**](/solutions/containers.md)

![security: high](https://img.shields.io/badge/security-high-blue) ![usability: high](https://img.shields.io/badge/usability-high-blue)

Developer tools absolutely _love_ to barf all over your machine, absolutely littering it with random binaries, state, caches, and hidden configuration files. Then, on top of it all, there's the huge amount of risk that comes from running so much untrusted code all of the time.

With IDEs like [VS Code](https://code.visualstudio.com/) supporting [developing inside a container](https://code.visualstudio.com/docs/remote/containers), this is a quite usable way to isolate untrusted (or untested) code from the rest of your machine, and quarantine the DevBarf™.

[Remote development over SSH](https://code.visualstudio.com/docs/remote/ssh) is another alternative, although arguably the remote development environment should be containerized too.