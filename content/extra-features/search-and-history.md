---
description: How to look up past threads with a user or search for keywords.
---

# Search & History

On Lane Scrims, staff can look up past Modmail threads with a user or search for specific keywords in threads. This helps track user activity, review previous cases, and maintain consistent moderation.

### Viewing Past Logs With a User

To see all previous threads with a specific user, use:\
`?logs <userID>`

**Example:**\
`?logs 106391128718245888`\
This command will display a list of all past Modmail interactions with that user, including timestamps and basic summaries. Use this to quickly review prior conversations before responding or escalating.

### Searching Within a Thread

To search for keywords in an open thread, use:\
`?loglink -s` or `?loglink -v`

* `?loglink -s` shows messages only to/from the user, ignoring staff chatter.
* `?loglink -v` shows additional details including message IDs and channel IDs, useful for referencing or reporting specific messages.

Once the log link is open, you can use your browser’s search (Ctrl+F / Cmd+F) to find keywords or phrases within the thread. This makes it easy to locate specific conversations, rule violations, or follow-ups.

### Searching Across the Inbox

To view previous threads with a user from anywhere on the server (even outside a thread), use:\
`?logs <userID>`

This command can also help when investigating repeated behaviour patterns or checking prior escalations. Always review the notes (`?notes <userID>`) alongside logs for full context.

### Best Practices

* Always check `?logs` before responding to ensure you understand the user’s history.
* Combine log review with `?notes <userID>` for internal context and prior staff comments.
* Use `?loglink -s` when you only need the user-facing conversation, and `?loglink -v` when you need full internal detail.
* Document any important findings as a `?note` to maintain a consistent record.

***

Following these steps ensures that all staff on Lane Scrims have access to complete context, maintain consistency in moderation, and can respond to users efficiently.
