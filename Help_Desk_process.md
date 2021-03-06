# Process for Help Desk Requests from External Users

> **SUMMARY**: If a Help Desk issue is assigned to you, then within two business days you are expected to add a comment to the issue that answers the questions, "Is this something that I can address? If so, when?"

When a new issue is received from an external user, it automatically creates a JIRA ticket.
Help Desk managers send a generic response (within one day) to the user notifying them that we will get them an answer soon.
Unless the Help Desk managers can answer the question themselves, they assign the issue to the person they think is most likely to be able to address it.

Within two business days, the assignee needs to add a comment to the ticket to either:
- Acknowledge that they will handle the issue (even if not immediately), or
- Indicate that they are not the right person to do so. In this case, they should reassign to the right person if they know who that is, or request that it be reassigned.

If you are assigned a ticket and you are the correct assignee, then you should provide a short answer that the Help Desk managers can send to the user. Please alert the Help Desk manager, Meghan, by referring to her in your comment (as @drakemn) so that she knows to forward your response to the user.

Your answer to the user can be something like, "We know about this issue and a fix will be coming in [approximate time]," or "Can you send more information about what you were doing when the problem occurred, your environment, etc. so that we can reproduce and diagnose the problem?" (Note that http://kbase.us/report-an-issue/ has guidelines on how to report an issue effectively.)

When you respond to a ticket that you are assigned, it's important to add some indication of how hard you think the issue is likely to be to fix, and when you will have time to work on it. Please also let us know if this is blocked by another issue--another task must be completed (by you or by someone else) before this can be fixed. (If possible, include link(s) to other JIRA tickets.)

It's ok if you don't have time to work on the issue right away--the important thing is to let the Executive Committee (EC) know your time frame so that if the issue is important, we can reassign resources appropriately.

If an issue is appropriately assigned, the assignee can provide valuable information to the person who reported the issue and to the EC by classifying it as follows:

1. This is a question. (This can include cases where a user is reporting a bug but actually they are just confused about the proper usage of a feature.)<br/>
  a. The answer is... (Enter text to be forwarded to the user by Help Desk personnel.) (The assignee can then resolve (not close) the ticket.)<br/>
  b. I will need to do more research to answer this. I will answer within X days.
    (Also, it's helpful if you can indicate if this is a question that is likely to come up again and thus should be added by UE to the relevant documentation.)
    
2. This is a task.<br/>
  a. I did the task. (The assignee can then close the ticket.)<br/>
  b. This is a non-trivial task; I will complete it within X days.<br/>
  c. This task is out of scope or not high enough priority. (The production lead and the EC can then verify that this is the case.)<br/>
  
3. This is a bug report.<br/>
  a. I was able to confirm that the bug happens as described. It should be fixed within X days. (The assignee should not close the ticket until the fix is committed and merged.)<br/>
  b. I could not reproduce the problem, and need more information.

4. This is a request for an improvement or new feature.<br/>
  a. This was easy to do so I did it. (Once the fix is committed, merged and deployed, the assignee can close the ticket.)<br/>
  b. It is on our roadmap and will likely be included in release X.<br/>
  c. It's not on our roadmap, but it's a good idea, so EC should consider adding it to our list.<br/>
  d. It's not on our roadmap and shouldn't be.

**Don't forget to close your tickets when they're done.**

The User Engagement team will send the EC a monthly report about JIRA performance, including the identification of top issues and bottlenecks.
https://atlassian.kbase.us/issues/?filter=10909 gives a good snapshot.
