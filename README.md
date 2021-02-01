# 18.6 Commit best practices
Ideally, each commit should be _minimal_ but complete:
  * **Minimal**: A commit should only contain changes related to a single problem. This will make it easier to understand the commit at a glance, and to describe it with a simple message. If you should discover a new problem, you should do a separate commit.
  * **Complete**: A commit should solve the problem that it claims to solve. If you think you’ve fixed a bug, the commit should contain a unit test that confirms you’re right.

Each commit message should:
  * **Be concise, yet evocative**. At a glance, you should be able to see what a commit does. But there should be enough detail so you can remember (and understand) what was done.
  * **Describe the why, not the what**. Since you can always retrieve the diff associated with a commit, the message doesn’t need to say exactly what changed. Instead it should provide a high-level summary that focuses on the reasons for the change.
