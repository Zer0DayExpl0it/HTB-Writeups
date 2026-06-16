---
title: "Checkpoint"
date: 2026-06-15
tags: [active-directory, kerberos, web]
difficulty: medium
---

# Checkpoint

> One-line summary of the box: what the final objective was and the headline technique used to get there.

**Machine:** Checkpoint · **Platform:** Hack The Box · **OS:** Windows · **Difficulty:** Medium

---

## Recon

Start with a quiet sweep and note what's exposed.

```bash
nmap -sC -sV -oA checkpoint 10.10.11.xx
```

Summarize what the scan told you — open ports, services, anything that hints at the path in.

## Foothold

Describe the first real access: the misconfiguration or vuln, the exact step, and the proof you landed.

```bash
# the command(s) that got you in
```

## Privilege Escalation

Explain how you went from your initial access to higher privilege. Keep it to the steps that
actually mattered — the chain, not every dead end.

```bash
# the key escalation step
```

## Root / Domain Admin

The final step and the loot. Show the evidence (a hash, a flag location, a shell as the target).

## Takeaways

- The one defensive lesson a blue-teamer should take from this box.
- The technique worth remembering for next time.

---

*Notes for you (delete before committing):*

- *Frontmatter is optional — the site will still title this "Checkpoint" from the folder name and
  set difficulty "medium" from the `Medium/` folder. But filling it in gives you real tags + date.*
- *`views:` is intentionally omitted. View counts can't be real on a static site without an
  analytics widget, so leaving it off shows a clean "—" instead of an invented number.*
- *To publish: replace `Medium/Checkpoint/README.md` in your repo with this file's contents,
  commit, and push. The portfolio picks it up on next load (no rebuild, no upload UI).*
