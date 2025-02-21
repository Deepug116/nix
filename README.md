# **Nix - The Purely Functional Package Manager**

[![Build Status](https://img.shields.io/github/actions/workflow/status/NixOS/nix/ci.yml)](https://github.com/NixOS/nix/actions)  
[![License: LGPL](https://img.shields.io/badge/License-LGPL-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)  
[![Chat on Matrix](https://img.shields.io/matrix/nixos:nixos.org)](https://matrix.to/#/#nixos:nixos.org)  

---

## What is Nix?
Nix is a powerful purely functional package manager** that makes software deployment reliable, reproducible, and declarative. It allows for atomic upgrades, rollbacks, and isolation of package dependencies**, making it an excellent choice for developers, system administrators, and DevOps professionals.

## Why Use Nix?
Reproducibility: Ensure that software installations are exactly the same across multiple machines.  
Isolation: Avoid dependency conflicts between different applications.  
Atomic Upgrades & Rollbacks: Easily roll back to previous versions of installed packages.  
Declarative Configuration: Define your entire environment in a single configuration file.  
Cross-Platform Support: Works on Linux, macOS, and partially on Windows (via WSL).  

---

## Getting Started
### Installation
To install Nix, run the following command in your terminal:

```sh
curl -L https://nixos.org/nix/install | sh
```

For detailed installation instructions, check the [official guide](https://nixos.org/download.html).

### Basic Usage
After installing, you can use Nix to install packages:

```sh
nix-env -iA nixpkgs.hello
```

To remove a package:

```sh
nix-env -e hello
```

For more commands, see the [Nix manual](https://nixos.org/manual/nix/stable/).

---

## Key Features
Multi-user Support: Nix allows multiple users to install packages without interfering with each other.  
Garbage Collection: Clean up unused packages with `nix-collect-garbage`.  
Pinning & Versioning: Install specific package versions without affecting system-wide dependencies.  
System Rollbacks: Undo unwanted changes effortlessly.  

---

## Contributing
We welcome contributions! If you’d like to help improve Nix, follow these steps:  
1. Fork the repository and clone it locally.  
2. Make your changes and commit them.  
3. Open a Pull Request (PR) with a clear description.  

Check out the [contributing guide](https://github.com/NixOS/nix/blob/master/CONTRIBUTING.md) for more details.

---

Community & Support
- Documentation: [Nix Manual](https://nixos.org/manual/nix/stable/)  
- Chat: [Matrix](https://matrix.to/#/#nixos:nixos.org)  
- Issues: [GitHub Issues](https://github.com/NixOS/nix/issues)  
- Discussions: [NixOS Discourse](https://discourse.nixos.org/)  

---

## License
Nix is licensed under the [LGPL-2.1 License](https://www.gnu.org/licenses/lgpl-2.1.html).

 Start using Nix today and take control of your package management!

