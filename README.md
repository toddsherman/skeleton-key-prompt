# Skeleton Key Prompt

A prompt that helps you build better prompts.

Paste it into any AI model and describe what you're trying to get done. It
interviews you — a few numbered questions at a time, adapting as it goes — and
then writes a finished prompt you can copy and paste anywhere.

`prompt.md` is the whole thing. Published at
[todd.sh/skeletonKeyPrompt](https://www.todd.sh/skeletonKeyPrompt).

## Why it works

Most weak prompts fail on the parts you didn't think to specify. This one
covers them for you — the role the model should take, who the output is for,
the constraints that matter, whether you want a one-off or a reusable template,
and how it should behave when something is missing or ambiguous. It asks about
what's relevant to your case and proposes defaults for the rest, so a vague
answer moves the process forward instead of stalling it.

It also restates your goal in one sentence before asking anything, so a misread
surfaces immediately rather than ten questions later.

## Notes

Output is deliberately plain text — no markdown symbols, no characters that
change when pasted between tools. Reusable templates come back with the
fill-in spots marked, e.g. `[PASTE TEXT HERE]`.

You can stop it at any point and have it write the prompt from whatever it has
so far.
