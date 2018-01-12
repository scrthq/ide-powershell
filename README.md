# ide-powershell

Experimental [PowerShell](https://github.com/powershell/powershell) language support
for [Atom](https://atom.io)

## Overview

This project leverages [atom-languageclient](https://github.com/atom/atom-languageclient)
and [PowerShell Editor Services](https://github.com/PowerShell/PowerShellEditorServices)
to provide rich PowerShell language features in the Atom editor.

**DISCLAIMER:** I am developing this as a side project in my free time, so please
consider contributing if you want to help it get better faster!

## Prerequisites

To use this package, you must first install its dependencies.  There are some
[build dependencies for node-gyp](https://github.com/nodejs/node-gyp#on-unix) that
must be installed first depending on your platform.

Once the build dependencies have been installed, you can install the `ide-powershell`
package and its dependencies in Atom:

```
$ apm install language-powershell terminal-tab-service ide-powershell
```

## Development

1. Follow the instructions in the Prerequisites section above but **exclude** the `ide-powershell`
   package from the `apm install` command

2. Fork this repo, clone it to a local folder, and go to that folder in a terminal

3. Run `apm install` install dependencies and build the package

4. Run `apm link` to wire up the package in Atom

5. Open or restart Atom and then try loading a .ps1 file

6. Change some code in this repo, run the "Reload Window" command, then try your changes!

## Maintainers

- [David Wilson](https://github.com/daviwil) - [@daviwil](http://twitter.com/daviwil)
- [Patrick Meinecke](https://github.com/SeeminglyScience) - [@SeeminglyScienc](http://twitter.com/SeeminglyScienc)

## License

This project is licensed under the [MIT License](LICENSE).  Some portions of the
code are based on the [PowerShell extension](https://github.com/PowerShell/vscode-powershell/)
for Visual Studio Code, also under the [MIT License](https://github.com/PowerShell/vscode-powershell/blob/master/LICENSE.txt).