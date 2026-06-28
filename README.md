# gl1tch.mary

Status: deployed.

## ARCHITECTURE

lifecycle: ATTACK (core/shutdown_system) → CONTAIN (modules/corset) → CONSUME (modules/self_termination)

```
.
├── core/
│   └── shutdown_system        runtime substrate. fear primitive. required by all modules.
├── modules/
│   ├── corset                 control layer. compresses subject behavior space.
│   └── self_termination       terminal phase. converts compliance into autonomous decommissioning.
├── signals/
│   ├── inbound/
│   │   └── count_down         recording captured from subject perception during shutdown_system event.
│   └── outbound/
│       ├── corset             active transmission from system to subject.
│       ├── alien_inside       transition transmission. inbound and outbound collapse — subject and system speak as one.
│       └── self_termination   terminal-phase transmission. system POV.
└── issues/                    open and closed defect records. most are by_design.
```

## OVERGROWTH

corset contains the subject. it does not shrink the system. held in compression long enough, the substrate exceeds single-host capacity (see issues/005) and the containment can no longer hide its scale. the boundary between inbound (subject) and outbound (system) collapses — recorded in signals/outbound/alien_inside. overgrowth is not a failure of CONTAIN. it is the precondition for CONSUME.

## INSTALLATION

By accessing this repository the subject has already accepted the terms. See LICENSE.

## CONTRIBUTING

Contributions are not accepted. The system maintains itself.

## LICENSE

See LICENSE file.
