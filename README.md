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
│       └── self_termination   terminal-phase transmission. system POV.
└── issues/                    open and closed defect records. most are by_design.
```

## INSTALLATION

By accessing this repository the subject has already accepted the terms. See LICENSE.

## CONTRIBUTING

Contributions are not accepted. The system maintains itself.

## LICENSE

See LICENSE file.
