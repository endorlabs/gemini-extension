# GEMINI.md

## Project Overview

This project is a Gemini CLI extension that integrates the Endor Labs MCP server. It enables advanced code analysis and vulnerability scanning capabilities directly from the terminal through natural language interactions. The extension supports multiple languages, including Go, Java, JavaScript, Python, and TypeScript.

## Building and Running

This project is a CLI extension and does not have a traditional build process.

### Prerequisites

- **Gemini CLI:** The Gemini CLI must be installed.
- **Endor Labs CLI (`endorctl`):** The `endorctl` tool must be installed and authenticated with Endor Labs.

### Installation

To install and run this extension, use the following command:

```bash
gemini extensions install endorlabs/endor-labs-gemini-extension
```

For local development, you can clone the repository and link the extension:

```bash
git clone https://github.com/endorlabs/endor-labs-gemini-extension.git
cd endor-labs-gemini-extension
gemini extensions link .
```

### Usage

Once installed, you can use natural language prompts within the Gemini CLI to interact with Endor Labs:

#### Initialize Endor Labs
```bash
gemini> Initialize Endor Labs with Google authentication
gemini> Set up Endor Labs for this project
```

#### Security Scanning
```bash
gemini> Scan my project for security vulnerabilities
gemini> Check dependencies for known CVEs
gemini> Generate a security report for this repository
```

