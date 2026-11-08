# Automatic Master Prompt Generator

> Turn simple ideas and rough instructions into detailed, structured,
> copy-ready master prompts.

**Automatic Master Prompt Generator** is a reusable prompt-engineering
skill that transforms plain-language requests into clear, actionable
prompts for AI tools. It focuses on understanding the user's intent,
choosing the right prompt structure, adding relevant constraints, and
checking the final prompt before delivery.

## Features

-   **Intent detection** --- identifies the goal, task type, audience,
    context, and desired output.
-   **Smart clarification** --- asks only when an essential detail is
    missing; otherwise uses clearly marked placeholders or sensible
    assumptions.
-   **Task-specific prompt structures** --- adapts prompts for writing,
    image generation, video, animation, coding, research, branding, and
    marketing.
-   **Workflow design** --- breaks complex tasks into logical phases and
    deliverables.
-   **Tool-aware instructions** --- tailors prompts to the named AI
    platform without inventing unsupported features.
-   **Quality checks** --- checks clarity, completeness, consistency,
    constraints, and copy-readiness.
-   **Reusable templates** --- supports placeholders such as `[TOPIC]`,
    `[PLATFORM]`, `[STYLE]`, and `[OUTPUT FORMAT]`.
-   **Prompt improvement** --- preserves useful details while removing
    ambiguity, repetition, and contradictions.

## How it works

1.  **Understand** the user's idea and intended result.
2.  **Extract** the relevant context, inputs, audience, style,
    constraints, and output format.
3.  **Clarify** only if a missing detail would materially change the
    result.
4.  **Architect** the prompt using a structure suited to the task.
5.  **Optimize** the instructions, workflow, and success criteria.
6.  **Validate** the prompt for contradictions, unsupported assumptions,
    and missing requirements.
7.  **Deliver** a complete, self-contained prompt ready to copy and use.

## Installation

Add the skill to the agent or environment that supports your skills
workflow. For example, with a compatible skills CLI:

``` bash
npx skills add <REPOSITORY_URL> --skill automatic-master-prompt-generator --agent <AGENT_NAME>
```

Replace `<REPOSITORY_URL>` and `<AGENT_NAME>` with the appropriate
values for your setup.

You can also place `skill.md` in the skill directory recognized by your
AI agent.

## Usage examples

Try requests such as:

``` text
Create a detailed master prompt for a cinematic product video.
```

``` text
Turn this rough idea into a professional image-generation prompt.
```

``` text
Improve my existing prompt for a scene-by-scene animated short.
```

``` text
Build a reusable prompt template for competitor research.
```

``` text
Create a master prompt for a brand identity and logo design workflow.
```

## Default output

Unless the user requests a different format, the skill returns:

1.  A concise prompt title.
2.  The complete optimized master prompt in a copy-ready code block.
3.  Brief customization notes for placeholders or assumptions, when
    needed.
4.  One useful next refinement suggestion.

If the user asks for only the prompt, it returns only the prompt.

## Design principles

-   Preserve the user's original intent.
-   Add useful detail, not filler.
-   Never invent facts, references, or technical capabilities.
-   Keep prompts self-contained and easy to reuse.
-   Separate required instructions from optional suggestions.
-   Use clear success criteria and explicit output formats.
-   Respect safety, privacy, consent, intellectual property, and
    platform rules.

## File structure

``` text
automatic-master-prompt-generator/
├── README.md
└── skill.md
```

## License

Add the license that matches how you intend to distribute this skill. No
license is specified by default.
