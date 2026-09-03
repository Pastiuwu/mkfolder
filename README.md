# 🛠️ MKFolder - Pentesting Workspace Manager
MKFolder is a CLI tool designed to quickly organize pentesting projects. With a single command, it generates a directory structure and offers an optimized workflow.

[![Screenshot-1.png](https://i.postimg.cc/nh58BfpT/Screenshot-1.png)](https://postimg.cc/k2xhPZVt) 

![GitHub](https://img.shields.io/badge/License-MIT-red)
![Shell](https://img.shields.io/badge/Shell-Bash-green)
## 🔥 Features

- 🚀 **Auto-create** organized pentesting directory structure
- 🌈 **Colorized output** with custom ASCII art
- 🔍 **Integrated Nmap menu** with scan profiles
- ⚡ **Dependency auto-check** and installation
- 📊 **Execution statistics** and time tracking
- 🛡️ **Error handling** and input validation

## 📦 Installation

### Basic Install (Bash/Zsh).
```bash
curl -sSL https://raw.githubusercontent.com/Pastiuwu/mkfolder | bash
```
Manual Install
Clone the repo:
```
bash
Copy
git clone https://github.com/Pastiuwu/mkfolder.git
cd mktool
```
Make executable:
```
bash
Copy
chmod +x src/mktool.sh
```
Add to your shell:
```bash
Copy
echo "source $(pwd)/src/mktool.sh" >> ~/.zshrc  # or ~/.bashrc
```
🎯 Usage
bash
Copy
mkt                          # Create default directories
mkt target1 scans reports    # Create custom directories
mkt --nmap-only              # Skip dirs, just launch Nmap
