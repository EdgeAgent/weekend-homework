# How to build with Claude Code — the house rules

These five projects teach more than tools. They teach a way of working. Follow these rules on every build:

1. **Spec before code.** Write the one-page spec first (each guide has one). If you can't say what "done" looks like, Claude can't build it.
2. **Small steps, verified.** One feature per prompt. Run it. Look at it. Then the next. Never ask for the whole app in one prompt.
3. **The CLAUDE.md is the contract.** Every project folder ships one. It holds the stack, the rules and the definition of done, so every session starts on the same page.
4. **Commit like you mean it.** A git commit after every working step. Your history is your undo button and your portfolio.
5. **Local first for personal data.** Documents, journals and libraries about YOUR life stay on YOUR machine. Local models (Ollama) or local files — cloud only when the data is public or throwaway.
6. **Ship the ugly version.** A working dashboard with no styling beats a beautiful mock-up. Polish is the last step, not the first.
7. **End with the demo.** Record a 60-second walkthrough when you finish. A project nobody can see doesn't exist.

## The prompt pattern that works

Every step in the guides uses this shape:

> "Read CLAUDE.md and SPEC.md. Build [one specific thing]. Use [stack/constraint]. When it runs, show me [the verification]. Do not start the next step."

Specific beats clever. If the output is wrong, correct the spec or the CLAUDE.md — not just the chat — so the fix survives the session.
