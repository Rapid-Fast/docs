---
description: >-
  How to close, reopen, archive, or mark threads, plus best practices for
  keeping threads organised.
---

# Managing Threads

Managing Modmail threads effectively on Lane Scrims ensures that support staff can provide timely responses while keeping the inbox organised. Proper thread management includes closing, reopening, archiving, marking, and maintaining clear internal notes.

### Closing Threads

When a thread’s issue has been resolved, close it to indicate that no further replies are required.

* Close immediately with `?close`.
* Schedule a delayed closure using `?close <time>`. Example:\
  `?close 15m`
* Close silently without notifying the user using `?close -s`.
* Cancel a scheduled close with `?close cancel`.

### Reopening Threads

If a user responds after a thread is closed (or you made an oopsies and closed it automatically like blake once did), the thread can be reopened automatically. Staff can continue replying as usual, or add a note using `?note` to track reopening.

### Suspending Threads

For threads that need to be temporarily paused without closing completely:

* Suspend the thread using `?suspend`.
* Suspended threads will not receive messages until unsuspended.
* Unsuspend a thread with `?unsuspend`.

### Archiving and Logs

To maintain records or report issues:

* Get a thread log with `?loglink`.
* Show only messages to/from the user with `?loglink -s`.
* Include additional internal metadata for Trust & Safety reports with `?loglink -v`.
* Use `?logs <userID>` outside a thread to review past interactions.

### Marking Threads (Not to be confused with marking for death, we won't add this anyways)

Threads can be marked or categorised for internal tracking:

* Move threads to specific categories with `?move <category>`.
* Add staff-only notes using `?note <text>` to indicate special handling or follow-ups.
* Tag threads consistently to help staff identify high-priority or complex cases.

### Best Practices for Thread Organisation

* Close threads promptly once issues are resolved.
* Suspend threads only when necessary and ensure they are unsuspended promptly.
* Use categories and notes to maintain a clear system of ownership and context.
* Regularly review logs to spot recurring issues or important patterns.
* Communicate with other staff when transferring threads to prevent overlaps or missed responses.

***

Following these practices keeps Lane Scrims’ Modmail inbox structured and ensures that all users receive efficient, accountable support.
