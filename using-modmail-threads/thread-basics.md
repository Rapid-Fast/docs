---
description: >-
  How threads are created, what they look like, and how staff interact with
  them.
---

# Thread Basics

Modmail threads are private channels created whenever a user contacts the bot. They allow staff to communicate with the user in a structured, organised way without cluttering public channels. This page explains how threads are created, what information is available in a thread, and how staff can interact with them effectively.

### How Threads Are Created

Threads are usually created automatically when a user sends a message to the Modmail bot or interacts with any panels the bot may have sent in a channel. Staff can also open a thread manually from anywhere on the inbox server using:

```
?newthread <userID>

Example:
?newthread 106391128718245888
```

After a thread is created, it appears in a designated staff channel. Each thread has a unique name (usually the member’s username or ID) and shows all messages exchanged with that member. Threads also display metadata like the user’s ID, DM channel ID, and any tags or notes attached.

### Thread Layout

A typical thread contains:

* **User Messages:** The content sent by the member.
* **Staff Replies:** Messages sent by staff using `?reply`, `?anonreply`, or `?realreply`. Each reply shows the message number for easy reference.
* **Notes:** Internal staff-only notes added with `?note`.
* **Tags (optional):** Labels for organisation, such as `escalation` or `follow-up`.

Staff can view thread logs and history using:

* `?logs` (inside a thread or with a specific user ID)
* `?loglink` / `?loglink -s` / `?loglink -v`

This provides full visibility into prior interactions, ensuring consistent responses.

### Interacting with Threads

Inside a thread, staff can perform several actions to manage communication and organisation:

* **Replying:**
  * `?reply <text>` – standard response
  * `?anonreply <text>` – hides staff name, shows role only
  * `?realreply <text>` – forces your name to appear
* **Editing / Deleting Replies:**
  * `?edit <number> <new text>`
  * `?delete <number>`
* **Closing / Suspending Threads:**
  * `?close` – ends the thread
  * `?close <time>` – schedules a delayed close
  * `?suspend` / `?unsuspend` – temporarily freeze or reactivate the thread
* **Thread Organisation:**
  * `?move <category>` – relocate the thread (requires `allowMove`)
  * `?note <text>` – add staff-only notes
  * `?role <role name>` – set your display role for the thread

Optional alerts can be set with `?alert` to notify you when a new message arrives, or cancelled with `?alert cancel`.

### Key Tips for Staff

* Always check `?logs` or `?notes` before replying to understand the user’s history.
* Use anonymous replies only when necessary.
* Keep notes and tags up to date to maintain clear organisation.
* Close threads only when the user’s issue is resolved.

***

Following these guidelines ensures that threads remain organised, professional, and efficient. Staff should treat each thread as a private conversation with the user while using notes, tags, and logs to maintain internal clarity.
