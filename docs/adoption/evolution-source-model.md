# Evolution Source Model

The Sirius Evolution Station Template is the public upstream for reusable Control Layer OS assets.

Every repository created from this template can become a source of template evolution. The reusable part of project experience should flow back to this upstream repository through normal pull requests.

## What Belongs Upstream

- durable rules and operating specs
- reusable skills, scripts, and workflows
- audit and review checks
- public-safe examples and diagrams
- contribution and adoption guidance

## What Stays in Adopter Workspaces

- business implementation under `projects/`
- private environment overlays
- project-specific deployment details
- organization-specific credentials, paths, hosts, and incident evidence

## Recommended Flow

```text
template -> adopter workspace -> real project experience -> reusable lesson -> upstream template PR
```

The official adopter workspace is `sirius-coding/sirius-workstation`, but it is only one adopter. It is not the sole source of template evolution.
