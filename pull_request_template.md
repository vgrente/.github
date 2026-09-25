## What and why
<!-- 2-3 sentences max. Link the ticket. Keep this shorter than the diff. -->

## Risk level
- [ ] Leaf: isolated code, new component/endpoint, or behind a feature flag
- [ ] Trunk: core logic, shared state, infrastructure, many dependents

Feature flag: `<name>` / none
Rollback: <flip flag / revert / needs migration rollback>
Behaviour that must NOT change: <...>

## Evidence
- Tests: <new/changed test names, not the full list>
- Runtime: <log lines, metrics, trace, or "n/a">
- UI: <screenshot or video, or "n/a">

## Agent confidence
<high / medium / low, and which part is least certain>

## Reviewer focus
<the 1-3 places a human should really read>
