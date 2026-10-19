# Teach From Zero

**For the moment when “explain it simply” still leaves you confused.**

A reusable teaching skill that guides AI to start with something you can picture, explain why each new idea is needed, and build toward the real mechanism—then code or notation when useful.

Created by **Romit Sharma** from the way he wants to learn.

[Download the skill ZIP](downloads/teach-from-zero-v1.0.0.zip) · [Read or copy the instructions](skills/teach-from-zero/SKILL.md) · [Example learning prompts](docs/EXAMPLES.md)

## Try it

1. Download the skill ZIP above.
2. Upload it into an AI chat that can open ZIP files.
3. Ask the AI to read `teach-from-zero/SKILL.md` inside it and follow those instructions:

> Use this skill to teach me [topic] from scratch. I’m completely blank—I don’t know anything about it.

If the AI cannot read ZIPs, extract the ZIP and upload `SKILL.md` directly, or open that file and paste its full contents into the chat before your question. A Markdown file is a plain text file; you can open it in a text editor.

Tell it what you already know, too:

> Use this skill to teach me why bread dough rises. I know we add yeast, but I don’t know what yeast is doing or how the dough holds the bubbles. Start there and explain every new idea you need.

Reading an uploaded file guides that conversation; it does not automatically install a permanent skill or carry into every new chat. For another chat, supply the instructions again or use your AI tool’s supported reusable-instructions feature.

## Why I made it

I would ask AI to explain something from scratch. Then I would explain how little I knew, how slowly I wanted to go, and how deeply I wanted to understand it.

The answer would still contain things I didn’t understand. I would ask about those, and the next explanation would create more questions. I kept having to explain how I wanted to be taught.

So I gave AI a detailed example of how I would teach a topic myself, and used it to build this skill.

The biggest difference in my experience was that it began covering the questions I was about to ask. When it mentioned something unfamiliar, it explained enough to keep me following, or clearly told me which detail we would return to later. I could keep a picture of what was happening in my head.

It isn’t perfect. But it has made learning with AI much better for me, and I’m sharing it for people who have the same frustration.

## What changes in the explanation?

Suppose you want to understand why bread dough rises. Start with a bowl of dough on the counter. You mixed the ingredients and left it alone. Later, it looks bigger.

What happened while it was sitting there? What is yeast doing? Where do the bubbles come from? Why do they stay inside the dough?

Those questions give you a reason to learn the next idea. The skill tells the AI to keep that same situation in view as it explains the mechanism and introduces the relevant names.

It also tells the AI to notice the connections it might otherwise skip:

- What exactly is this new thing, and where does it exist?
- Why do we need it at this point?
- Who or what causes the next action?
- What changed, and what is still missing?
- Is this an analogy, or how the real system works?

For programming, code comes after its purpose is understood, with small examples traced through execution. For maths, each relevant operation and sign change gets a reason.

The aim is understanding you can explain in your own words.

## Who it is for

People meeting an unfamiliar subject for the first time. People who know the terminology but still cannot picture what happens. People who keep asking “why?” and “how?” because the first explanation leaves gaps.

You can use it across subjects. You can also say what you already know so the explanation does not repeat foundations you have mastered. Explicit requests for short answers or revision should still be respected.

## What this download contains

The reusable skill lives in `skills/teach-from-zero/`:

- `SKILL.md`: the complete teaching instructions and worked examples.
- `agents/openai.yaml`: display and invocation metadata for tools that support it.
- `assets/icon.svg`: the included skill icon.

The downloadable ZIP contains that skill folder plus the license. For a chat upload, the important file is `SKILL.md`. For a tool that supports native skills, follow that tool’s current installation instructions and use the `teach-from-zero` folder; installation paths and supported metadata vary.

No API key, application server, or paid service is included or required by the skill itself. Your chosen AI service has its own requirements.

## What to expect

This is a set of teaching instructions, not a separate AI model or a source of verified subject knowledge. Results depend on the model, topic, and context. Clear explanations can still contain errors. The skill asks for accurate mechanisms, bounded analogies, and verification of uncertain or changing facts.

My positive experience is personal feedback, not a controlled benchmark or a promise of identical results across every model. There are no claims of measured learning gains here.

## Help improve it

Try it on a topic you genuinely find difficult. Tell us where the explanation first lost you, what it assumed you knew, and what helped. See [contributing](CONTRIBUTING.md) for a useful feedback format.

If you share a comparison, keep the topic, model, starting context, and prompt consistent, with the skill as the main change. Label edited excerpts and avoid presenting an invented example as an actual AI response.

## License

[MIT](LICENSE). You can use, adapt, and share it under the terms of the license.
