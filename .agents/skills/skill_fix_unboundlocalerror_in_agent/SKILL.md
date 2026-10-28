---
name: skill_fix_unboundlocalerror_in_agent
description: Reusable playbook: Fix UnboundLocalError in agent turn loop
---

# Fix UnboundLocalError in agent turn loop

## Problem & Error Symptoms
cannot access local variable response

## Root Cause
Observed during development.

## Verified Resolution & Playbook
Track last_usage explicitly before loop break.

*Generated automatically by Reflexion Procedural Memory on 2026-10-28 22:47:40*
