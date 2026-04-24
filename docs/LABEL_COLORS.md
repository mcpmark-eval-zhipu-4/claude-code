# Label Organization Guide

This document provides a comprehensive reference to all labels used in this repository. It serves as a guide for contributors to understand, use, and maintain the label organization system for better visual organization and easier issue triage.

## Label Categories

| Label Name | Category | Description |
|------------|----------|-------------|
| critical | Priority | Indicates a critical issue that requires immediate attention |
| hotfix | Type | Indicates an urgent fix for a production issue |
| memory | Area | Indicates an issue related to memory management or allocation |
| high-priority | Priority | Indicates a high-priority issue requiring timely resolution |

### Priority Labels

Labels in this category indicate the importance or urgency of an issue:

| Label Name | Category | Color | Description |
|------------|----------|-------|-------------|
| **critical** | Priority | 🔴 Red | Critical issues that affect core functionality or cause severe problems. Use when the issue blocks users or causes data loss. Examples: application crashes, security vulnerabilities, complete feature failures. |
| **high-priority** | Priority | 🟠 Orange | High priority issues that should be addressed soon but are not as urgent as critical. Use for significant but not blocking issues. |

### Issue Type Labels

Labels in this category describe the nature of the issue:

| Label Name | Category | Color | Description |
|------------|----------|-------|-------------|
| **hotfix** | Type | 🟢 Green | Indicates an urgent fix for a production issue. These should be merged quickly to address real-world problems. |

### Area Labels

Labels in this category indicate the specific area of the codebase affected:

| Label Name | Category | Color | Description |
|------------|----------|-------|-------------|
| **memory** | Area | 🔵 Blue | Issues related to memory management, allocation, leaks, or optimization. Covers JavaScript heap issues and context management. |

## Usage Guidelines

### When to Use Priority Labels

**Use `critical` when:**
- The issue causes complete application failure
- The issue presents a security vulnerability
- The issue leads to data loss
- The issue affects multiple users significantly
- Platform-specific bugs that affect a large user base

**Use `high-priority` when:**
- The issue is important but doesn't completely block functionality
- There's a workaround available
- The issue should be resolved within a reasonable timeframe
- User experience is significantly impacted

### When to Use Type Labels

**Use `hotfix` when:**
- The issue affects production systems
- There's an established workaround, and it should be fixed quickly
- Multiple users are impacted and need an immediate resolution

### When to Use Area Labels

**Use `area` labels when:**
- The issue is specific to a particular part of the codebase
- The issue affects performance in a particular domain
- The issue requires knowledge of specific modules or components

### General Best Practices

1. **Be Consistent**: Apply labels consistently across the repository
2. **Be Specific**: Use the most specific label that fits (e.g., `memory` for heap issues)
3. **Be Timely**: Apply labels as soon as the issue is identified
4. **Review Regularly**: Review and cleanup labels periodically
5. **Communicate**: Inform the team about changes to the labeling system

## Label Color Reference

| Color | Hex Code | Usage |
|-------|----------|-------|
| Red | #E74C3C | Critical/Priority issues |
| Orange | #E67E22 | High-Priority issues |
| Green | #2ECC71 | Hotfix/Type issues |
| Blue | #3498DB | Area/Component issues |

## Visual Organization Benefits

### Issue Filtering

With proper labels, you can easily filter and organize issues:

- **By Priority**: Focus on high-priority or critical issues first
- **By Type**: Quickly identify hotfixes, bugs, or features
- **By Area**: Find issues in specific parts of the codebase

### Trend Analysis

Labels help in:
- Tracking issue distribution across categories
- Identifying patterns in bug reports
- Monitoring the health of specific areas of the codebase

### Contribution Tracking

Labels help maintainers:
- Assign issues to the right team members
- Prioritize work based on labels
- Generate reports on repository health

---

*Last updated: 2026-04-24*
*Total labels documented: 4*