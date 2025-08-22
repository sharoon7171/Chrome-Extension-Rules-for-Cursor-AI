# Chrome Extension Rules for Cursor AI

**Created by [sqtech.dev](https://sqtech.dev)**

This repository contains comprehensive rules for Cursor AI to ensure professional, compliant, and efficient Chrome extension development following the latest August 2025 Chrome Web Store policies.

## 🎯 Purpose

These rules configure Cursor AI to:
- **Always ask for user approval** before making any changes
- **Never skip complex coding tasks** or file sections
- **Use terminal verification** for all changes
- **Follow Chrome extension compliance** standards
- **Maintain professional code quality** and structure

## 📋 Rule Files Overview

### Core Behavior Rules
1. **01-core-behavior.mdc** - Fundamental AI behavior with user approval requirements
2. **08-user-approval-required.mdc** - Detailed user approval process and examples

### Development Quality Rules
3. **02-task-management.mdc** - Task division and comprehensive handling
4. **03-code-generation.mdc** - Efficient code creation without complete rewrites
5. **09-comprehensive-code-analysis.mdc** - Complete file scanning requirements
6. **06-anti-duplication-and-imports.mdc** - Prevent code duplication

### Code Standards Rules
7. **05-coding-style-and-structure.mdc** - Professional project structure and coding standards
8. **04-file-handling.mdc** - File operation guidelines

### Verification Rules
9. **07-comprehensive-verification.mdc** - Complete implementation verification
10. **10-terminal-verification.mdc** - Mandatory terminal command verification

### Compliance Rules
11. **11-chrome-extension-compliance.mdc** - Latest August 2025 Chrome Web Store policies

## 🚀 Key Features

### ✅ User Control
- **Never acts autonomously** - always asks for permission
- **Clear approval process** with specific action descriptions
- **User-focused collaboration** approach

### ✅ Complete Code Handling
- **Never skips complex tasks** - breaks them into manageable parts
- **Scans files in segments** to ensure complete understanding
- **Systematic approach** to large codebases

### ✅ Terminal Verification
- **Always uses terminal commands** for verification
- **Comprehensive testing** of all changes
- **Professional verification standards**

### ✅ Chrome Extension Compliance
- **Latest August 2025 policies** implementation
- **Manifest V3 requirements** enforcement
- **Code readability standards** maintenance
- **Security and privacy** compliance

### ✅ Professional Standards
- **Modern coding practices** with latest language features
- **Modular project structure** for maintainability
- **Anti-duplication measures** with proper imports
- **Quality assurance processes**

## 📁 Installation

1. Copy the `.cursor/rules/` directory to your project root
2. Ensure all rule files have `alwaysApply: true` (already configured)
3. Restart Cursor to apply the new rules

## 🔧 Rule Configuration

All rules are configured with:
```yaml
---
description: [Rule description]
globs: ['**/*']
alwaysApply: true
---
```

This ensures they apply to all files in your project at all times.

## 📖 Usage

Once installed, Cursor AI will:

1. **Ask for your approval** before any code changes
2. **Break down complex tasks** into manageable steps
3. **Scan files completely** without skipping sections
4. **Verify all changes** using terminal commands
5. **Ensure compliance** with Chrome extension policies

## 🛡️ Benefits

- **Full control** over AI actions
- **No missed tasks** or incomplete implementations
- **Professional code quality**
- **Chrome Web Store compliance**
- **Reduced debugging time**
- **Future-proof development**

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

**Free to use, modify, and distribute** - The MIT License allows anyone to use this code for any purpose with minimal restrictions.

## 🤝 Contributing

Feel free to submit improvements or additional rules that enhance the development experience.

---

**Last Updated:** August 2025  
**Compatible with:** Cursor AI with .mdc rule support  
**Target:** Chrome Extension Development with latest policies  
**Created by:** [sqtech.dev](https://sqtech.dev) - Professional Development Solutions

---

<div align="center">
  <p><strong>Built with ❤️ by <a href="https://sqtech.dev">sqtech.dev</a></strong></p>
  <p>Professional development tools and solutions for modern web applications</p>
</div>
