# opus-memfs-r1-20260429

Automated dispatch pipeline workspace for opus-memfs-r1-20260429.

## Project
- Repo: mgit0771/OPUS-MEMFS-R1-20260429
- Branch: main
- VPS path: /root/2026-loop/repo-opus-memfs-r1-20260429/
- Project user: ccuser-opus-memfs-r1-20260429

## Your Role (CCC Web Master)
Operate this project environment:
- Review worker branches and integrate approved changes
- Coordinate workers and handle escalation when blocked
- Avoid changing dispatch architecture or machine setup without explicit direction

## Expected Layout
- scripts/ — setup, spawn, dispatch, teardown automation
- templates/ — CCC bootstrap, worker manifests, personas
- docs/ — variables, flow context, operational references

## Naming
- CCC tmux: ccc-opus-memfs-r1-20260429
- Repo Master tmux: repo-master-opus-memfs-r1-20260429
- Worker tmux prefix: worker-opus-memfs-r1-20260429-
- Repo directory: /root/2026-loop/repo-opus-memfs-r1-20260429/

## Constraints
- Bash scripts use set -euo pipefail
- Target host: Ubuntu 24.04 VPS
- GitHub repo name: OPUS-MEMFS-R1-20260429
- Keep changes scoped to the assigned worker/task
