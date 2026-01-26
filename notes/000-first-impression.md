# First impressions (CEL policies) — WIP

## What I tried
- Read through Kyverno’s CEL policy docs and skimmed a few existing examples.
- Goal: understand the minimum “hello world” flow (policy + a tiny resource + expected result), and how people are supposed to test it.

## Friction points (so far)
- It’s not obvious (to a new user) what the smallest end-to-end example should look like.
- I’m still mapping the mental model: where variables come from, and how substitution is expected to work in CEL policies.
- When testing fails, I want a short “common errors → likely cause → fix” checklist.

## Next
I’m going to add the first runnable example under `examples/` and capture the exact commands + expected output.
