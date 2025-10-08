---
description: >-
  This page shows the standard workflow for handling a Modmail thread from start
  to finish. Only the essential commands and actions are included for quick
  reference.
---

# Quick Workflow

This page shows a typical workflow for staff handling a Modmail thread, from receiving a message to closing the thread. Focus on the key steps and main commands; everything else can be found in the command reference pages.

### 1. Receiving a New Thread

When a user messages Modmail, a new thread opens automatically. You can also open a thread manually:

* `?newthread <userID>`

Check the user’s previous threads with `?logs <userID>` if needed.

### 2. Replying

Respond to the user with the appropriate type of reply:

* Standard: `?reply <text>`
* Anonymous: `?anonreply <text>` (hides your name, only shows your role)
* Real reply: `?realreply <text>` (shows your name even if anonymous mode is active)

You can edit or delete your own replies using `?edit <number> <text>` or `?delete <number>`.

### 3. Organising the Thread

Keep threads clear and easy to follow:

* Add notes: `?note <text>`
* View notes: `?notes <userID>`
* Delete notes: `?delete_note <noteID>`
* Move threads to categories (if allowed): `?move <category>`
* Tag threads for follow-ups or special cases.

### 4. Managing status

* Close a thread: `?close`
* Close after a delay: `?close <time>` (cancel with `?close cancel`)
* Suspend temporarily: `?suspend` / `?unsuspend`
* Alert staff for new messages: `?alert` / `?alert cancel`

### 5. Optional Actions

* Block / unblock users: `?block <time>` / `?unblock`
* Get thread logs: `?loglink` (or `?loglink -s` for member-only messages)
* Use snippets for canned responses: see the Snippets page

***

Following this workflow ensures that threads are handled quickly, professionally, and consistently. Staff should always check notes and previous logs, respond using the correct reply type, and close threads only when the issue is fully resolved. Okay you can stop typing now no i said stop bro stop typing in the docs that was the end stop it-
