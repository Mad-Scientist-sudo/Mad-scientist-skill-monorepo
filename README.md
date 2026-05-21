# Mad Scientist Skill Monorepo

<p align="center">
  <strong>155 standalone Mad Scientist agent skills, organized into individually installable packages.</strong>
</p>

<p align="center">
  <img alt="Skills" src="https://img.shields.io/badge/skills-155-111827?style=for-the-badge">
  <img alt="Packages" src="https://img.shields.io/badge/packages-155-7c3aed?style=for-the-badge">
  <img alt="Workspace" src="https://img.shields.io/badge/workspace-pnpm-2563eb?style=for-the-badge">
  <img alt="Layout" src="https://img.shields.io/badge/layout-categorized-059669?style=for-the-badge">
</p>

---

## What This Is

This repository is a category-organized monorepo of standalone `SKILL.md` packages. Most skills live under `packages/<category>/<skill-slug>/`, with a small set of legacy root packages under `packages/<skill-slug>/`.

Each package preserves the skill's instructions and supporting files such as scripts, references, examples, workflows, tests, templates, and assets.

## Layout

```text
mad-scientist-skill-monorepo/
  package.json
  pnpm-workspace.yaml
  packages/
    09-media-lifestyle/
      weather/
        SKILL.md
        package.json
    15-data-research/
      github-pr-workflow/
        SKILL.md
        package.json
    watch/
      SKILL.md
      package.json
```

## Quick Start

```bash
git clone https://github.com/Mad-Scientist-sudo/Mad-scientist-skill-monorepo.git
cd Mad-scientist-skill-monorepo
pnpm install
pnpm list
```

Inspect one skill:

```bash
cd packages/09-media-lifestyle/weather
sed -n '1,120p' SKILL.md
```

## Package Index

