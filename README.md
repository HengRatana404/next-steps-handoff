# next-steps-handoff

After each turn, suggests up to three next prompts above the input box, with a **Hand off** button at the top right of the band.

```
next:                                   [ Hand off ]
  1: run the tests you just wrote
  2: do the same for the settings page
  3: /code-review high
  0: dismiss
```

Press `1`, `2` or `3` from an empty prompt box (or click one) and that prompt is written into the box as a draft. Edit it, then press Enter yourself. `0` dismisses. **Hand off** fills the box with `/handoff continue this work in a new session`; it needs a `handoff` skill installed, and you press Enter yourself. The plugin never submits a prompt on its own.

## Install

At the prompt of a terminal session:

```
/plugin install next-steps-handoff --marketplace HengRatana404/next-steps-handoff
```

From a shell:

```
claude plugin install next-steps-handoff --marketplace HengRatana404/next-steps-handoff
```

In the desktop app, where `/plugin` does not run: click + next to the prompt box, then Plugins, Add marketplace with `HengRatana404/next-steps-handoff`, then Add plugin.

If you also have the Next steps plugin enabled, turn it off so you don't get two bands.

## License

MIT, see `LICENSE`.
