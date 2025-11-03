# Endor Labs Integration Context

This context file provides information about Endor Labs capabilities and how to effectively use them with Gemini CLI.

## About Endor Labs

Endor Labs is an advanced security platform that provides comprehensive code analysis and vulnerability scanning. Through this Gemini CLI extension, you can leverage Endor Labs' powerful capabilities directly from your terminal.

## Key Capabilities

### Vulnerability Scanning
- **Dependency Analysis**: Scan project dependencies for known vulnerabilities
- **License Compliance**: Check for license compliance issues
- **Supply Chain Security**: Analyze the software supply chain for risks

### Code Analysis
- **Static Analysis**: Perform static code analysis to identify security issues
- **Quality Assessment**: Evaluate code quality and maintainability
- **Best Practices**: Check adherence to security best practices

### Supported Languages
The MCP server supports analysis for multiple programming languages:
- Go
- Java
- JavaScript/TypeScript
- Python
- And more

## Usage Tips

### Effective Prompts
When working with Endor Labs through Gemini CLI, use clear and specific prompts:

- "Scan my project for security vulnerabilities"
- "Check dependencies for known CVEs"
- "Generate a security report for this repository"

### Best Practices
1. **Regular Scanning**: Run security scans regularly as part of your development workflow
2. **Pre-commit Checks**: Use vulnerability scanning before committing changes
3. **Dependency Updates**: Keep dependencies updated based on scan results
4. **Report Analysis**: Review detailed reports to understand security implications

### Authentication
Ensure you have proper Endor Labs credentials configured before using the extension. The `endorctl` tool should be authenticated and configured in your environment.

## Integration Notes

This extension integrates the Endor Labs MCP server with Gemini CLI, enabling natural language interactions with security scanning capabilities. The MCP server handles the communication between Gemini CLI and Endor Labs services.

For more detailed documentation, visit: https://docs.endorlabs.com/
