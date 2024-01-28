# Essentials of Programming Languages, Third Edition

## Development Environment

- (Fedora-only) [Copr](https://copr.fedorainfracloud.org/)

  Copr manages third-party package repositories on Fedora and related operating systems, such as Rocky Linux.  Install with the command `dnf install 'dnf-command(copr)'`.

- (Windows-only) [Chocolatey](https://chocolatey.org/)

  Chocolatey is third-party package manager for Windows and Windows Server.  Enable automatic updates by installing [choco-upgrade-all-at](https://community.chocolatey.org/packages/choco-upgrade-all-at).

- (Windows-only) [winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/)

  This is the official Windows package manager, integrated with the Microsoft Store.  Install via Chocolately.  Note that neither the Microsoft Store nor winget are available on Windows Server.

- [Chez Scheme](https://cisco.github.io/ChezScheme/)

  This is the Scheme implementation I used in college on NeXT computers, now released as free/libre/open source software.

  On Fedora, install via [superboum/chez-scheme](https://copr.fedorainfracloud.org/coprs/superboum/chez-scheme/).

  On Windows, install via winget, then add `...\Chez Scheme...\bin\ta6nt` (e.g., `C:\Program Files\Chez Scheme 9.5.8\bin\ta6nt`) to the per-user or system-wide executable search path.

  On Ubuntu, install via APT.

- [VSCodium](https://vscodium.com/) or Microsoft Visual Studio Code

  I recommend VSCodium because it removes Microsoft's telemetry and tracking functions from Visual Studio Code.  Otherwise, the two work identically.

- [Chez Scheme REPL](https://marketplace.visualstudio.com/items?itemName=release-candidate.vscode-scheme-repl) for VSCodium and Microsoft Visual Studio Code

  This VSCodium/VSCode extension adds Chez Scheme syntax checking/highlighting, inline documentation, and tab completion.

- [GNU Emacs](https://www.gnu.org/software/emacs/)

  What can I say?  Old habits die hard.  This is my preferred editor, having used it since 1994.

- [Geiser](https://www.nongnu.org/geiser/)

  This integrates Scheme with Emacs, similar to SLIME and Common Lisp.
