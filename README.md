# WindowsSandboxes
A collection of Windows Sandbox configurations and scripts.

For more information on Windows Sandbox see Microsoft's Documentation.

- Overview - https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-overview

- Architecture - https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-architecture

- Configuration - https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-configure-using-wsb-file
</br></br>
## Protip:
-------------
Be sure to substitute any `<HostFolder></HostFolder>` locations inside the .wsb files with the correct location(s) on your computer (i.e. "C:\Users\USER\WindowsSandboxes\SandboxScripts)".
</br></br>
## Development Environment Sandbox
-------------
This is used to setting up a disposable development enviroment.
</br></br>
Adding and subtracting whatever $Packages you require for your ideal environment can be done in the .ps1 file inside of the SandboxScripts folder.
```
├── WindowsSandboxes
│   ├── SandboxScripts
│   │   ├── InstallChocolateyVSCodeGitAndNode.ps1
```

### Useful Links:

[Git](https://git-scm.com/)

[Node.JS](https://nodejs.org)

[VS Code](https://code.visualstudio.com/)
