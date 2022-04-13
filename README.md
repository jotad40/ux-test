# FactoryTalk Vault Quick Start

This repository contains a two sample solutions.
Blah blah...

## Repository Organization

You are free to organize your repository in any manner you choose with one
exception: the `.vault` folder must exist at the root of the repository.

This example uses folders to group related content as shown below:

```text
.
├─ .vault           # Contains FTVault specific content.
│  └─ vault.yaml    # Describes the structure of this repository to FTVault.
|                   #   See the 'Resource' section for more information.
|
├─ line_abc         # Contains an example solution
│  ├─ src
│  │  ├─ abc.acd    # A LogixDesigner project
│  │  └─ machines   # Contains a FTDS project
│  |     └─ ...
│  ├─ tests
│  |  └─ sim.e3d    # An Emulate3D project
│  ├─ drawing       # Contains an ePlan project
│  |  └─ ...
│  └─ docs.pdf      # Misc files
|
├─ line_xyz         # Contains another example solution
│  └- machine1.acd
│  └- machine2.acd
|
├─ shared           # Contains content shared among the solutions
│  └─ mixer.acd
|
└─ README.md        # This file
```

## Resources

### FactoryTalk Vault
- [Vault.yaml](#) reference
- [FactoryTalk Vault](#) home page
- [FactoryTalk Hub](#) home page
- etc.

### Learning git
- [An Intro to Git and GitHub for Beginners (Tutorial)](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
- [Pro Git book](https://git-scm.com/book)
- [Git reference](https://git-scm.com/docs)
- etc.

### Graphical interfaces for git
- [GitHub Desktop](https://desktop.github.com/)
- [SourceTree](https://www.sourcetreeapp.com/)
- etc.