| Skill | Package |
|---|---|
| [`agent-browser`](./packages/14-devops/agent-browser) | `@mad-scientist-skills/agent-browser` |
| [`agentmail`](./packages/11-email/agentmail) | `@mad-scientist-skills/agentmail` |
| [`agentmail-productivity`](./packages/08-communication/agentmail-productivity) | `@mad-scientist-skills/agentmail-productivity` |
| [`airtable`](./packages/13-productivity/airtable) | `@mad-scientist-skills/airtable` |
| [`apify`](./packages/15-data-research/apify) | `@mad-scientist-skills/apify` |
| [`apple-notes`](./packages/10-apple/apple-notes) | `@mad-scientist-skills/apple-notes` |
| [`apple-reminders`](./packages/10-apple/apple-reminders) | `@mad-scientist-skills/apple-reminders` |
| [`architecture-diagram`](./packages/16-creative-ai/architecture-diagram) | `@mad-scientist-skills/architecture-diagram` |
| [`arxiv`](./packages/15-data-research/arxiv) | `@mad-scientist-skills/arxiv` |
| [`ascii-art`](./packages/16-creative-ai/ascii-art) | `@mad-scientist-skills/ascii-art` |
| [`ascii-video`](./packages/16-creative-ai/ascii-video) | `@mad-scientist-skills/ascii-video` |
| [`audiocraft-audio-generation`](./packages/19-lifestyle/audiocraft-audio-generation) | `@mad-scientist-skills/audiocraft-audio-generation` |
| [`axolotl`](./packages/12-mlops/axolotl) | `@mad-scientist-skills/axolotl` |
| [`baoyu-comic`](./packages/16-creative-ai/baoyu-comic) | `@mad-scientist-skills/baoyu-comic` |
| [`baoyu-infographic`](./packages/16-creative-ai/baoyu-infographic) | `@mad-scientist-skills/baoyu-infographic` |
| [`batchdata-skip-trace`](./packages/20-rei/batchdata-skip-trace) | `@mad-scientist-skills/batchdata-skip-trace` |
| [`beautiful-websites`](./packages/20-rei/beautiful-websites) | `@mad-scientist-skills/beautiful-websites` |
| [`blogwatcher`](./packages/15-data-research/blogwatcher) | `@mad-scientist-skills/blogwatcher` |
| [`blotato-text-poster`](./packages/18-social/blotato-text-poster) | `@mad-scientist-skills/blotato-text-poster` |
| [`brave-search`](./packages/15-data-research/brave-search) | `@mad-scientist-skills/brave-search` |
| [`browser-use-cloud`](./packages/14-devops/browser-use-cloud) | `@mad-scientist-skills/browser-use-cloud` |
| [`census-data`](./packages/15-data-research/census-data) | `@mad-scientist-skills/census-data` |
| [`claude-code`](./packages/17-ai-coding/claude-code) | `@mad-scientist-skills/claude-code` |
| [`claude-design`](./packages/17-ai-coding/claude-design) | `@mad-scientist-skills/claude-design` |
| [`clip`](./packages/12-mlops/clip) | `@mad-scientist-skills/clip` |
| [`codebase-inspection`](./packages/15-data-research/codebase-inspection) | `@mad-scientist-skills/codebase-inspection` |
| [`codex`](./packages/17-ai-coding/codex) | `@mad-scientist-skills/codex` |
| [`comfyui`](./packages/16-creative-ai/comfyui) | `@mad-scientist-skills/comfyui` |
| [`content-repurposer`](./packages/18-social/content-repurposer) | `@mad-scientist-skills/content-repurposer` |
| [`content-repurposing-engine`](./packages/18-social/content-repurposing-engine) | `@mad-scientist-skills/content-repurposing-engine` |
| [`copywriting`](./packages/18-social/copywriting) | `@mad-scientist-skills/copywriting` |
| [`daily-eod-report`](./packages/daily-eod-report) | `@mad-scientist-skills/daily-eod-report` |
| [`data-infographic-generator`](./packages/16-creative-ai/data-infographic-generator) | `@mad-scientist-skills/data-infographic-generator` |
| [`design-md`](./packages/16-creative-ai/design-md) | `@mad-scientist-skills/design-md` |
| [`discord`](./packages/08-communication/discord) | `@mad-scientist-skills/discord` |
| [`docker-management`](./packages/14-devops/docker-management) | `@mad-scientist-skills/docker-management` |
| [`dspy`](./packages/12-mlops/dspy) | `@mad-scientist-skills/dspy` |
| [`evaluating-llms-harness`](./packages/12-mlops/evaluating-llms-harness) | `@mad-scientist-skills/evaluating-llms-harness` |
| [`excalidraw`](./packages/16-creative-ai/excalidraw) | `@mad-scientist-skills/excalidraw` |
| [`fal-ai-video-generation`](./packages/16-creative-ai/fal-ai-video-generation) | `@mad-scientist-skills/fal-ai-video-generation` |
| [`find-nearby`](./packages/19-lifestyle/find-nearby) | `@mad-scientist-skills/find-nearby` |
| [`findmy`](./packages/10-apple/findmy) | `@mad-scientist-skills/findmy` |
| [`fine-tuning-with-trl`](./packages/12-mlops/fine-tuning-with-trl) | `@mad-scientist-skills/fine-tuning-with-trl` |
| [`firecrawl`](./packages/15-data-research/firecrawl) | `@mad-scientist-skills/firecrawl` |
| [`firehose`](./packages/15-data-research/firehose) | `@mad-scientist-skills/firehose` |
| [`fish-audio-tts`](./packages/09-media-lifestyle/fish-audio-tts) | `@mad-scientist-skills/fish-audio-tts` |
| [`frontend-design`](./packages/16-creative-ai/frontend-design) | `@mad-scientist-skills/frontend-design` |
| [`gemini-image-editor`](./packages/07-image-graphics/gemini-image-editor) | `@mad-scientist-skills/gemini-image-editor` |
| [`gguf-quantization`](./packages/12-mlops/gguf-quantization) | `@mad-scientist-skills/gguf-quantization` |
| [`github-auth`](./packages/15-data-research/github-auth) | `@mad-scientist-skills/github-auth` |
| [`github-issues`](./packages/15-data-research/github-issues) | `@mad-scientist-skills/github-issues` |
| [`github-pr-workflow`](./packages/15-data-research/github-pr-workflow) | `@mad-scientist-skills/github-pr-workflow` |
| [`github-repo-management`](./packages/15-data-research/github-repo-management) | `@mad-scientist-skills/github-repo-management` |
| [`godmode`](./packages/godmode) | `@mad-scientist-skills/godmode` |
| [`gohighlevel-api`](./packages/20-rei/gohighlevel-api) | `@mad-scientist-skills/gohighlevel-api` |
| [`google-workspace`](./packages/13-productivity/google-workspace) | `@mad-scientist-skills/google-workspace` |
| [`gpt-image-2`](./packages/18-social/gpt-image-2) | `@mad-scientist-skills/gpt-image-2` |
| [`graphic-design`](./packages/07-image-graphics/graphic-design) | `@mad-scientist-skills/graphic-design` |
| [`grpo-rl-training`](./packages/12-mlops/grpo-rl-training) | `@mad-scientist-skills/grpo-rl-training` |
| [`guidance`](./packages/12-mlops/guidance) | `@mad-scientist-skills/guidance` |
| [`hermes-agent`](./packages/21-hermes/hermes-agent) | `@mad-scientist-skills/hermes-agent` |
| [`hermes-agent-setup`](./packages/21-hermes/hermes-agent-setup) | `@mad-scientist-skills/hermes-agent-setup` |
| [`hermes-agent-skill-authoring`](./packages/21-hermes/hermes-agent-skill-authoring) | `@mad-scientist-skills/hermes-agent-skill-authoring` |
| [`hermes-multi-agent-telegram`](./packages/21-hermes/hermes-multi-agent-telegram) | `@mad-scientist-skills/hermes-multi-agent-telegram` |
| [`hermes-workspace-setup`](./packages/21-hermes/hermes-workspace-setup) | `@mad-scientist-skills/hermes-workspace-setup` |
| [`heygen-avatar-video`](./packages/20-rei/heygen-avatar-video) | `@mad-scientist-skills/heygen-avatar-video` |
| [`himalaya`](./packages/11-email/himalaya) | `@mad-scientist-skills/himalaya` |
| [`homedepot-repair-estimator`](./packages/20-rei/homedepot-repair-estimator) | `@mad-scientist-skills/homedepot-repair-estimator` |
| [`hr-hiring`](./packages/21-hermes/hr-hiring) | `@mad-scientist-skills/hr-hiring` |
| [`huggingface-hub`](./packages/12-mlops/huggingface-hub) | `@mad-scientist-skills/huggingface-hub` |
| [`humanizer`](./packages/16-creative-ai/humanizer) | `@mad-scientist-skills/humanizer` |
| [`ideation`](./packages/16-creative-ai/ideation) | `@mad-scientist-skills/ideation` |
| [`image-editing`](./packages/16-creative-ai/image-editing) | `@mad-scientist-skills/image-editing` |
| [`imessage`](./packages/10-apple/imessage) | `@mad-scientist-skills/imessage` |
| [`instagram-carousel-authority`](./packages/18-social/instagram-carousel-authority) | `@mad-scientist-skills/instagram-carousel-authority` |
| [`jupyter-live-kernel`](./packages/17-ai-coding/jupyter-live-kernel) | `@mad-scientist-skills/jupyter-live-kernel` |
| [`kanban-orchestrator`](./packages/14-devops/kanban-orchestrator) | `@mad-scientist-skills/kanban-orchestrator` |
| [`kanban-worker`](./packages/14-devops/kanban-worker) | `@mad-scientist-skills/kanban-worker` |
| [`landglide-lookup`](./packages/20-rei/landglide-lookup) | `@mad-scientist-skills/landglide-lookup` |
| [`linear`](./packages/13-productivity/linear) | `@mad-scientist-skills/linear` |
| [`llama-cpp`](./packages/12-mlops/llama-cpp) | `@mad-scientist-skills/llama-cpp` |
| [`llm-wiki`](./packages/15-data-research/llm-wiki) | `@mad-scientist-skills/llm-wiki` |
| [`macos-computer-use`](./packages/10-apple/macos-computer-use) | `@mad-scientist-skills/macos-computer-use` |
| [`mad-census-baby`](./packages/15-data-research/mad-census-baby) | `@mad-scientist-skills/mad-census-baby` |
| [`mad-event-maker`](./packages/20-rei/mad-event-maker) | `@mad-scientist-skills/mad-event-maker` |
| [`mad-graphic-designer-skill`](./packages/18-social/mad-graphic-designer-skill) | `@mad-scientist-skills/mad-graphic-designer-skill` |
| [`mad-skip-trace`](./packages/20-rei/mad-skip-trace) | `@mad-scientist-skills/mad-skip-trace` |
| [`manim-video`](./packages/16-creative-ai/manim-video) | `@mad-scientist-skills/manim-video` |
| [`maps`](./packages/13-productivity/maps) | `@mad-scientist-skills/maps` |
| [`mcporter-agent`](./packages/17-ai-coding/mcporter-agent) | `@mad-scientist-skills/mcporter-agent` |
| [`melissa-data-information`](./packages/15-data-research/melissa-data-information) | `@mad-scientist-skills/melissa-data-information` |
| [`minecraft-modpack-server`](./packages/19-lifestyle/minecraft-modpack-server) | `@mad-scientist-skills/minecraft-modpack-server` |
| [`ml-paper-writing`](./packages/ml-paper-writing) | `@mad-scientist-skills/ml-paper-writing` |
| [`modal-serverless-gpu`](./packages/12-mlops/modal-serverless-gpu) | `@mad-scientist-skills/modal-serverless-gpu` |
| [`nano-banana-image-gen`](./packages/07-image-graphics/nano-banana-image-gen) | `@mad-scientist-skills/nano-banana-image-gen` |
| [`nano-banana-pro`](./packages/07-image-graphics/nano-banana-pro) | `@mad-scientist-skills/nano-banana-pro` |
| [`nano-pdf`](./packages/13-productivity/nano-pdf) | `@mad-scientist-skills/nano-pdf` |
| [`native-mcp`](./packages/21-hermes/native-mcp) | `@mad-scientist-skills/native-mcp` |
| [`notion`](./packages/13-productivity/notion) | `@mad-scientist-skills/notion` |
| [`notion-mastery`](./packages/11-email/notion-mastery) | `@mad-scientist-skills/notion-mastery` |
| [`nova-youtube-agent`](./packages/18-social/nova-youtube-agent) | `@mad-scientist-skills/nova-youtube-agent` |
| [`obliteratus`](./packages/12-mlops/obliteratus) | `@mad-scientist-skills/obliteratus` |
| [`obsidian`](./packages/obsidian) | `@mad-scientist-skills/obsidian` |
| [`ocr-and-documents`](./packages/13-productivity/ocr-and-documents) | `@mad-scientist-skills/ocr-and-documents` |
| [`openai-whisper-api`](./packages/17-ai-coding/openai-whisper-api) | `@mad-scientist-skills/openai-whisper-api` |
| [`opencode`](./packages/17-ai-coding/opencode) | `@mad-scientist-skills/opencode` |
| [`openhue`](./packages/19-lifestyle/openhue) | `@mad-scientist-skills/openhue` |
| [`opus-blotato-video-poster`](./packages/18-social/opus-blotato-video-poster) | `@mad-scientist-skills/opus-blotato-video-poster` |
| [`opus-clip-mcp`](./packages/18-social/opus-clip-mcp) | `@mad-scientist-skills/opus-clip-mcp` |
| [`outlines`](./packages/12-mlops/outlines) | `@mad-scientist-skills/outlines` |
| [`owner-skip-trace`](./packages/20-rei/owner-skip-trace) | `@mad-scientist-skills/owner-skip-trace` |
| [`p5js`](./packages/16-creative-ai/p5js) | `@mad-scientist-skills/p5js` |
| [`pdf-generation`](./packages/11-email/pdf-generation) | `@mad-scientist-skills/pdf-generation` |
| [`peft-fine-tuning`](./packages/12-mlops/peft-fine-tuning) | `@mad-scientist-skills/peft-fine-tuning` |
| [`pixel-art`](./packages/16-creative-ai/pixel-art) | `@mad-scientist-skills/pixel-art` |
| [`pokemon-player`](./packages/19-lifestyle/pokemon-player) | `@mad-scientist-skills/pokemon-player` |
| [`polymarket`](./packages/15-data-research/polymarket) | `@mad-scientist-skills/polymarket` |
| [`popular-web-designs`](./packages/16-creative-ai/popular-web-designs) | `@mad-scientist-skills/popular-web-designs` |
| [`powerpoint`](./packages/13-productivity/powerpoint) | `@mad-scientist-skills/powerpoint` |
| [`pretext`](./packages/16-creative-ai/pretext) | `@mad-scientist-skills/pretext` |
| [`property-contact-research`](./packages/20-rei/property-contact-research) | `@mad-scientist-skills/property-contact-research` |
| [`pytorch-fsdp`](./packages/12-mlops/pytorch-fsdp) | `@mad-scientist-skills/pytorch-fsdp` |
| [`reels-text-overlay`](./packages/16-creative-ai/reels-text-overlay) | `@mad-scientist-skills/reels-text-overlay` |
| [`rei-ai-weekly-newsletter`](./packages/20-rei/rei-ai-weekly-newsletter) | `@mad-scientist-skills/rei-ai-weekly-newsletter` |
| [`rei-ai-zoom-processor`](./packages/20-rei/rei-ai-zoom-processor) | `@mad-scientist-skills/rei-ai-zoom-processor` |
| [`remotion`](./packages/16-creative-ai/remotion) | `@mad-scientist-skills/remotion` |
| [`remotion-video-editing`](./packages/16-creative-ai/remotion-video-editing) | `@mad-scientist-skills/remotion-video-editing` |
| [`rentcast-property-report`](./packages/20-rei/rentcast-property-report) | `@mad-scientist-skills/rentcast-property-report` |
| [`research-paper-writing`](./packages/research-paper-writing) | `@mad-scientist-skills/research-paper-writing` |
| [`sarah-outbound-caller`](./packages/20-rei/sarah-outbound-caller) | `@mad-scientist-skills/sarah-outbound-caller` |
| [`seedance-2-video-maker`](./packages/16-creative-ai/seedance-2-video-maker) | `@mad-scientist-skills/seedance-2-video-maker` |
| [`segment-anything-model`](./packages/12-mlops/segment-anything-model) | `@mad-scientist-skills/segment-anything-model` |
| [`seo-audit`](./packages/15-data-research/seo-audit) | `@mad-scientist-skills/seo-audit` |
| [`service-deployment-and-monitoring`](./packages/14-devops/service-deployment-and-monitoring) | `@mad-scientist-skills/service-deployment-and-monitoring` |
| [`serving-llms-vllm`](./packages/12-mlops/serving-llms-vllm) | `@mad-scientist-skills/serving-llms-vllm` |
| [`sketch`](./packages/16-creative-ai/sketch) | `@mad-scientist-skills/sketch` |
| [`songwriting-and-ai-music`](./packages/16-creative-ai/songwriting-and-ai-music) | `@mad-scientist-skills/songwriting-and-ai-music` |
| [`stable-diffusion-image-generation`](./packages/16-creative-ai/stable-diffusion-image-generation) | `@mad-scientist-skills/stable-diffusion-image-generation` |
| [`supadata-transcript`](./packages/18-social/supadata-transcript) | `@mad-scientist-skills/supadata-transcript` |
| [`teams-meeting-pipeline`](./packages/13-productivity/teams-meeting-pipeline) | `@mad-scientist-skills/teams-meeting-pipeline` |
| [`touchdesigner-mcp`](./packages/16-creative-ai/touchdesigner-mcp) | `@mad-scientist-skills/touchdesigner-mcp` |
| [`unsloth`](./packages/12-mlops/unsloth) | `@mad-scientist-skills/unsloth` |
| [`vercel`](./packages/14-devops/vercel) | `@mad-scientist-skills/vercel` |
| [`vercel-deploy`](./packages/14-devops/vercel-deploy) | `@mad-scientist-skills/vercel-deploy` |
| [`vercel-site-deploy`](./packages/14-devops/vercel-site-deploy) | `@mad-scientist-skills/vercel-site-deploy` |
| [`video-transcribe-and-timestamp`](./packages/18-social/video-transcribe-and-timestamp) | `@mad-scientist-skills/video-transcribe-and-timestamp` |
| [`watch`](./packages/watch) | `@mad-scientist-skills/watch` |
| [`weather`](./packages/09-media-lifestyle/weather) | `@mad-scientist-skills/weather` |
| [`weights-and-biases`](./packages/12-mlops/weights-and-biases) | `@mad-scientist-skills/weights-and-biases` |
| [`whisper`](./packages/17-ai-coding/whisper) | `@mad-scientist-skills/whisper` |
| [`xitter`](./packages/18-social/xitter) | `@mad-scientist-skills/xitter` |
| [`xurl`](./packages/18-social/xurl) | `@mad-scientist-skills/xurl` |
| [`youtube-content`](./packages/09-media-lifestyle/youtube-content) | `@mad-scientist-skills/youtube-content` |
| [`youtube-opus-skill`](./packages/18-social/youtube-opus-skill) | `@mad-scientist-skills/youtube-opus-skill` |
| [`yt-thumbnail-creator`](./packages/18-social/yt-thumbnail-creator) | `@mad-scientist-skills/yt-thumbnail-creator` |

## Quality Notes

- Each package contains exactly one top-level `SKILL.md`.
- Package names use the `@mad-scientist-skills/` scope.
- Live secrets must stay in local `.env` files and out of git.
- Generated cache files such as `__pycache__` and `*.pyc` are ignored.

## License

Proprietary - (c) 2026 Mad Scientist LLC. All rights reserved.
