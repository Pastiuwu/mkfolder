# 🛠️ MKTool - Pentesting Workspace Manager

![ASCII Art Preview](https://imgur.com/a/SDAj9ZU)  
*A dynamic terminal tool for creating pentesting workspaces with style*

## 🔥 Features

- 🚀 **Auto-create** organized pentesting directory structure
- 🌈 **Colorized output** with custom ASCII art
- 🔍 **Integrated Nmap menu** with scan profiles
- ⚡ **Dependency auto-check** and installation
- 📊 **Execution statistics** and time tracking
- 🛡️ **Error handling** and input validation

## 📦 Installation

### Basic Install (Bash/Zsh)
```bash
curl -sSL https://raw.githubusercontent.com/yourusername/mktool/main/install.sh | bash

Manual Install
Clone the repo:

bash
Copy
git clone https://github.com/yourusername/mktool.git
cd mktool
Make executable:

bash
Copy
chmod +x src/mktool.sh
Add to your shell:

bash
Copy
echo "source $(pwd)/src/mktool.sh" >> ~/.zshrc  # or ~/.bashrc
🎯 Usage
bash
Copy
mkt                          # Create default directories
mkt target1 scans reports    # Create custom directories
mkt --nmap-only              # Skip dirs, just launch Nmap
