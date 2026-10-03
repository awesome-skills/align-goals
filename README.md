# Align Goals

Briefly restate the user's desired outcome and current problem so misunderstandings are easy to spot.

## Install

```bash
npx skills@latest add awesome-skills/align-goals -g -y
```

If you use the unified Agent Skills Manager, import the `skills/align-goals` directory through its local installation workflow.

## Use

```text
Use $align-goals to restate my goal and the problem I want to solve before we plan.
```

You can also explicitly invoke `@align-goals` in clients that support that syntax. Invocation syntax depends on your agent. Chinese trigger phrases are retained in the skill.

## Behavior

Distinguishes outcomes, obstacles, and proposed approaches; preserves supported constraints; asks one question only when ambiguity matters. Follows the user's language. An alignment-only request does not authorize execution, and one invocation does not create a permanent response preference.

Read the complete [skill instructions](skills/align-goals/SKILL.md).

## License

[MIT](LICENSE) · Part of [Awesome Skills](https://github.com/awesome-skills).
