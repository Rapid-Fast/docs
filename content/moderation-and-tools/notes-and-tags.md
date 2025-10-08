---
description: >-
  How to leave staff-only notes inside a thread and categorize threads with
  tags.
---

# Notes & Tags

Staff can leave internal notes and categorise threads using tags to help manage Modmail interactions efficiently. Notes are visible only to staff, while tags help organise threads by type, urgency, or topic. This ensures that everyone handling a thread has the context they need.

### Adding Notes

To add a staff-only note for the user in the current thread, use:

```
?note <text>
```

* Notes are linked to the user, not just the thread.
* Include important context, reminders, or follow-up actions.
* Example: `?note User reported repeated rule violations.`

### Viewing Notes

You can view all notes attached to a user using:

```
?notes <userID>
```

* Replace `<userID>` with the Discord ID of the member.
* This displays a list of notes with their unique note IDs for reference.
* Example: `?notes 106391128718245888`

### Deleting Notes

To remove a note that is no longer relevant or was added by mistake:

```
?delete_note <noteID>
```

* `<noteID>` is shown when running `?notes`.
* Example: `?delete_note 42`

### Using Tags to Categorise Threads

Tags are a way to categorise threads for easy tracking and prioritisation. For example, you might use tags like `escalation`, `follow-up`, `ban request`, or `general inquiry`.

* Tags help staff quickly see the purpose or status of a thread.
* Some servers implement tags as thread names or channel categories, while others may use internal bot features depending on configuration.
* Use consistent naming for tags to avoid confusion.

**Tips for Effective Notes and Tags:**

* Always add a note when an important decision or action is made in the thread.
* Keep tags updated to reflect the current status or type of thread.
* Combine notes and tags for maximum clarity — notes give context, tags give quick reference.
* Review notes before replying to maintain continuity in staff communication.

***

By using notes and tags consistently, staff can manage threads more efficiently, maintain clear communication, and ensure users receive timely and appropriate responses.
