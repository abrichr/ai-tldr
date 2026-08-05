<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#050505" style="background-color: #050505;">
<tr>
<td align="center" style="padding: 16px 8px;">

<table width="100%" cellpadding="0" cellspacing="0" style="width: 100%; max-width: 600px; font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;">

<!-- CARD: LFM2.5-2.6B -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://cdn-thumbnails.huggingface.co/social-thumbnails/models/LiquidAI/LFM2.5-2.6B.png" alt="Liquid AI LFM2.5-2.6B model card social thumbnail on Hugging Face" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MODEL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-04</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">LFM2.5-2.6B — Liquid AI's 2.6B on-device agent competes with 4x-larger models</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">A 2.6B open-weight agent that plans, calls tools, and runs entirely on phones, laptops, and robots.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
LFM2.5-2.6B is Liquid AI's new 2.6B-parameter open-weight language model, built for agentic workflows that run entirely on-device. It ships with base and instruction-tuned checkpoints on Hugging Face, a 128K context window, and support for 16 languages.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The 30-layer hybrid stacks 22 double-gated convolution blocks with 8 grouped-query attention layers, pre-trained on ~34T tokens. Post-training turns the base into an agent through supervised fine-tuning, per-domain teacher distillation, and a final agentic reinforcement-learning stage.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
LFM2.5-2.6B lets developers deploy planning, tool calling, and multi-step reasoning without a cloud round-trip — 30 tok/s on a phone and 220 tok/s on an M5 Max CPU — while beating Gemma-4 and Qwen3.5 4.7B on tool use and instruction following.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Developers shipping local agents on phones, laptops, or robots; anyone needing capable agentic inference with zero cloud cost.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Liquid AI</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/liquidai-lfm2-5-2-6b" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Warp Agent CLI -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://cdn.sanity.io/images/1ygbk6d0/production/e0bead02c24e74b9b0fe8c3a57f7ab48df02ce94-1920x1080.png" alt="Warp Agent CLI running inside a terminal window" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-04</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Warp Agent CLI — the Warp coding agent goes standalone in any terminal</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Warp's multi-model coding agent ships as a standalone CLI you can drop into any terminal, with multiplexing, remote handoff, and BYO keys.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Warp Agent CLI takes the coding agent previously locked inside the Warp Terminal app and packages it as a standalone binary. It works in Ghostty, iTerm 2, VS Code's integrated terminal, Windows Terminal, and Apple's default Terminal — no Warp Terminal required.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
A native multiplexing layer keeps sessions persistent across directory switches and pipes full-screen apps like vim, gdb, and sqlite through without breaking. An auto-router picks a model per task from frontier and open-weight endpoints; subagents can be delegated or handed off to a cloud agent.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Warp Agent CLI removes the lock-in that kept teams on Warp Terminal to use its agent, giving Claude Code, Codex CLI, and Cursor a same-shape competitor that runs anywhere. The BYO-key free tier and $10 ad-hoc credit floor lower the entry cost considerably.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Developers on Ghostty, iTerm 2, VS Code, or Windows who want a capable coding agent without switching terminals; teams already on Warp who want to use it in CI or SSH sessions.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Warp</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/warp-agent-cli" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Shieldstral 1.0 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://mistral.ai/cms-media/api/media/file/Thumbnail-Model%3DShieldstral.jpg" alt="Mistral Shieldstral 1.0 announcement thumbnail" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MODEL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-04</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Shieldstral 1.0 — Mistral ships a 3B open safety classifier for text and images</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">A 3B open-weights safety classifier that reads a plain-language policy at inference, rates text or images, and fits in a 16GB GPU.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Shieldstral 1.0 is a compact safety classifier from Mistral for content moderation across text and images. Instead of learning one fixed rule set at training time, the model reads a plain-language policy at inference and answers yes/no about whether content violates it. Weights are open on Hugging Face under Apache 2.0.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The team frames moderation as binary question-answering, training on a unified 54M-sample dataset. The 3B parameter model takes a policy plus content and returns a calibrated yes/no probability in one forward pass, covering text-only, image-only, and text+image inputs across 12 languages.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Teams can rewrite a policy in a text file and re-run the classifier locally on one GPU — no retraining, no per-call API cost. Mistral reports Shieldstral matches or beats models up to 7x its size, including 97.7% F1 on VLGuard and 88.1% F1 on WildGuardTest.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Trust and safety teams, LLM app builders who need flexible, self-hostable content moderation without a black-box API dependency.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Mistral AI</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/mistral-shieldstral-1-0" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: LLM 0.32 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://opengraph.githubassets.com/1/simonw/llm/releases/tag/0.32" alt="GitHub release page for simonw/llm version 0.32" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-04</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">LLM 0.32 — Simon Willison's CLI ships reasoning traces and server-side tools</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">The de-facto Python CLI for LLMs turns its 0.32 alpha into a stable release, with reasoning traces, provider tools, and a Git-style log store.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
LLM 0.32 is the stable release of Simon Willison's open-source Python command-line tool and library for talking to language models. It adds streamed reasoning traces, OpenAI's Responses API, server-side tools like WebSearch and CodeInterpreter, and a new content-addressed SQLite log store.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Reasoning-capable OpenAI models default to the <code style="font-family: Menlo, Consolas, monospace; font-size: 13px;">/v1/responses</code> endpoint, letting reasoning interleave with tool calls across a chain. Reasoning summaries stream to stderr so the main output stays clean for piping. The log store keys every message by hash so conversations no longer duplicate JSON.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Server-side tools mean a single <code style="font-family: Menlo, Consolas, monospace; font-size: 13px;">llm -T websearch</code> flag now buys a working web-search-and-answer pipeline with no local scaffolding. The pause-for-approval hook and new log schema turn LLM into a viable base for longer agent loops without a separate framework.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Python developers writing CLI scripts against frontier LLMs, plugin authors, agent tinkerers who want a lightweight plumbing layer without a heavy framework.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Simon Willison</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/simonw-llm-0-32-aug4" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Cloudflare Workers AI FP8 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://blog.cloudflare.com/_emdash/api/media/file/01KZ1Q04GM9SA4QGPGPKWJQSJ6.png" alt="Cloudflare Workers AI header for Kimi and GLM quantization work" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-03</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Cloudflare Workers AI — FP8 doubles Kimi K2.6 context, INT4 cuts GLM 5.2 40%</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">FP8 KV cache and INT4 weights land on Workers AI, doubling context and shrinking checkpoints for Kimi K2.6 and GLM 5.2.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Cloudflare quantized how Workers AI serves two of the biggest open MoE models. Kimi K2.6's KV cache now runs at FP8 instead of BF16 — that alone doubles the context window. GLM 5.2's weights compress from 8-bit to 4-bit, shrinking each checkpoint from 705 GB to 421 GB.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The FP8 KV cache halves per-token memory during attention, so the same GPUs hold twice as many tokens — Kimi K2.6 jumps from 686K to 1.37M context. INT4 weight compression frees GPU memory for 1.18M tokens of KV cache per card and speeds decode up to 55% at low concurrency.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Anyone calling Kimi K2.6 or GLM 5.2 on Workers AI now gets longer context, faster responses, and roughly 30% lower cost — with no code change. Cloudflare calls both changes effectively lossless on their benchmarks.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Developers already using Workers AI who want more context headroom or lower latency without changing a line of code.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Cloudflare</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/cloudflare-workers-ai-kimi-glm-fp8" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: DeepSeek V4-Flash on MI300X -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://opengraph.githubassets.com/fe062dd43f9d925b03fc8898d6e0c18a6feb16d0acee68ba0a23d6df376984bb/ryanzhou/deepseek-v4-flash-mi300x" alt="GitHub repository card for ryanzhou/deepseek-v4-flash-mi300x" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">REPO</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">NOTABLE</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-04</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">DeepSeek V4-Flash on one MI300X — 168 tok/s decode, no quantization</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Docker Compose stack that runs the full 304B DeepSeek V4-Flash unquantized on a single AMD MI300X, hitting 168 tok/s decode.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
An Apache-2.0 vLLM overlay from developer ryanzhou that runs the full 304B DeepSeek V4-Flash model on one AMD MI300X GPU without weight quantization. The entire 156.67 GiB of weights fits in HBM3.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
The stack fixes AMD's FNUZ FP8 cache-writer for the MI300X, patches MoE routing corruption that hurt tool-calling accuracy, ships 21 GEMM shapes tuned for gfx942, and pairs a 20 GB GPU KV cache with a 96 GiB CPU KV tier. DSpark speculative decoding adds probabilistic drafting.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Vanilla vLLM misbehaved on the MI300X for months. This drop-in Docker Compose setup rents for about $1.99/hr on AMD Developer Cloud, giving self-hosted teams a cheaper, unquantized alternative to NVIDIA for the flagship DeepSeek model.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
AMD GPU users and self-hosted inference teams who want to run the full DeepSeek V4-Flash without NVIDIA hardware or weight quantization.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">ryanzhou</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/ryanzhou-deepseek-v4-flash-mi300x" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Swiftlet -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://opengraph.githubassets.com/aee21e068307c0f774c8adad0bb967e3ad2569a03b0cb9952ba041d64d71199a/leonickson1/Swiftlet" alt="Swiftlet GitHub repository social card" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">REPO</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">NOTABLE</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-03</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Swiftlet — 80B Qwen runs in 4.3 GB on a Mac, 35B on an iPhone</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Swift and Metal runtime that runs Qwen 35B on an iPhone and 80B on a Mac by streaming MoE experts from local storage.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Swiftlet is an Apache-2.0 project that hosts Qwen3-Next and Qwen3.5/3.6 hybrid MoE models on Apple devices. Only a small dense core sits in RAM; the routed mixture-of-experts weights stream from local storage as tokens need them.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Every token routes through a small subset of experts, so Swiftlet only loads the active experts into memory. The routed weights stream from disk on demand — dropping an 80B footprint from tens of gigabytes of RAM to about 4.3 GB peak, at the cost of extra storage I/O.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
MoE models of this size have needed workstations or servers until now. Swiftlet makes a 35B model feasible on an iPhone 17 at ~2.5 GB peak RAM and ~1 token/second, and 80B feasible on a consumer Mac at 4.3 GB RAM — entirely offline, no data leaves the device.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
iOS and macOS developers, on-device AI hobbyists who want the largest possible open-weight model running locally on Apple hardware.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">leonickson1</td>
<td align="right" style="padding-top: 16px;"><a href="https://ai-tldr.dev/releases/swiftlet-qwen-metal" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
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
