---
description: >-
  All reply types in one place (normal, anonymous, custom/template replies, and
  when to use each).
---

# Replying

This page explains all ways staff can reply to users in Modmail threads, including normal replies, anonymous replies, real replies, and the use of canned/template messages. Understanding when to use each type ensures professional and consistent communication with users.

### Standard Replies

The most common way to respond is with a **standard reply** using:

```
?reply <text> (or ?r <text>)
```

* Sends a message directly to the user.
* Your staff name and role are displayed by default unless `forceAnon` is enabled.
* Example: `?r How can I assist you today?`

### Anonymous Replies

Anonymous replies hide your staff name, only showing your staff role. Use this when you want to respond without revealing who you are:

```
?anonreply <text> (or ?ar <text>)
```

* Useful for sensitive topics or when multiple staff handle the same thread.
* Example: `?ar Please follow the server rules carefully.`
* Note: Anonymous replies will respect the `forceAnon` setting if enabled.

### Real Replies

A **real reply** always shows your staff name, even if anonymous mode is enabled. Use this when personal accountability is important:

```
?realreply <text> (or ?rr <text>)
```

* Recommended for official communications or when following up on previous conversations.
* Example: `?rr I’ve reviewed your report personally and here’s the resolution.`

### Editing or Deleting Replies

You can edit or delete your previous replies if you made a mistake or need to clarify something:

```
?edit <number> <new text>
?delete <number>
```

* `<number>` is the message number shown next to your reply in the thread.
* Use these sparingly to maintain a clear log of interactions.

### Using Notes and Templates (if any at all, depends if management feels lazy today)

Staff can also use **notes and snippets** to streamline replies:

* **Notes:**
  * `?note <text>` – add a staff-only note for context.
  * `?notes <userID>` – view all notes for a user.
  * `?delete_note <noteID>` – remove a note.
* **Snippets (canned messages):**
  * Refer to the Snippets page

### When to Use Each Reply Type

* **`?reply` / standard:** Use for normal, everyday communication where your name can appear.
* **`?anonreply` / anonymous:** Use when multiple staff may interact with the user or for sensitive topics.
* **`?realreply`:** Use when personal accountability is required, or for escalation responses.
* **Snippets:** Use for efficiency on repeated queries or standardised responses.

***

Following these guidelines ensures that replies are professional, consistent, and appropriately personalised. Staff should always choose the reply type based on the context of the conversation and the sensitivity of the topic.
