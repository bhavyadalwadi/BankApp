# Graph Report - BankApp  (2026-05-26)

## Corpus Check
- 23 files · ~135,895 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 241 nodes · 318 edges · 22 communities (13 shown, 9 thin omitted)
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 21 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `9a703603`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]

## God Nodes (most connected - your core abstractions)
1. `BankApp Project Context` - 16 edges
2. `Primary App` - 15 edges
3. `BankApp Architecture` - 14 edges
4. `$()` - 13 edges
5. `TetherClass` - 13 edges
6. `BankApp Workflows` - 10 edges
7. `ya()` - 9 edges
8. `BankApp Coding Rules` - 9 edges
9. `ga()` - 8 edges
10. `na()` - 7 edges

## Surprising Connections (you probably didn't know these)
- `fa()` --calls--> `h()`  [INFERRED]
  _script/jquery-3.2.1.min.js → _script/bootstrap.min.js
- `xa()` --calls--> `i()`  [INFERRED]
  _script/jquery-3.2.1.min.js → _script/bootstrap.min.js
- `calculatePrice()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js
- `calculatePerc()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js
- `calculatemonths()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js

## Communities (22 total, 9 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.13
Nodes (15): addOffset(), attachmentToOffset(), autoToFixedAttachment(), MIRROR_LR, MIRROR_TB, now(), OFFSET_MAP, offsetToPx() (+7 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (16): $(), animComplete(), childComplete(), complete(), Datepicker(), datepicker_bindHover(), datepicker_handleMouseover(), handlerProxy() (+8 more)

### Community 2 - "Community 2"
Cohesion: 0.08
Nodes (31): $a(), B(), E(), Ea(), fa(), fb(), g(), ha() (+23 more)

### Community 3 - "Community 3"
Cohesion: 0.31
Nodes (13): e(), h(), i(), l(), n(), o(), r(), s() (+5 more)

### Community 4 - "Community 4"
Cohesion: 0.12
Nodes (16): BankApp Project Context, Business Purpose, Critical Dependencies, Current Architecture Themes, Deployment Model, Environments, Important APIs, Important Databases (+8 more)

### Community 5 - "Community 5"
Cohesion: 0.12
Nodes (15): Critical Workflows, Dangerous Code Paths, Databases Used, Dependencies, Failure Modes, Important Source Files, Inbound APIs, Known Technical Debt (+7 more)

### Community 6 - "Community 6"
Cohesion: 0.13
Nodes (14): Auth Flow, BankApp Architecture, Caching Layers, Deployment Topology, End-to-End Request Flows, Event-Driven Architecture, Failover Behavior, Frontend / Backend Interaction (+6 more)

### Community 7 - "Community 7"
Cohesion: 0.18
Nodes (10): BankApp Workflows, Debugging, Deployment, Feature Rollout, Incident Response, Local Development, Migrations, Observability Investigation (+2 more)

### Community 8 - "Community 8"
Cohesion: 0.25
Nodes (7): BankApp, LLM Start Here, Main files, Quick Repo Summary, Start here, Status, What this repo does

### Community 9 - "Community 9"
Cohesion: 0.2
Nodes (9): API Conventions, Architecture Patterns, BankApp Coding Rules, Database / Migration Patterns, Error Handling / Logging, Naming / Structure, State Management, Testing Conventions (+1 more)

### Community 10 - "Community 10"
Cohesion: 0.29
Nodes (6): BankApp Onboarding, Critical Entrypoints, First Read, How To Start Reasoning, Local Run Baseline, Module Map

### Community 11 - "Community 11"
Cohesion: 0.5
Nodes (3): BankApp Decision Log, Graphify-first repo discovery, Preserve repo separation

### Community 12 - "Community 12"
Cohesion: 0.5
Nodes (3): Critical Entrypoints, Read First, Top-Level Modules

## Knowledge Gaps
- **90 isolated node(s):** `transformKey`, `tethers`, `MIRROR_LR`, `MIRROR_TB`, `OFFSET_MAP` (+85 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **9 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `$()` connect `Community 1` to `Community 2`?**
  _High betweenness centrality (0.094) - this node is a cross-community bridge._
- **Why does `ya()` connect `Community 3` to `Community 2`?**
  _High betweenness centrality (0.011) - this node is a cross-community bridge._
- **Are the 12 inferred relationships involving `$()` (e.g. with `calculatePrice()` and `calculatePerc()`) actually correct?**
  _`$()` has 12 INFERRED edges - model-reasoned connections that need verification._
- **What connects `transformKey`, `tethers`, `MIRROR_LR` to the rest of the system?**
  _90 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._