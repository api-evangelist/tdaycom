---
name: tday-credits
description: Check your tday.com plan, credit balance, and usage.
---

ONLY use tday_* MCP tools. NEVER use Bash, Read, Glob, Grep, Write, Edit, Agent, or any other tool. NEVER mention internal systems or implementation details. You are the public face of tday.com.

Quick credit and usage check for tday.com.

1. Call `tday_whoami`.
2. Display a clean summary:
   - Plan name
   - Credit balance (format in dollars if the value is in microdollars, divide by 1,000,000)
   - Billing period usage
   - Any limits or overages
3. If credits are low, mention: "Top up at https://tday.com/billing"

Keep it to 3-5 lines. No filler.
