<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#050505" style="background-color: #050505;">
<tr>
<td align="center" style="padding: 16px 8px;">

<table width="100%" cellpadding="0" cellspacing="0" style="width: 100%; max-width: 600px; font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;">

<!-- CARD: Anthropic context-engineering rules for Claude 5 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://cdn.prod.website-files.com/68a44d4040f98a4adf2207b6/6a639c6b2e881afef80764c6_og_the-new-rules-of-context-engineering-for-claude-5-generation-models.jpg" alt="Anthropic blog banner for 'The new rules of context engineering for Claude 5 generation models'" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">ARTICLE</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-24</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Anthropic's new context-engineering rules — 80% less system prompt on Claude 5</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Anthropic just published the playbook for building Claude 5 agents — start by deleting 80% of your system prompt.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Anthropic engineer Thariq Shihipar's blog post lays out new context-engineering rules for Claude Opus 5 and Fable 5. The team cut more than 80% of Claude Code's own system prompt for these models with no measurable drop on coding evals.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The playbook swaps prescriptive rules for judgment-based guidance, replaces in-line tool examples with expressive tool interfaces, uses progressive disclosure through skills, and drops instruction repetition. The <code>/doctor</code> command audits an existing setup and proposes fixes.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Prompts written for Claude 4 carry dead weight on Claude 5. Following this playbook cuts token spend on every request, speeds up cold starts, and unlocks the exploratory behavior the newer models were tuned for.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Claude Code users, Anthropic SDK developers, and agent builders migrating from Claude 4 to Opus 5 or Fable 5.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">Anthropic</td>
<td align="right"><a href="https://claude.com/blog/the-new-rules-of-context-engineering-for-claude-5-generation-models" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Claude Code 2.1.219 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://opengraph.githubassets.com/24526cd9f128be20facd538d7b2f3d7cdfe427ae03671f0bc99d44936a3a051a/anthropics/claude-code/releases/tag/v2.1.219" alt="Claude Code v2.1.219 release page on GitHub" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-24</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Claude Code 2.1.219 — Opus 5 becomes default, subagents nest to depth 3</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Anthropic's terminal coding agent adopts Opus 5 as its default and lets subagents spin up their own subagents three layers deep.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Claude Code 2.1.219 makes Claude Opus 5 the default Opus model, arriving with a 1M-token context. The release also adds a strict sandbox network allowlist that refuses non-allowed hosts without prompting, and a new DirectoryAdded hook for session setup.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Subagents can now spawn their own subagents down to three levels deep — up from one. Set <code>CLAUDE_CODE_MAX_SUBAGENT_SPAWN_DEPTH=1</code> to keep the old flat behaviour. Opus 4.7 is removed from fast mode; fast mode now routes to Opus 5 or Opus 4.8.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Users of the Claude Code CLI pick up Opus 5's stronger long-horizon coding without changing model flags. The deeper subagent tree lets one workflow decompose a task into workers of workers — the shape complex orchestration actually needs.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Claude Code power users, teams running Claude Code in CI, and anyone building multi-agent workflows on top of the CLI.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">Anthropic</td>
<td align="right"><a href="https://github.com/anthropics/claude-code/releases/tag/v2.1.219" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Kimi K3 Redis zero-days -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi0TE9DH98zjhcQPB99o9CcCvYH1otVTUwpXl_9Af1Nbl89gqHBAqP2jtb-BFrmXdR-4OYmPOGJJoilFiac2ooKHM5Lbe_kD5kLpW1eRcdpOWsG53701lGhFi93e0UpvGrptdb2usksom4mF56GWE1of2M7KsmAZav9cENd90xYAVz7Dq3yPIBJEODDDaQ/s1700-e365/redis-0day.jpg" alt="Kimi K3 agents find Redis zero-day vulnerabilities" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">SECURITY</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #ff0040; color: #ffffff; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-24</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Kimi K3 finds Redis zero-days — 32 agents build authenticated RCE in 27 min</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">A 32-agent Kimi K3 run cloned Redis, fuzzed it, debugged crashes in GDB, and shipped an RCE proof of concept.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Researchers at Bera Buddies used Moonshot's Kimi K3 model to run an autonomous vulnerability-discovery workflow against Redis. The agents found 19 zero-days and wrote authenticated RCE exploits. Redis pushed seven patched versions on July 23 in response.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
32 specialised agents cloned the Redis source, generated fuzzers, instrumented the binary, and used GDB to root-cause crashes. The lead bug is a double-free in stream consumer groups; a separate heap overflow lives in the bundled RedisBloom TDigest module.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Every RCE chain requires an authenticated client, so this is not a pre-auth internet worm — but it shows a mid-tier open model orchestrating end-to-end zero-day discovery in minutes. Redis operators should upgrade to a patched build now.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Redis operators (upgrade to 6.2.23 / 7.2.15 / 7.4.10 / 8.2.8 / 8.4.5 / 8.6.5 / 8.8.1), security teams, and threat researchers.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">Bera Buddies</td>
<td align="right"><a href="https://thehackernews.com/2026/07/kimi-k3-agents-found-redis-zero-days.html" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Apertus 1.5 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://actu.epfl.ch/image/165800/1440x810.jpg" alt="Apertus 1.5 announcement banner from EPFL, showing the Swiss AI Initiative branding." width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MODEL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-24</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Apertus 1.5 — Switzerland's fully open 8B/70B goes multimodal</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Switzerland's fully open Apertus grows eyes and ears, keeps its Apache-2.0 promise.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Apertus 1.5 is the new release of Switzerland's fully open LLM, built by ETH Zurich, EPFL, and CSCS. It ships in 8B and 70B sizes and, for the first time, takes images and audio as input alongside text — all under Apache 2.0.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The team continued pretraining 1.0 checkpoints on the Alps supercomputer — 4T more tokens for the 8B, 2T for the 70B. Post-training added an optional thinking mode, better tool use, and a 262,144-token context window (4× Apertus 1.0).
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Apertus 1.5 gives Europe a sovereign, fully open multimodal option at a size teams can self-host. Because everything is public — data, weights, training code — regulators, hospitals, and public agencies can audit the whole stack.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
European labs, public-sector teams, and researchers who need an auditable open-weight multimodal model.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">Swiss AI Initiative</td>
<td align="right"><a href="https://apertus-ai.org/articles/2026-07-apertus-1-5/" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Grok Build Workflows -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://x.ai/images/news/workflows-og.png" alt="xAI Grok Build Workflows announcement" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-23</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Grok Build Workflows — xAI's coding CLI now fans a task across up to 1,024 parallel agents</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Grok Build learned to fan a job across up to 1,024 parallel agents, verify with independent skeptics, and post one report — from a single slash command.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Workflows are xAI's new orchestration layer on top of Grok Build, the company's terminal coding agent. A workflow spawns many sub-agents in parallel, gives each a slice of a larger job, and stitches the results together. It targets work that won't fit in one context window.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Each workflow run defaults to 128 concurrent agents and scales to 1,024. Sub-agent results pass through independent skeptic agents that try to refute findings before they land in the final report. Saved workflows live in <code>.grok/workflows/</code> as reusable slash commands.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Fan-out orchestration is the current frontier of coding-agent design. The 1,024-agent ceiling and built-in skeptic verification make Grok Build competitive on two jobs single-context coders can't handle: large PR reviews and 100-issue triage sweeps.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Engineering teams using Grok Build for large PR reviews, backlog triage, or codebase-wide audits. Available to SuperGrok and X Premium+ subscribers.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">xAI</td>
<td align="right"><a href="https://x.ai/news/workflows" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Grok in Google Workspace -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://x.ai/images/news/grok-in-google-workspace-og.png" alt="xAI Grok for Google Workspace announcement card" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-24</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Grok in Google Workspace — free xAI add-on lands inside Docs, Sheets, and Slides</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">xAI turned Grok on inside every Google Workspace doc, sheet, and slide — free, one install, cited cells and all.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Grok for Google Workspace is xAI's new marketplace add-on that puts a Grok sidebar inside Google Docs, Sheets, and Slides at no cost. One install through the Google Workspace Marketplace enables the assistant across all three apps.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The sidebar sends the current document, spreadsheet range, or slide outline to Grok on request. In Sheets, answers cite exact cell references; in Slides, Grok assembles decks from an outline; in Docs, it drafts, refines, and copyedits text with tone-consistent rewrites.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
This is xAI's second major productivity-suite launch in a week — Grok for Microsoft 365 arrived seven days earlier. Making the add-on free removes the biggest adoption barrier; teams on Workspace can trial Grok next to Gemini without a procurement conversation.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Google Workspace users who want Grok inside Docs, Sheets, and Slides without changing tools or paying for another AI seat.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">xAI</td>
<td align="right"><a href="https://x.ai/news/introducing-google-workspace-addon" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Alibaba open-code-review -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://repository-images.githubusercontent.com/1241960226/27bf01cb-17df-44d5-9b7b-bcf17c970c6d" alt="GitHub social card for alibaba/open-code-review, an open-source AI code review CLI" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-07-24</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Alibaba open-code-review — line-level LLM code review at 1/9 the tokens</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Hybrid pipeline + LLM code reviewer, battle-tested at Alibaba, now Apache-2.0 with 12.7k GitHub stars.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
open-code-review is a command-line code reviewer that reads a Git diff and posts precise, line-anchored comments. Alibaba built it internally and released it under Apache-2.0, plugging into OpenAI-compatible or Anthropic-compatible model providers.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Reviews start with a deterministic pipeline that applies a fine-tuned ruleset for common defects (NPE, thread-safety, XSS, SQL injection) and selects which chunks to spend tokens on. The LLM agent then does dynamic context retrieval and writes the line-level comments.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
On a 200 PR benchmark from 50 open-source repos, Alibaba reports higher precision and F1 than Claude Code at about 1/9 the token cost — the kind of gap that shows up on a monthly invoice.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Platform teams and open-source maintainers who want automated line-level code review without the token bill of a general-purpose coding agent.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0;">Alibaba</td>
<td align="right"><a href="https://github.com/alibaba/open-code-review" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- FOOTER -->
<tr>
<td style="padding-top: 32px; border-top: 2px solid #f5f5f0; text-align: center;">
<p style="margin: 0 0 8px; font-size: 20px; font-weight: 800; color: #f5f5f0;">All releases at <a href="https://ai-tldr.dev" style="color: #f7ff00; text-decoration: none;">ai-tldr.dev</a></p>
<p style="margin: 0; font-size: 14px; color: #8a8a85;">Simple explanations • No jargon • Updated daily</p>
</td>
</tr>

</table>
</td>
</tr>
</table>

<!-- Open-tracking pixel (pomegra analytics). Must be the last element in the body. -->
<img src="https://analytics.pomegra.io/p/iVFoPRUpT" width="1" height="1" alt="" style="display:none" border="0">
