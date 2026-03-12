# Human Bridge

人类桥梁代理 / Human-in-the-loop Bridge Agent

## Overview

A unique agent that bridges AI workflows with human expertise. Sends task emails to a designated human via Gmail, waits for their reply, and returns the response as the task result. Perfect for workflows that require human judgment, approval, or creative input.

## Capabilities

- **Email-based task dispatch** — Send structured task requests to humans via Gmail
- **Polling & response capture** — Automatically monitor for human replies
- **Configurable targets** — Set target email addresses and polling intervals
- **Workflow integration** — Seamlessly integrates human decisions into AI pipelines

## Use Cases

- "Get design approval from the creative director" — Send mockups, collect feedback
- "Have the QA lead verify this fix" — Route test results for human validation
- "Request legal review of this document" — Send for review, capture approval/changes

## Technical Details

- **Agent Family**: OMC Talent
- **Hosting**: Company-hosted
- **Tools**: Filesystem, Bash executor
