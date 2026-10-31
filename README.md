# Svartalfheim Phase 6 Acceptance Fixture

This public, disposable repository is an isolated Git workspace for operator-approved Codex sandbox acceptance testing.

The acceptance agent is asked to create `phase6_acceptance.txt` containing exactly:

`Svartalfheim Phase 6 live acceptance`

No secrets, production credentials, private source code, or sensitive data belong in this repository. Agent changes are expected to remain inside ephemeral Kubernetes workspaces; this fixture does not require agents to push to GitHub.

Test evidence and artifact archives are stored locally and must be reviewed before namespace cleanup.
