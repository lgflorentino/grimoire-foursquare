grimoire-foursquare
---

## Desc:
Buncha scripts for building things. These are tuned to my system, however you may like to checkout the metadata (`config.toml`) to see where the script was inherited from which will be much more generic.
See [grimoire](https://git.sr.ht/~lgflorentino/grimoire) for a similar project targeting [Zshell](https://zsh.sourceforge.io/) and \*nix based systems. [WSL](https://docs.microsoft.com/en-us/windows/wsl/about) and other methods for running \*nixy style scripts on Windows are also contained in that repository. This repository is for Powershell only scripts. 

## Dependencies
See `grimoire-foursquare.toml` for dependency versions
```psh
psh git
```

## Instructions
Branches are named after the target version of Windows. A script should exist in the branch if it targets that version. There may exist differences between scripts which are named the same but are populated in different branches

The following command will list versions for which one or more scripts are supported.
```
git branch
```

# Project Layout
```
- root folder
 |-- installers: Scripts for installing onto the base filesystem
 |  |--
 |-- builders: scripts for building in a sandboxed environment
    |--
```

### Example script folder layout
```
- root
 |- installers
   |- example-script
     |- env
     |- example-script.ps1
     |- ?

```





## LICENSE

MIT. See LICENSE

