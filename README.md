# lib-command

`command` — user-space command registration and invocation algebra: a
`Command` is an operation executed by the active command handler.

## Layout

```text
handl-packages/command/   the .hnl package
scripts/hnl-gate.sh       the gate
workflows/gate.yaml                     bupha entry (handl-gates)
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
