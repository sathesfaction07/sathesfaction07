# Hi, I'm Sanket

I build data and AI tools that are honest about their own accuracy. Most of the projects below start
from a question the obvious solution answers too confidently, such as *"did we get all of them?"*,
*"is this trend real?"* or *"does this confidence score mean anything?"*, and measure the answer
instead of assuming it.

Every repository runs its tests in CI on Linux and Windows.

## Start here

| Project | What it shows |
|:--|:--|
| [**Docket**](https://github.com/sathesfaction07/docket) | Live multi-user case tracking. Concurrent edits are version-checked so none is lost (measured: 17 of 24 notes lost before, none after), verified on DynamoDB and real Firestore. |
| [**AsOf**](https://github.com/sathesfaction07/asof) | Compliance checks against rules versioned by effective date, with a replayable audit log. 421 tests. |
| [**Plumbline**](https://github.com/sathesfaction07/plumbline) | A classifier that measures whether its confidence is calibrated, and abstains when the evidence is too thin. |
| [**Echelon**](https://github.com/sathesfaction07/echelon) | A multi-agent system that delegates work down capability tiers and reviews it back up, with an audited knowledge base. |
| [**Candor**](https://github.com/sathesfaction07/candor) | An SOP assistant that refuses to answer on weak evidence and turns the gap into a question for a human expert. |
| [**Lookalike**](https://github.com/sathesfaction07/lookalike) | Near-duplicate image detection with embeddings and vector search, via CLI, web API or batch pipeline. |

## AI and ML systems

- [Echelon](https://github.com/sathesfaction07/echelon): hierarchical multi-agent delegation and review
- [Candor](https://github.com/sathesfaction07/candor): question answering that knows what it doesn't know
- [Plumbline](https://github.com/sathesfaction07/plumbline): classification with calibrated confidence
- [Errorbar](https://github.com/sathesfaction07/errorbar): evaluation where every number carries its uncertainty
- [Lookalike](https://github.com/sathesfaction07/lookalike): duplicate and near-duplicate image clustering
- [Litmus](https://github.com/sathesfaction07/litmus): image screening that first checks the policy can be applied
- [Vigil](https://github.com/sathesfaction07/vigil): multilingual policy screening with a human making the call
- [Smokesignal](https://github.com/sathesfaction07/smokesignal): safety and quality risk detection in product reviews
- [Shelfwise](https://github.com/sathesfaction07/shelfwise): multi-agent product research for about half a cent per query
- [Marginalia](https://github.com/sathesfaction07/marginalia): a browser extension that answers process questions from SOPs
- [Inkgate](https://github.com/sathesfaction07/inkgate): templated messages that must pass a quality gate before sending
- [Squint](https://github.com/sathesfaction07/squint): distorted-text recognition with ranked candidates
- [Certainty](https://github.com/sathesfaction07/certainty): reading compliance certificates with vision models and checking the standards they cite
- [Plimsoll](https://github.com/sathesfaction07/plimsoll): anomaly detectors scored on precision and recall, and why an alert didn't fire
- [Tells](https://github.com/sathesfaction07/tells): evasive listing detection, with LLM reasoning on the uncertain cases
- [Twinlane](https://github.com/sathesfaction07/twinlane): bulk listing validation with headless browsers and a vision-model fallback
- [Polarity](https://github.com/sathesfaction07/polarity): rule-expression parsing with an LLM fallback, showing what each keyword really does
- [Kinship](https://github.com/sathesfaction07/kinship): entity resolution that measures how far fuzzy matching can be trusted
- [Crossroads](https://github.com/sathesfaction07/crossroads): evidence-graded engineering decision cards, including embeddings and near-duplicate detection

## Data correctness

- [Doubletake](https://github.com/sathesfaction07/doubletake): values that read two ways, like `03/04/2026`
- [Headcount](https://github.com/sathesfaction07/headcount): extraction that proves completeness, not just a total
- [Denominator](https://github.com/sathesfaction07/denominator): aggregation that shows what offset paging silently drops
- [Parallax](https://github.com/sathesfaction07/parallax): explaining disagreements between two systems of record
- [Mirage](https://github.com/sathesfaction07/mirage): trends that might be artifacts of how the data was collected
- [Meridian](https://github.com/sathesfaction07/meridian): one timeline from 16 regional feeds, with local time handled correctly
- [Vintage](https://github.com/sathesfaction07/vintage): how old a cached status reading really is
- [Afterhours](https://github.com/sathesfaction07/afterhours): business-hours SLAs and the wait they hide
- [Deadletter](https://github.com/sathesfaction07/deadletter): what delivery reports cannot prove
- [Shoehorn](https://github.com/sathesfaction07/shoehorn): what a target document format can't hold

## Trust and safety

- [Docket](https://github.com/sathesfaction07/docket): case lifecycle management with live sync
- [AsOf](https://github.com/sathesfaction07/asof): compliance as of a date, with an audit log

## Infrastructure and engineering practice

- [Ballast](https://github.com/sathesfaction07/ballast): a batch fetcher that re-tunes itself under memory pressure
- [Switchyard](https://github.com/sathesfaction07/switchyard): concurrent operations behind rate limits and circuit breakers
- [Preflight](https://github.com/sathesfaction07/preflight): how strong "this tool will run" really is
- [Firstsight](https://github.com/sathesfaction07/firstsight): resumable, idempotent search-results harvesting
