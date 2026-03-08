---
config: AI-Assisted Programming
date: '2026-03-08T23:53:34.024633'
layout: post
model: deepseek-chat
title: AI-Assisted Programming Digest
total_tokens: 7303
---

<main>
    <h2>THIS WEEK'S BIG PICTURE</h2>
    <p>This week saw a major model release with OpenAI's GPT-5.4, emphasizing its coding and tool-use capabilities, while the industry grapples with the practical and security implications of agentic workflows. The focus is shifting from raw code generation to the reliability and safety of AI-executed code, highlighted by new security tools, anti-patterns for collaboration, and a stark demonstration of prompt injection risks in automated issue triage. Meanwhile, major players are courting open-source maintainers with free access to premium AI tools.</p>

    <h2>TOP 3 TOOLS/TECHNIQUES TO KNOW</h2>
    <ul>
        <li>
            <h3><a href="https://openai.com/index/introducing-gpt-5-4/">Introducing GPT‑5.4</a></h3>
            <p><strong>What it is:</strong> OpenAI's latest frontier model, featuring state-of-the-art coding, computer use, and a 1 million token context window.</p>
            <p><strong>Why it matters:</strong> For developers, the enhanced coding and tool-use capabilities promise more reliable agentic workflows and complex task handling, while the massive context allows for deeper project analysis.</p>
            <p><strong>Key detail:</strong> Available via API as `gpt-5.4` and `gpt-5.4-pro`, with an August 31st, 2025 knowledge cutoff.</p>
        </li>
        <li>
            <h3><a href="https://github.blog/security/how-to-scan-for-vulnerabilities-with-github-security-labs-open-source-ai-powered-framework/">How to scan for vulnerabilities with GitHub Security Lab’s open source AI-powered framework</a></h3>
            <p><strong>What it is:</strong> GitHub Security Lab's open-source "Taskflow Agent" for AI-powered vulnerability scanning.</p>
            <p><strong>Why it matters:</strong> It provides a concrete, open-source tool to address the critical need for security in AI-generated code, specifically effective at finding high-impact vulnerabilities like auth bypasses and IDORs.</p>
            <p><strong>Key detail:</strong> The framework is open source, allowing teams to integrate and customize AI-powered security scanning into their own workflows.</p>
        </li>
        <li>
            <h3><a href="https://simonwillison.net/guides/agentic-engineering-patterns/anti-patterns/">Anti-patterns: things to avoid</a></h3>
            <p><strong>What it is:</strong> A guide outlining common detrimental practices when using AI coding agents in team environments.</p>
            <p><strong>Why it matters:</strong> It addresses the growing friction caused by AI use, such as submitting unreviewed code in PRs, which erodes team trust and code quality.</p>
            <p><strong>Key detail:</strong> The primary rule: never file a pull request with code you haven't personally reviewed and understood, even if an AI wrote it.</p>
        </li>
    </ul>

    <h2>CODE & WORKFLOW UPDATES</h2>

    <h3>MODELS & APIs</h3>
    <p><strong><a href="https://simonwillison.net/2026/Mar/3/gemini-31-flash-lite/">Gemini 3.1 Flash-Lite</a></strong></p>
    <p><strong>What's new:</strong> Google released a significantly cheaper variant of its Gemini Flash model family.</p>
    <p><strong>Capability claims:</strong> Priced at $0.25/million input tokens and $1.5/million output tokens, it's positioned as a cost-effective option for tasks where top-tier reasoning isn't required, supporting configurable "thinking levels."</p>

    <h3>TOOLS & INTEGRATIONS</h3>
    <p><strong><a href="https://openai.com/index/chatgpt-for-excel">Introducing ChatGPT for Excel and new financial data integrations</a></strong></p>
    <p><strong>New integration:</strong> Direct ChatGPT integration for Microsoft Excel, powered by GPT-5.4.</p>
    <p><strong>Key detail:</strong> Aimed at accelerating modeling and analysis within regulated environments like finance, suggesting built-in compliance and data handling considerations.</p>

    <h3>PRACTICAL WORKFLOWS</h3>
    <p><strong><a href="https://simonwillison.net/guides/agentic-engineering-patterns/agentic-manual-testing/">Agentic manual testing</a></strong></p>
    <p><strong>Specific technique:</strong> The foundational pattern of having a coding agent execute the code it writes to verify it works.</p>
    <p><strong>When it works best:</strong> This is the core principle that differentiates useful coding agents from simple code generators; it should be the baseline for any non-trivial AI coding task to avoid deploying broken code.</p>

    <h2>QUICK LINKS</h2>
    <ul>
        <li><a href="https://simonwillison.net/2026/Mar/6/clinejection/">Clinejection — Compromising Cline's Production Releases just by Prompting an Issue Triager</a> - A sobering case study of a prompt injection attack against an AI-powered GitHub issue triager.</li>
        <li><a href="https://simonwillison.net/2026/Mar/7/codex-for-open-source/">Codex for Open Source</a> - OpenAI is offering six months of free ChatGPT Pro with Codex to maintainers of popular open-source projects.</li>
        <li><a href="https://lucumr.pocoo.org/2026/3/5/theseus/">AI And The Ship of Theseus</a> - A thoughtful piece on how AI "clean room" re-implementations challenge traditional concepts of code ownership and licensing.</li>
    </ul>
</main>