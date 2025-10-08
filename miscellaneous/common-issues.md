---
description: >-
  Troubleshooting common mistakes staff make (accidental replies, wrong channel,
  etc.).
---

# Common Issues

This page covers common mistakes or issues staff may encounter while using Modmail on Lane Scrims. Following these troubleshooting steps will help prevent errors and ensure smooth handling of member threads.

### Accidentality Sending the Wrong Reply

* If you send a reply in a thread by mistake, you can delete it using:\
  `?delete <number>`\
  `<number>` is the message number shown in front of your reply.
* To correct your reply instead of deleting it, use:\
  `?edit <number> <new text>`\
  This ensures the user sees the corrected message without confusion.

### Posting in the Wrong Thread like the actual NPC you are

* Always double-check the thread’s channel name before sending messages.
* If a message is sent in the wrong thread, use `?delete <number>` to remove it.
* Consider sending the correct reply in the intended thread using `?reply <text>` or `?r <text>`.

### Misusing Anonymous vs Real/Normal Replies

* To maintain anonymity while sending messages, use `?anonreply <text>` or `?ar <text>`.
* If you accidentally sent a message anonymously but intended to include your name, use `?realreply <text>` or `?rr <text>` instead.
* Always verify whether the thread should display your staff role or your actual name before sending.

### Accidentality Closing Threads

* If a thread is closed prematurely, you can unsuspend it with:\
  `?unsuspend`
* If the thread was scheduled to close using `?close <time>`, cancel the scheduled close using:\
  `?close cancel`
* For silent closures that you didn’t intend, reopening the thread and notifying the member may be necessary.

### Accidentally Deleting a Thread

You're cooked

### Blocking or Unblocking Mistakes

* Accidentally blocking a member can be reversed with:\
  `?unblock <userID>`
* If you block for the wrong duration, cancel or adjust it as needed using:\
  `?block <userID> <time>`
* Check the current block status of a member with:\
  `?is_blocked <userID>`

### Missing Notes or Logs

* If you cannot locate past notes, run:\
  `?notes <userID>`
* If a note was accidentally deleted, it cannot be recovered, so always double-check before using `?delete_note <noteID>`.
* To review past conversations for context, use:\
  `?logs <userID>`
* For thread-specific log links, use:\
  `?loglink`, `?loglink -s`, or `?loglink -v` depending on the details required.

### Common Workflow Mistakes

* Avoid sending replies to the wrong DM channel. Use `?dm_channel_id` to confirm the channel ID before messaging.
* For referencing a specific user message, use:\
  `?message <number>`
* Always check your displayed staff role using `?role` to ensure clarity and professionalism in threads.

***

By following these guidelines, staff can quickly resolve mistakes, maintain thread clarity, and ensure that members have a smooth, professional experience in Lane Scrims Modmail.
