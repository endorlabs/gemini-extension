# Endor Labs Gemini CLI Extension

This extension integrates the Endor Labs MCP server with Gemini CLI, enabling advanced code analysis and vulnerability scanning capabilities directly from your terminal through natural language interactions.

## Prerequisites

- **Gemini CLI:** The Gemini CLI must be installed.
- **Endor Labs CLI (`endorctl`):** The `endorctl` tool must be installed and authenticated with Endor Labs.

## Installation

To install and run this extension, use the following command:

```bash
gemini extensions install endorlabs/gemini-extension
```

For local development, you can clone the repository and link the extension:

```bash
git clone https://github.com/endorlabs/gemini-extension.git
cd gemini-extension
gemini extensions link .
```

## Usage

Once installed, you can use natural language prompts within the Gemini CLI to interact with Endor Labs:

### Initialize Endor Labs
```bash
gemini> Initialize Endor Labs with Google authentication
gemini> Set up Endor Labs for this project
```

### Security Scanning
```bash
gemini> Scan my project for security vulnerabilities
gemini> Check dependencies for known CVEs
gemini> Generate a security report for this repository
```