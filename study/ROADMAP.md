# Secret Server Engineer study roadmap

Use Delinea University and the current official course/exam guidance as the authority. This roadmap is a practical study aid, not an official exam blueprint or question bank.

## Starting point
Previously practiced in discussion; hands-on validation is still required:
- Secret templates versus individual secrets; fields and ownership.
- Heartbeat versus Remote Password Changing (RPC).
- Distributed Engines, Site Connectors, queued work, and dependency updates.
- Introductory permissions, discovery, workflows, session recording, and recovery concepts.

## Practice sequence
| Stage | Focus | Evidence to record |
| --- | --- | --- |
| 1 | Inventory and supported lab design | Product version, platform, resource limits, architecture |
| 2 | Templates, secrets, folders, permissions | Create a test secret; verify permitted and denied access |
| 3 | Heartbeat and password rotation | Baseline, controlled failure, recovery, verification |
| 4 | Engines and connectivity | Work path, required connectivity, queue/failure observations |
| 5 | Discovery and onboarding | Scoped test target, results, review and onboarding decisions |
| 6 | Dependencies | Test service dependency, rotation result, recovery procedure |
| 7 | Requests and workflows | Request, approval, denial, expiry, audit evidence |
| 8 | Session recording | Prerequisites, test session, access controls, playback evidence |
| 9 | Backup and recovery | Document backup scope; perform an isolated restore when available |

Feature availability depends on licensing, version, and deployment. Mark unavailable labs as blocked rather than completed.

## Completion standard
For each lab, explain the feature, perform the task, demonstrate a failure or denied action where appropriate, and document recovery. Record the official source and product version used.
