# eMoto UGC Story Director / 电摩 UGC 剧情编导

[简体中文](README.md) | **English**

Develop eMoto concepts into two-part stories, character references, first frames and connected camera prompts.

[Download complete project ZIP](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools/raw/main/packages/skill-emoto-ugc-story-director.zip) · [All projects](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools)

## Features

- Character expression and physical reactions
- Stable product appearance and dialogue speakers
- Timed shots and prompt-structure validation

## What is included

| Part | Location |
| --- | --- |
| eMoto AI Content Resources and Validation | [electric-moto-ai-workflow](apps/electric-moto-ai-workflow/README.en.md) |
| Skill instructions | [SKILL.md](skill/emoto-ugc-story-director/SKILL.md) |

## Download and extract

1. Open this repository, choose **Code → Download ZIP**, or use the complete-project download above.
2. Right-click the downloaded ZIP and choose **Extract All**. Open the extracted folder containing this README.
3. Keep the whole folder together. Start the program first using the next section, then install/use its skill.

Installation also writes PACKAGE-LOCATION.json beside the installed SKILL.md, mapping the bundled programs to their actual extracted directories. Keep the full extracted folder; rerun the installer after moving it. Existing Skill content is preserved by default while paths are refreshed.

## 1. Set up the program first

### eMoto AI Content Resources and Validation (`electric-moto-ai-workflow`)

Codex, with optional Python for prompt-file validation.

Open `apps/electric-moto-ai-workflow` first. Story-director and product-video resources with prompt-structure validation.

1. This is a content-resource toolkit. Use `安装Skill.cmd` at the complete bundle root first.
2. Give Codex your product references and verified specs, then invoke emoto-ugc-story-director.
3. Review the shots/prompts before choosing your own rendering platform.
4. For structure validation run `python skills/emoto-ugc-story-director/scripts/validate_prompt.py C:/path/prompt.md`.

[Full program / browser-extension guide](apps/electric-moto-ai-workflow/README.en.md)

No standalone desktop renderer or preconfigured generation account is included.

## 2. Install the Skill

1. At the extracted project's root, double-click `安装Skill.cmd` on Windows.
2. The installer copies `skill/emoto-ugc-story-director` to `%USERPROFILE%\.codex\skills\emoto-ugc-story-director`. Existing same-name skills are skipped; check the displayed result.
3. Reopen Codex and start a new chat. Use the exact skill name shown below.
4. If scripts cannot run under your organization policy, open install.ps1 for review or copy the skill directory manually to the same destination.

## 3. First task

| Prepare | Details |
| --- | --- |
| Input | Product reference images, market, story direction and duration. |
| Output | Story, character-view prompts, first frames, video prompts and post copy. |

```text
Use emoto-ugc-story-director to plan two 10-second garage-surprise scenes from my eMoto reference. Deliver shots and a review version first.
```


## Limits and troubleshooting

electric-moto-ai-workflow is a collection of scripts and skills, not a one-click desktop renderer.

| Problem | Next step |
| --- | --- |
| Skill not visible | Check the installer output and destination SKILL.md, reopen Codex and start a new chat. |
| Program fails to start | Open its directory in PowerShell and run the documented command so the error remains visible; check that program's README. |
| Browser panel missing | Select the exact folder containing manifest.json, check supported websites and refresh the website tab. |
| External service unavailable | Supply your own authorization/settings and verify access. Keep local output rather than claiming a sync/send succeeded. |

## Privacy and status

This is a source/skill distribution. No real accounts, OAuth tokens, customer/KOL lists, contracts, orders, mailbox exports or business media are included. You configure your own services. Documentation and package paths were checked; live orders, sends and publications were not executed as part of documentation validation.
