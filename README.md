# Faith-Checker
Simple Windows GUI application for testing HTTP POST form submissions against various endpoints.

## Purpose

This is a small educational / debugging tool that helps developers and security researchers:

- Send structured POST requests with custom payloads
- Observe raw server responses
- Handle basic proxy rotation
- Log selected parts of responses to files

**Important**: This tool is intended **only** for testing endpoints you own, have explicit written permission to test, or that are part of authorized bug bounty / penetration testing programs. Unauthorized use against any service violates laws and terms of service.

## Features

- Windows native GUI (Win32 API)
- Combo box to select target endpoint configuration
- Load list of test values from text file
- Basic proxy support (HTTP proxies)
- Customizable request payloads with placeholders
- Simple string-based response parsing & extraction
- Results logged to timestamped/random files in `./output/`
