# Linux Command for Raycast

Search Linux commands and view their detailed usage information directly in Raycast.

## Features

- 🔍 **Quick Search**: Search through 100+ common Linux commands
- 📖 **Detailed Documentation**: View full command documentation with options and examples
- ⚡ **Fast Access**: Instantly access command information without leaving your workflow
- 🔗 **Open in Browser**: Jump to the original documentation on GitHub
- 📋 **Copy to Clipboard**: Copy command names and examples with one click

## Data Source

This extension uses data from the [linux-command](https://github.com/jaywcjlove/linux-command) repository by [@jaywcjlove](https://github.com/jaywcjlove), which provides comprehensive Linux command documentation in Chinese.

## Supported Commands

The extension includes documentation for common Linux commands such as:

- File Operations: `ls`, `cat`, `cp`, `mv`, `rm`, `mkdir`, `find`, `grep`, `awk`, `sed`
- System Info: `ps`, `top`, `df`, `du`, `free`, `uptime`, `vmstat`
- Network: `curl`, `wget`, `ssh`, `scp`, `ping`, `netstat`, `iptables`
- Text Processing: `echo`, `head`, `tail`, `sort`, `uniq`, `cut`, `tr`
- Package Management: `npm`, `yarn`, `pip`, `docker`, `kubectl`
- And many more...

## Usage

1. Open Raycast
2. Type "Search Linux Command" or use the configured shortcut
3. Search for a command by name or description
4. Press Enter to view detailed documentation
5. Use keyboard shortcuts to:
   - Copy command name
   - Open in browser
   - Copy example commands

## Installation

### From Source

```bash
# Clone the repository
git clone <your-repo-url>
cd raycast-linux-command

# Install dependencies
npm install

# Build the extension
npm run build

# Import to Raycast
# Open Raycast → Import Extension → Select this folder
```

### From Raycast Store

(Coming soon)

## Development

```bash
# Start development mode
npm run dev

# Build for production
npm run build

# Run linting
npm run lint

# Fix linting issues
npm run fix-lint
```

## Requirements

- Raycast 1.50.0 or later
- Node.js 18 or later
- npm or yarn

## License

MIT

## Acknowledgments

- [linux-command](https://github.com/jaywcjlove/linux-command) - The comprehensive Linux command documentation repository
- [Raycast](https://raycast.com) - The powerful macOS launcher
