# Verify tmux for prompt_agent: Prompt-Conditioned Session Adapter

A verification page for prompt-conditioned terminal sessions mediated through tmux.

## Verification Focus

- Agent: prompt_agent
- Track: Adapter Verification
- Shared image: `docs/assets/hero.png`
- Image position: fixed in the right-side hero media container

## Trace Notes

- Prompt context is stored alongside pane state.
- Instruction changes are marked before command execution.
- Session memory is compared with current terminal output.

## Review Lens

- Prompt-to-pane binding
- Instruction drift detection
- Session memory consistency
