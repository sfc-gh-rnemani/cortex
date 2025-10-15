# Cursor MCP Configuration Setup

This directory contains the Model Context Protocol (MCP) configuration for Project Snow Owl's AI-powered account research capabilities. The templates in this project leverage two MCP servers: **Sequential Thinking** and **Brave Search**.

## Prerequisites

### Node.js Installation

Both MCP servers require Node.js to be installed locally on your system.

#### macOS Installation

**Option 1: Using Homebrew (Recommended)**
```bash
# Install Homebrew if you don't have it
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Node.js
brew install node

# Verify installation
node --version
npm --version
```

**Option 2: Using Official Installer**
1. Visit [nodejs.org](https://nodejs.org/)
2. Download the macOS installer (.pkg file)
3. Run the installer and follow the prompts
4. Verify installation in Terminal:
   ```bash
   node --version
   npm --version
   ```

**Option 3: Using Node Version Manager (nvm)**
```bash
# Install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

# Restart terminal or run:
source ~/.bashrc

# Install latest LTS version of Node.js
nvm install --lts
nvm use --lts

# Verify installation
node --version
npm --version
```

#### Windows Installation

**Option 1: Using Official Installer (Recommended)**
1. Visit [nodejs.org](https://nodejs.org/)
2. Download the Windows installer (.msi file)
3. Run the installer as Administrator
4. Follow the installation wizard (ensure "Add to PATH" is checked)
5. Restart your computer
6. Verify installation in Command Prompt or PowerShell:
   ```cmd
   node --version
   npm --version
   ```

**Option 2: Using Windows Package Manager (winget)**
```cmd
# Install Node.js
winget install OpenJS.NodeJS

# Verify installation
node --version
npm --version
```

## MCP Server Setup

### 1. Sequential Thinking Server

The Sequential Thinking server provides structured problem-solving capabilities for complex analysis tasks.

**GitHub Repository:** [modelcontextprotocol/servers - Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking)

**Installation:**
No manual installation required. The server uses `npx` to automatically download and run the latest version.

**Configuration:**
Already configured in `mcp.json`. No additional setup needed.

**Capabilities:**
- Structured multi-step thinking processes
- Problem decomposition and analysis
- Hypothesis generation and verification
- Iterative reasoning with course correction

### 2. Brave Search Server

The Brave Search server provides comprehensive web search capabilities for research and data collection.

**GitHub Repository:** [modelcontextprotocol/servers-archived - Brave Search](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/brave-search)

**Installation:**
No manual installation required. The server uses `npx` to automatically download and run the latest version.

**API Key Setup Required:**

1. **Get a Brave Search API Key:**
   - Visit [Brave Search API](https://api.search.brave.com/)
   - Sign up for a free account
   - Navigate to your dashboard
   - Create a new API key
   - Copy the API key

2. **Configure the API Key:**
   - Open `mcp.json` in this directory
   - Replace `YOUR_BRAVE_API_KEY_HERE` with your actual API key:
   ```json
   {
     "mcpServers": {
       "brave-search": {
         "command": "npx",
         "args": [
           "-y",
           "@modelcontextprotocol/server-brave-search"
         ],
         "env": {
           "BRAVE_API_KEY": "your_actual_api_key_here"
         }
       }
     }
   }
   ```

**Capabilities:**
- Real-time web search across diverse sources
- News and article discovery
- Industry research and trend analysis
- Company information gathering
- Competitive intelligence collection

## Cursor Configuration

### 1. Copy MCP Configuration

Copy the `mcp.json` file to your Cursor MCP configuration directory:

**macOS:**
```bash
cp mcp.json ~/.cursor/mcp_config/mcp.json
```

**Windows:**
```cmd
copy mcp.json %APPDATA%\Cursor\mcp_config\mcp.json
```

### 2. Restart Cursor

After copying the configuration file, restart Cursor completely for the changes to take effect.

### 3. Verify MCP Servers

1. Open Cursor
2. Look for MCP server indicators in the status bar
3. Test functionality by using the research templates in the `Prompt_Templates` directory

## Usage with Project Snow Owl Templates

Once configured, the MCP servers integrate seamlessly with all Project Snow Owl templates:

### Sequential Thinking Integration
- **Industry Analysis**: Structured trend analysis and prioritization
- **Regulatory Research**: Systematic compliance requirement analysis
- **Executive Research**: Comprehensive stakeholder mapping
- **Account Planning**: Strategic opportunity analysis and planning

### Brave Search Integration
- **Company News**: Real-time news discovery and monitoring
- **Industry Analysis**: Market research and competitive intelligence
- **Executive Research**: Professional background verification
- **Engagement Calendar**: Event discovery and opportunity identification

## Troubleshooting

### Common Issues

**Node.js Not Found:**
- Ensure Node.js is properly installed and added to your system PATH
- Restart your terminal/command prompt after installation
- Try running `which node` (macOS/Linux) or `where node` (Windows) to verify installation

**MCP Servers Not Loading:**
- Verify `mcp.json` is in the correct Cursor configuration directory
- Check that your Brave API key is correctly configured
- Restart Cursor completely
- Check Cursor's developer console for error messages

**Brave Search API Errors:**
- Verify your API key is active and has remaining quota
- Check that the API key is correctly formatted in `mcp.json`
- Ensure no extra spaces or characters in the API key

**Permission Errors:**
- On macOS/Linux, you may need to use `sudo` for global npm installations
- On Windows, run Command Prompt or PowerShell as Administrator

### Getting Help

If you encounter issues:
1. Check the [Cursor MCP Documentation](https://cursor.sh/docs/mcp)
2. Verify Node.js installation with `node --version` and `npm --version`
3. Review Cursor's developer console for detailed error messages
4. Ensure your Brave Search API key is valid and active

## Security Notes

- **Never commit your actual Brave API key to version control**
- Keep your API key secure and don't share it
- Regularly rotate your API keys for security
- Monitor your API usage to detect any unusual activity

## Version Requirements

- **Node.js**: Version 18.0 or higher recommended
- **npm**: Version 8.0 or higher recommended
- **Cursor**: Latest version with MCP support
- **MCP Servers**: Latest versions (automatically handled by npx)

## Updates

The MCP servers automatically update to the latest versions when using `npx` with the `-y` flag. No manual updates are required for the servers themselves. However, you should:

- Periodically update Node.js to the latest LTS version
- Keep Cursor updated to the latest version
- Monitor the MCP server repositories for any breaking changes or new features
