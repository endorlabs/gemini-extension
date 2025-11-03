# Endor Labs Gemini CLI Extension

This extension integrates the Endor Labs MCP server with Gemini CLI, enabling advanced code analysis and vulnerability scanning capabilities directly from your terminal through natural language interactions.

## Prerequisites

- **Gemini CLI:** The Gemini CLI must be installed.
- **Endor Labs CLI (`endorctl`):** The `endorctl` tool must be installed and authenticated with Endor Labs.

## Installation

To install and run this extension, use the following command:

```bash
gemini extensions install https://github.com/endorlabs/gemini-extension.git
```

For local development, you can clone the repository and link the extension:

```bash
git clone https://github.com/endorlabs/gemini-extension.git
cd gemini-extension
gemini extensions link .
```

## Usage

Once installed, you can use natural language prompts within the Gemini CLI to interact with Endor Labs. The output of these commands will be a summary of the scan results, including any vulnerabilities found:

### Initialize Endor Labs
```bash
gemini> Initialize Endor Labs with Google authentication using the command `endorctl init --auth-mode=google`
```

### Security Scanning
```bash
gemini> Scan my project for security vulnerabilities
gemini> Check dependencies for known CVEs
gemini> Generate a security report for this repository
```

## Verification

### Testing the Extension

To verify the extension is working correctly, you can run a security scan on a sample project. For example:

```bash
gemini> Scan my project for security vulnerabilities
```

Expected output will include a summary of any vulnerabilities found in your project's dependencies or code.

### Checking Connectivity

To ensure the extension is properly connected to the Endor Labs MCP server, you can use the `/mcp list` command within the Gemini CLI:

```bash
gemini> /mcp list
```

A successful response will list the available MCP servers, including the Endor Labs MCP server, indicating a healthy connection.