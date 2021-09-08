# Install under a separate user account

![security: medium](https://img.shields.io/badge/security-medium-yellow) ![usability: low/medium](https://img.shields.io/badge/usability-low%2Fmedium-red)

Marginally better than [installing an app without protection](install-native-app-no-sandbox.md) is creating a separate, non-privileged user account and installing it locally within there. The biggest problems are:

* This significantly impairs usability
* Not all apps are happy to be installed this way, and will want to elevate to administrator privileges

## Windows

The built-in command line tool [`runas`](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/cc771525(v=ws.11)) can launch anything (including GUI apps!) as if another user started it.

For example, you can:

1. Install [Zoom](/apps/zoom.md) into its own user account (local to that user only)
2. On your main account, create a shortcut that will `runas` the Zoom executable
3. Whenever you need to open Zoom, use the shortcut
4. Enter the password for the other user account when prompted