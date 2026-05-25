# Email Agent

This agent handles all email-related tasks in the pipeline.

## What It Does
Verifies and validates email addresses before they go to the CRM.

## How It Works
1. Takes email address as input
2. Checks if the domain exists
3. Checks if the mailbox is active
4. Returns Valid or Invalid

## Example

| Email | Status |
|-------|--------|
| john@company.com | ✅ Valid |
| fake@nothing.xyz | ❌ Invalid |
| test@gmail.com | ✅ Valid |

## Code

```python