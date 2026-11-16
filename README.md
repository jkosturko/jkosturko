# Hi, I'm Jessica

I build AI agents, research how they fail, and publish it so the field can build agents that are safe to ship.

I led engineering at Google and the New York Times. Now I work on this full time: I run a fleet of AI agents every day, and the failures I publish come from that work.

[![The Failure Key](https://img.shields.io/badge/The_Failure_Key-1f6feb?style=for-the-badge)](https://github.com/jkosturko/agent-failure-key)
[![Intent Gateway](https://img.shields.io/badge/Intent_Gateway-6e40c9?style=for-the-badge)](https://intentgateway.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge)](https://www.linkedin.com/in/jessicakosturko/)

## Focus areas

- how AI agents fail in production, and how to tell one failure from another
- checking that an agent did what was asked, not only that it reported success
- experiments on agents, such as fault injection with the prediction written down first
- solving the issue that we will soon expect humans to gate more systems than humans can meaningfully and reliably gate

## An Identification Key for Agent Failures

[**agent-failure-key**](https://github.com/jkosturko/agent-failure-key) is a playbook of differentiating failure modes so that systems can be built from the ground up with these failure modes in mind, and quick diagnostics when things go wrong.

It catalogs 36 failure modes in AI-orchestrated agent systems. Each one is grounded in logged incidents on an agent platform I designed and run in daily operation. Three of them:

- **Phantom Mutation.** The agent reports work it never did.
- **Probe Inflation.** The observer's probes inflate the health numbers.
- **Monitoring-Induced Rate Limit Amplification.** The watchdog causes the outage.

Free to use under CC BY 4.0, with a [PDF edition](https://intentgateway.ai/key).

<p align="center">
  <a href="https://github.com/jkosturko/agent-failure-key">
    <img src="assets/agent-failure-key-cover.png" width="520" alt="Cover of An Identification Key for Agent Failures: 36 operational failure modes in AI-orchestrated agent systems, by Jessica Kosturko">
  </a>
</p>

## Intent Gateway

My company, [Intent Gateway](https://intentgateway.ai), makes a platform for building and running AI agents that measures whether each one did what was asked, and catches it when it didn't. The failure key came out of running it. The platform code is private.

## Open source

- [**agent-failure-key**](https://github.com/jkosturko/agent-failure-key): the identification key above.
- [**obsidian-live-git-diff**](https://github.com/jkosturko/obsidian-live-git-diff): a side-by-side rendered git diff for Obsidian. Review what your AI agent changed without losing your comments.
- [**sre-skills**](https://github.com/jkosturko/sre-skills): incident response, diagnosis and runbook skills for AI agents.

## Tech stack

**Agents and evaluation**

![Claude](https://img.shields.io/badge/Claude-d97757?logo=anthropic&logoColor=white)
![Model Context Protocol](https://img.shields.io/badge/Model_Context_Protocol-444444)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?logo=vercel&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0a60b5)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425cc7?logo=opentelemetry&logoColor=white)

**Application**

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?logo=react&logoColor=61dafb)
![Hono](https://img.shields.io/badge/Hono-e36002?logo=hono&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003b57?logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ed?logo=docker&logoColor=white)

## Get in touch

If you'd like to talk about agent failures, or you think I could help you or your organization make agents safe to ship, reach me on [LinkedIn](https://www.linkedin.com/in/jessicakosturko/).
