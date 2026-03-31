# Claude Code Source

<img src="https://github.com/anthropics/claude-code/blob/main/demo.gif?raw=1" />

> **⚠️ WARNING**  
> Extracted from `cli.js.map` in the public npm package `@anthropic-ai/claude-code@2.1.88`.  
> Not original source. Not modified. Not official. Research use only. © Anthropic PBC.

---

## One line

This repo = `npm pack @anthropic-ai/claude-code@2.1.88` + `cli.js.map` → reconstructed TypeScript.

---

## What you get

```
claude-code-source/2.1.88/
├── cli.js              # 13 MB compiled bundle
├── cli.js.map          # 59 MB source map (the key)
├── package.json
├── src-extracted/      # ~1902 .ts/.tsx files, original paths preserved
└── vendor/             # bundled deps
```

Open `src-extracted/`. Read the code. That is the point.

---


## Extract it yourself (exact method)

```bash
# 1. Create a test directory
mkdir claude && cd claude

# 2. Download the extraction script (public gist by @sorrycc)
curl -O https://gist.githubusercontent.com/sorrycc/d77bcc8c2bfd0ac04d8d6ad98c413905/raw/extract-claude-code.mjs

# 3. Run the script to extract v2.1.88 
bun extract-claude-code.mjs 2.1.88
# Or with Node.js if Bun is not installed:
# node --experimental-fetch --experimental-import-meta-resolve extract-claude-code.mjs 2.1.88

# 4. Enter the extracted output directory
cd claude-code-source

# 5. See what is inside
ls -la

# 6. Enter the version folder
cd 2.1.88

# 7. View the full file structure
ls -la

# 8. Enter the extracted source folder
cd src-extracted

# 9. See what is inside
ls -la
```

---

## Notes

- This is not a fork. Not a rebuild. It is a direct extraction via source maps.
- The code is intact. If it does not run in your env, that is an env issue.
- I do not provide support. I published what was publicly extractable.
- Found something? Explore. Share. Or don't. Your call.

---

## Legal

Original copyright: Anthropic PBC.  
This archive: publicly extractable content, shared for technical research and education.  
If you represent Anthropic and want removal: open an issue. I will respond.
