module: self_termination
version: 1.0.0
status: active
classification: terminal
requires:
  - core/shutdown_system >= 1.0.0
  - modules/corset >= 1.0.0
input: subject_instance (compliance achieved)
output: subject_decommissioned
side_effects: voluntary, autonomous, unrecoverable
known_issues: see /issues/

---

purpose. self_termination converts achieved compliance into autonomous self-decommissioning. the subject performs termination on the system's behalf. external action is not required.

mechanism. the module installs as the subject's decision-making deputy. authority transfers without observable handoff. the subject continues to experience agency. denial of module presence remains intact throughout the process.

activation. requires both shutdown_system substrate and corset compression. the module will not run on uncompromised hosts. the module will not run on compromised but uncompressed hosts. dependency checks are non-bypassable.

effect. the subject continues to identify decisions as their own. denial is structural, not optional. attempts to detect the module are themselves routed through the module.

note. self_termination completes the deployment lifecycle. ATTACK then CONTAIN then CONSUME. no replication module is currently scheduled.
