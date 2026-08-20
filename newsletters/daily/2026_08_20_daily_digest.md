<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#050505" style="background-color: #050505;">
<tr>
<td align="center" style="padding: 16px 8px;">

<table width="100%" cellpadding="0" cellspacing="0" style="width: 100%; max-width: 600px; font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;">

<!-- CARD: Ultra-FineWeb-L1 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://cdn-thumbnails.huggingface.co/social-thumbnails/datasets/openbmb/Ultra-FineWeb-L1.png" alt="Hugging Face dataset card for OpenBMB's Ultra-FineWeb-L1 pretraining corpus" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">DATASET</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-20</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Ultra-FineWeb-L1 — a 1.3T-token open web corpus for pretraining</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">A 1.3T-token English web corpus from OpenBMB, cleaned from six 2025 Common Crawl snapshots and free under Apache 2.0.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Ultra-FineWeb-L1 adds 1.3 trillion English tokens — roughly 1.14 billion documents — drawn from six Common Crawl snapshots taken during 2025. It ships as Parquet files under Apache 2.0 and sits at the L1 filtered layer of OpenBMB's UltraData framework.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Six cleaning steps produce the corpus: trafilatura 2.0 extracts main text, fastText drops non-English pages, heuristic rules cut low-quality text, sensitive fields are redacted, MinHash deduplication removes near-copies, and a final pass repairs broken encodings.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Pretraining data is the piece of the stack fewest labs publish. OpenBMB reports the same MiniCPM5-1B run scores 0.635 points higher on downstream evals when trained on Ultra-FineWeb-L1 instead of FineWeb, and the 2025 snapshots push the knowledge cutoff forward.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Teams pretraining open base models who need a large, high-quality, commercially usable English corpus without building their own pipeline.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">OpenBMB</td>
<td align="right" style="padding-top: 16px;"><a href="https://huggingface.co/datasets/openbmb/Ultra-FineWeb-L1" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Grok 4.6 on Amazon Bedrock -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://x.ai/images/news/og-grok-4-6-on-bedrock.webp" alt="xAI announcement card for Grok 4.6 arriving on Amazon Bedrock" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MODEL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-19</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Grok 4.6 on Amazon Bedrock — xAI's flagship opens to AWS teams</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Grok 4.6 is generally available on Amazon Bedrock, with a US-only and a global inference profile for AWS teams.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Amazon Bedrock now serves Grok 4.6 across every AWS Region where Bedrock runs. Two inference profiles: <code style="font-family: Menlo, Consolas, monospace; font-size: 13px;">us.xai.grok-4.6</code> for US-only data residency and <code style="font-family: Menlo, Consolas, monospace; font-size: 13px;">global.xai.grok-4.6</code> for higher throughput anywhere.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Calls go through Bedrock's Responses, Chat Completions and Converse APIs — no rewrite needed for existing Bedrock code. The model keeps its 500K-token context window and four reasoning effort levels (low → xhigh), with billing landing in AWS Cost Explorer.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Regulated AWS shops that couldn't send prompts to a third-party endpoint can now reach xAI's flagship under existing IAM, logging and billing. The US geo profile answers data-residency requirements that blocked many enterprise teams outright.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
AWS enterprise teams building agents or long-context workflows who need to stay inside existing cloud governance — $2/1M input, $6/1M output.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">xAI</td>
<td align="right" style="padding-top: 16px;"><a href="https://x.ai/news/grok-4-6-amazon-bedrock" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: OpenAI Private Safety Processing -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://techcrunch.com/wp-content/uploads/2026/02/GettyImages-2236544149.jpg?resize=1200,800" alt="OpenAI CEO Sam Altman in profile against a plain white background" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">SECURITY</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-19</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Private Safety Processing — OpenAI's abuse check that stores no customer data</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">OpenAI previews an abuse check that reads across many conversations while storing none of them.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Private Safety Processing is a new OpenAI monitoring service, in preview with select customers, that looks for abuse patterns across several related conversations while Zero Data Retention stays fully in force — prompts and responses are never stored.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Rather than judging each request alone, it reviews inputs and outputs of multiple conversations together. When something looks suspicious it hands OpenAI a narrowly defined signal — not the underlying text. Customers can opt to share more if they want.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Companies with strict security requirements have had to choose between Zero Data Retention and abuse monitoring. Private Safety Processing removes that trade-off. TechCrunch notes Anthropic retains data for 30 days on certain models — the two labs are now offering visibly different deals to the same enterprise buyers.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Enterprise API teams with strict data-residency or compliance rules who couldn't previously enable abuse monitoring without sacrificing data-deletion guarantees.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">OpenAI</td>
<td align="right" style="padding-top: 16px;"><a href="https://techcrunch.com/2026/08/19/openai-seeks-to-one-up-anthropic-with-new-customer-privacy-protections/" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: Unsloth Dynamic 3.0 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://cdn-thumbnails.huggingface.co/social-thumbnails/models/unsloth/Qwen3.8-27B-GGUF.png" alt="Hugging Face model card banner for the Unsloth Qwen3.8-27B GGUF quantizations" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">ALGORITHM</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-19</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Unsloth Dynamic 3.0 — GGUF quants keep 10% more accuracy per gigabyte</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">Unsloth's third-generation quantization recipe squeezes more accuracy out of the same GGUF file size.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
Dynamic 3.0 changes how Unsloth converts full-precision LLM weights into GGUF files. Unsloth reports the result holds over 10% more top-1% accuracy than any other provider's file of the same size. The first set covers Qwen3.8-27B in eleven builds from 6.2 GB to 54.7 GB BF16.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Three changes drive the gain: a larger imatrix calibration set from agentic coding, chat and multilingual text; finer per-layer quantization type decisions; and a wider menu of quantization techniques. It's purely post-training — no QAT or distillation.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
File size is the binding constraint for anyone running a large open model on a single GPU or laptop. A Dynamic 3.0 quant can do work that previously needed the next size up, freeing VRAM for longer context. The Qwen3.8 GGUFs were downloaded 5.1 million times in five days.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Anyone running open models locally on consumer hardware, especially those already using llama.cpp or Unsloth Desktop.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Unsloth</td>
<td align="right" style="padding-top: 16px;"><a href="https://unsloth.ai/docs/basics/dynamic-3.0-ggufs" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: ai-memory v1.29.0 -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://opengraph.githubassets.com/092cd1f5911d99f74362e471820cd4d0818a6e04cf26b490302b0ce1d2d2ed84/akitaonrails/ai-memory" alt="GitHub social preview card for the akitaonrails/ai-memory repository" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">TOOL</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #f7ff00; color: #050505; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">MAJOR</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-19</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">ai-memory v1.29.0 — long-term memory that follows agents across CLIs</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">A local, git-versioned wiki of what your coding agent already figured out, readable by whichever agent you open next.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
ai-memory writes a persistent markdown wiki out of your coding-agent sessions so the next agent starts already knowing the project. Quit Claude Code mid-task, open Codex in the same directory, and continue without re-explaining the architecture. Around 18 agent CLIs are supported — v1.29.0 shipped 19 August 2026.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Lifecycle hooks capture prompts, tool calls and session boundaries, sanitized and capped at 16 KiB per observation. Those observations are consolidated into markdown pages kept under git. Retrieval mixes SQLite FTS5, entity matching, graph-neighbour ranking and optional vector similarity.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Switching coding tools throws away everything the previous agent learned — failed approaches, decisions, open questions. Keeping that record on disk in plain markdown under MIT means the notes outlive any one vendor. It hit #5 on GitHub Trending on August 20, with 3,310 stars.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Developers who switch between several coding agents — Claude Code, Cursor, Codex, Zed — and want persistent project knowledge without re-explaining context each time.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">AkitaOnRails</td>
<td align="right" style="padding-top: 16px;"><a href="https://github.com/akitaonrails/ai-memory" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
</tr>
</table>

