---
description: If someone is a bit naughty
---

# Blocking and Restrictions

On Lane Scrims, staff can block users from using Modmail or set temporary restrictions. This is useful for preventing spam, repeated rule-breaking messages, or any situation where a user should temporarily or permanently lose access to Modmail threads.

### Blocking a User

To block a user from sending Modmail messages:\
`?block <userID>`

**Example:**\
`?block 106391128718245888`

Once blocked, the user cannot open new threads or send messages in existing threads until unblocked.

### Temporary Blocks

You can block a user for a specific duration using:\
`?block <userID> <time>`

**Example:**\
`?block 106391128718245888 7d`

The `<time>` parameter accepts standard durations like `m` for minutes, `h` for hours, `d` for days, and `w` for weeks. After the timer expires, the user will automatically regain access to Modmail.

### Unblocking a User

To remove a block and allow a user to use Modmail again:\
`?unblock <userID>`

**Example:**\
`?unblock 106391128718245888`

### Checking Block Status

To see if a user is currently blocked:\
`?is_blocked <userID>`

**Example:**\
`?is_blocked 106391128718245888`

### Best Practices

* Only block users when necessary, such as repeated spam or abusive messages.
* Use temporary blocks where possible to allow users to correct behaviour.
* Keep a note using `?note <text>` whenever you block someone, so other staff are aware of the context.
* Review block statuses regularly to ensure no user is unnecessarily restricted.

***

Proper use of blocking and restrictions ensures that Lane Scrims Modmail remains organised, safe, and manageable for staff, while providing fair opportunities for users to communicate when appropriate.
