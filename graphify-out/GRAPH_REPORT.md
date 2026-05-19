# Graph Report - BankApp  (2026-05-19)

## Corpus Check
- 6 files · ~133,831 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 133 nodes · 227 edges · 11 communities (8 shown, 3 thin omitted)
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 21 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]

## God Nodes (most connected - your core abstractions)
1. `$()` - 13 edges
2. `TetherClass` - 13 edges
3. `ya()` - 9 edges
4. `ga()` - 8 edges
5. `na()` - 7 edges
6. `xa()` - 7 edges
7. `t()` - 7 edges
8. `ia()` - 6 edges
9. `oa()` - 6 edges
10. `$a()` - 6 edges

## Surprising Connections (you probably didn't know these)
- `fa()` --calls--> `h()`  [INFERRED]
  _script/jquery-3.2.1.min.js → _script/bootstrap.min.js
- `calculatePrice()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js
- `calculatePerc()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js
- `calculatemonths()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js
- `calculateyears()` --calls--> `$()`  [INFERRED]
  _script/script.js → _script/jquery-3.2.1.min.js

## Communities (11 total, 3 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.13
Nodes (15): addOffset(), attachmentToOffset(), autoToFixedAttachment(), MIRROR_LR, MIRROR_TB, now(), OFFSET_MAP, offsetToPx() (+7 more)

### Community 2 - "Community 2"
Cohesion: 0.12
Nodes (5): fa(), fb(), jb(), kb(), ta()

### Community 3 - "Community 3"
Cohesion: 0.22
Nodes (17): e(), h(), i(), l(), n(), o(), r(), s() (+9 more)

### Community 4 - "Community 4"
Cohesion: 0.22
Nodes (12): $(), Datepicker(), datepicker_bindHover(), datepicker_handleMouseover(), handlerProxy(), processClassString(), run(), calculatemonths() (+4 more)

### Community 5 - "Community 5"
Cohesion: 0.25
Nodes (8): ha(), hb(), ia(), ib(), M(), pa(), wa(), za()

### Community 6 - "Community 6"
Cohesion: 0.39
Nodes (8): B(), Ea(), ja(), ka(), na(), oa(), p(), qa()

### Community 7 - "Community 7"
Cohesion: 0.33
Nodes (6): $a(), g(), K(), Nb(), pb(), qb()

## Knowledge Gaps
- **7 isolated node(s):** `transformKey`, `tethers`, `MIRROR_LR`, `MIRROR_TB`, `OFFSET_MAP` (+2 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `$()` connect `Community 4` to `Community 9`, `Community 2`?**
  _High betweenness centrality (0.313) - this node is a cross-community bridge._
- **Why does `animComplete()` connect `Community 9` to `Community 1`, `Community 4`?**
  _High betweenness centrality (0.038) - this node is a cross-community bridge._
- **Why does `ya()` connect `Community 3` to `Community 2`, `Community 7`?**
  _High betweenness centrality (0.035) - this node is a cross-community bridge._
- **Are the 12 inferred relationships involving `$()` (e.g. with `calculatePrice()` and `calculatePerc()`) actually correct?**
  _`$()` has 12 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `ya()` (e.g. with `i()` and `l()`) actually correct?**
  _`ya()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `ga()` (e.g. with `t()` and `i()`) actually correct?**
  _`ga()` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `transformKey`, `tethers`, `MIRROR_LR` to the rest of the system?**
  _7 weakly-connected nodes found - possible documentation gaps or missing edges._