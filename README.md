# Refi – the Refim method

The public method Refi works with: how to run a get-to-know, a first look, a
retro, a co-design and a check-in, and how to keep the record.

The Refim app downloads the latest release and hands it to the user's AI CLI
(Claude Code first, Codex next). Method and app are updated independently.

```
AGENT.md              who Refi is, how it works, how it keeps the record
skills/<session>/     one method per session: get-to-know, first-look, retro,
                      co-design, check-in
templates/            the shape of every record document
prompts/system.md     the system prompt the app sends on every turn
                      ({method_dir} is filled in by the app)
conventions/chat.md   how conversations in the Refim app reach Refi
VERSION               version of this method release
```

Written in English on purpose; Refi speaks and writes the record in the user's
language. Origin: `refim-workspace/refim-agent` and `data/templates`, October 2026.
