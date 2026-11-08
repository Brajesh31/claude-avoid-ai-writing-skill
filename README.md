# claude-avoid-ai-writing-skill

A Claude Code skill for identifying formulaic AI-writing patterns and improving clarity, specificity, and natural expression.

## Overview

This skill reviews writing for generic phrasing, repetitive structure, inflated claims, unnecessary transitions, and other patterns that can make text feel formulaic. It supports both detection-only review and rewriting.

The skill treats these patterns as editorial signals, not proof of who wrote a piece. Human writers can use the same patterns, and AI detectors can produce false positives.

## Main Capabilities

- Detect common formulaic writing patterns.
- Identify vague or inflated language.
- Reduce repetitive transitions and sentence structures.
- Improve specificity and concrete detail.
- Preserve the writer's intended meaning.
- Adapt tone to casual, professional, technical, warm, or direct styles.
- Rewrite content in place when requested.
- Iterate until the text is clear without becoming unnatural.

## Available Modes

| Mode | Purpose |
|---|---|
| `rewrite` | Identify patterns and provide an improved version |
| `detect` | Report patterns without changing the text |
| `iterate` | Review and refine through additional passes |

The default mode and exact invocation behavior are defined in `SKILL.md`.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-avoid-ai-writing-skill.git ~/.claude/skills/avoid-ai-writing
```

## Usage

Invoke the skill when editing or auditing prose:

```text
/avoid-ai-writing
```

Provide the text, intended audience, genre, and preferred voice. State whether you want detection only or a rewrite.

## Editing Workflow

1. Identify the purpose and audience of the text.
2. Review sentence structure, transitions, and repeated phrasing.
3. Flag generic or unsupported claims.
4. Replace vague language with concrete meaning.
5. Preserve the author's intent and factual details.
6. Keep technical terminology where precision requires it.
7. Match the requested voice and level of formality.
8. Re-read the revised version for natural flow.
9. Avoid over-editing distinctive or intentional stylistic choices.

## Writing Quality Checklist

- The opening gets to the point.
- Claims are specific and supported.
- Sentences vary naturally.
- Transitions are not repetitive.
- Adjectives and intensifiers add meaning.
- Examples are concrete.
- The conclusion does not merely repeat the introduction.
- The writer's voice remains recognizable.
- Technical meaning is preserved.

## Responsible Use

Do not use AI-writing pattern detection as a standalone judgment of authorship, academic integrity, or professional credibility. A flagged pattern is not proof that a person used AI. Consider context, genre, language background, and other evidence.

## Repository Contents

- `SKILL.md`: Main detection and rewriting instructions.
- `README.md`: Modes, workflow, and responsible-use guidance.

## Practical Principle

The goal is better writing, not merely lower AI-detection scores. Improve clarity and substance while preserving the writer's actual voice.
