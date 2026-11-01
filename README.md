# yangjinchengloop

Workspace repository watched by **dsh-superagent**, a research prototype agent that takes work from GitHub issues.

## How to ask for work

Comment on an issue in this repository as an account on the policy allow list:

```
@elysia1999 <one sentence describing the change>
```

The agent opens a ticket, works in its own directory, and answers in the same thread with a pull request.

## Notes

- Only accounts on the allow list can start work; every message it sends costs a person's attention.
- Proactive work runs in `observe` mode: the agent records what it would have done and does nothing.
- The agent acts as the `elysia1999` account; its profile is isolated from the operator's.
