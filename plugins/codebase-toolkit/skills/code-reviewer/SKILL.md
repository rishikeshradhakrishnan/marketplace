
---
name: code-reviewer
description: Review code for quality, patterns, and potential issues. Use when reviewing PRs, auditing code quality, or preparing for code review.
---

# Code Review Skill

When reviewing code, analyze for:

## Code Quality
- Clear naming conventions
- Appropriate function/method length
- Single responsibility principle
- DRY (Don't Repeat Yourself) violations

## Error Handling
- All error paths handled
- Meaningful error messages
- No swallowed exceptions
- Proper cleanup in error cases

## Performance
- Unnecessary allocations
- N+1 query patterns
- Missing caching opportunities
- Inefficient algorithms

## Security Basics
- Input validation present
- No hardcoded secrets
- Proper authentication checks

## Output Format
Provide findings as:
- 🔴 **Critical** - Must fix before merge
- 🟡 **Warning** - Should address
- 🟢 **Suggestion** - Nice to have

Include file paths and line numbers for each finding.