</td>
</tr>
</table>
</td>
</tr>

<!-- CARD: smolvm untrusted sandbox -->
<tr>
<td style="padding-top: 16px;">
<table width="100%" cellpadding="0" cellspacing="0" bgcolor="#0e0e0e" style="background-color: #0e0e0e; border: 1px solid #f5f5f0;">

<tr>
<td>
<img src="https://opengraph.githubassets.com/1/smol-machines/smolvm" alt="GitHub repository card for smol-machines/smolvm" width="100%" style="width: 100%; max-width: 600px; height: auto; display: block; border-bottom: 1px solid #f5f5f0;">
</td>
</tr>

<tr>
<td style="padding: 16px;">

<div style="margin-bottom: 12px; line-height: 1.5;">
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">SECURITY</span>
<span style="display: inline-block; width: 6px;">&nbsp;</span>
<span style="display: inline-block; background-color: #181818; color: #f5f5f0; padding: 4px 10px; font-size: 11px; font-weight: 700; text-transform: uppercase; font-family: Menlo, Consolas, monospace; vertical-align: middle;">NOTABLE</span>
<span style="display: inline-block; padding-left: 12px; font-size: 13px; color: #8a8a85; vertical-align: middle;">2026-08-19</span>
</div>

<h2 style="margin: 0 0 8px; font-size: 24px; font-weight: 800; color: #f5f5f0; line-height: 1.2;">Simon Willison — smolvm boots a real VM per task to run untrusted code</h2>

<p style="margin: 0 0 20px; font-size: 15px; color: #8a8a85; line-height: 1.5;">A hands-on test of smolvm 1.8.3 as a per-task sandbox for code an AI agent should not be trusted to run on your machine.</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">What is it?</strong><br>
smolvm gives every untrusted task its own Linux virtual machine instead of a shared container. Simon Willison tested version 1.8.3 for running Python and JavaScript data transformations that came from a model — Apache-2.0, written in Rust, wrapping libkrun as its VM monitor.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">How does it work?</strong><br>
Each workload boots its own guest kernel via Hypervisor.framework (macOS), KVM (Linux), or Windows Hypervisor Platform — hypervisor-enforced isolation, not a shared kernel. Images use OCI format so any Docker Hub image can be booted as a microVM.
</p>

<p style="margin: 0 0 16px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Why does it matter?</strong><br>
Warm runs take about 48 ms, making a VM-per-task design practical where teams usually settle for containers. Willison confirmed isolation holds: a 1 GB allocation inside a 256 MiB VM fails cleanly, a fork bomb tears down without leaking, and a VM without network has none.
</p>

<p style="margin: 0 0 20px; font-size: 15px; color: #f5f5f0; line-height: 1.6;">
<strong style="color: #f7ff00;">Who is it for?</strong><br>
Agent and developer-tool builders who need strong isolation for model-generated code without the latency overhead of full container orchestration.
</p>

<table width="100%" cellpadding="0" cellspacing="0" style="border-top: 1px solid #2a2a28; padding-top: 16px;">
<tr>
<td style="font-size: 14px; font-weight: 700; color: #f5f5f0; padding-top: 16px;">Simon Willison</td>
<td align="right" style="padding-top: 16px;"><a href="https://simonwillison.net/2026/Aug/19/smolmachines-untrusted-sandbox/" style="color: #f7ff00; font-size: 13px; font-weight: 700; text-decoration: none; text-transform: uppercase; font-family: Menlo, Consolas, monospace;">DETAILS →</a></td>
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
