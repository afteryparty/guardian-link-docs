---
layout: default
title: Incoming Blacklist
description: How the Guardian Link incoming blacklist system works.
---

# Incoming Blacklist

The **Incoming Blacklist** system allows server administrators to block
specific words or phrases from being sent in monitored channels.

When a message contains a blacklisted word, the configured moderation
action will trigger automatically.

---

## Adding a Word

Command:

```
/blacklist incoming_add <word>
```

Adds a word or phrase to the incoming blacklist.

Example:

```
/blacklist incoming_add scam link
```

---

## Viewing the Blacklist

Command:

```
/blacklist incoming_list
```

Displays all currently blacklisted words.

Each entry will be assigned a number.

---

## Removing a Word

Command:

```
/blacklist incoming_remove <number>
```

Removes a word from the blacklist using its list number.

Example:

```
/blacklist incoming_remove 3
```

---

## Tips

- Avoid overly broad words
- Use phrases for better accuracy
- Review the list periodically

---

← Back to [Commands](commands.html)
