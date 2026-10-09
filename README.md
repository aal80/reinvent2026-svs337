# SVS337 - AWS Lambda MicroVMs: Strong Isolation for Agents & Beyond

(reinvent2026-SVS337)

Agents running generated code, multi-tenant platforms, and untrusted workloads all need strong isolation, but each traditional compute option forces a tradeoff. VMs isolate well but start slowly. Containers are fast but share a kernel. Functions scale to zero but limit state. Teams close the gaps with isolation logic they build and maintain themselves. Lambda MicroVMs offer sandboxes with VM-level isolation for each agent, tenant, or task: state that persists across invocations, automatic suspend on idle, resume on demand. This session covers how MicroVMs work, the security and isolation model, lifecycle management, and patterns for agentic sandboxing and untrusted code execution.

## Video (click to watch)
TBD
<!--
[![](https://img.youtube.com/vi/_____/0.jpg)](https://www.youtube.com/watch?v=_____)
-->

## Slides
* [Session presentation slides - TBD](./TBD.pdf?raw=true)

## Useful links
* [[Docs] Lambda MicroVM docs](https://docs.aws.amazon.com/lambda/latest/dg/lambda-microvms-guide.html)
* [[Workshop] Lambda MicroVM workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/6d4c8211-decb-4c20-932a-4de228ef152e/en-US)
* [[Samples] Lambda MicroVM sample patterns](https://serverlessland.com/patterns?services=lambda-microvms)

## Claude Managed Agents
* [[Webinar] Deploying secure production-ready agents with Claude Managed Agents on AWS](https://aal80.github.io/2026-webinar-aws-anthropic-claude-managed-agents-with-lambda-microvms/)
* [[Docs] Self-hosted sandboxes](https://platform.claude.com/docs/en/managed-agents/self-hosted-sandboxes)
* [[Docs] Security model: what you own](https://platform.claude.com/docs/en/managed-agents/self-hosted-sandboxes-security)
* [[Guide] AWS guide: Lambda MicroVMs as a sandbox for Claude Managed Agents](https://docs.aws.amazon.com/lambda/latest/dg/microvms-integrations-claude-managed-agents.html)
* [[Sample] AWS sample: reference solution](https://github.com/aws-samples/sample-lambda-microvm-claude-managed-agents)




