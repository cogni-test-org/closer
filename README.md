# node-template

Node-at-root template — a Cogni full-app submodule node. The operator's wizard `generate`s a new node repo from this template, sets its identity, and pins it as a git submodule at `nodes/<slug>` in the operator monorepo.

Seeded from `Cogni-DAO/cogni:nodes/node-template/`. `.cogni/secrets-catalog.yaml` + `k8s/external-secrets/` are intentionally absent (bug.5086 Part D — inherited via ESO).

> This is the **candidate-a / test** mint source (`cogni-test-org`). Prod mints from `Cogni-DAO/node-template`.
