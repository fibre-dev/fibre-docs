# fibre docs

The documentation for [fibre](https://fibre.dev): sandboxes for agents and the code they write. Built with
[Mintlify](https://mintlify.com).

## preview locally

```bash
npx mint dev
```

## the examples are tested

Code blocks carry a few extra words that a test runner reads: `run` (run this block), `capture=NAME=.field` (keep a
field of its JSON output for the blocks after it), `norun reason="…"` (not run, and why), and `expected` (the output
the block before must produce; `"…"` matches any value). Every example runs against the real API before it is
published.

## license

MIT
