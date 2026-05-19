# Decision Report: Caslmark

A NestJS native, agent aware policy & guardrail layer that compiles state DOI insurance rules and carrier API contracts into the same CASL ability graph Jerry already trusts - so every LLM tool call is pre checked, logged, and reversible.

## Evidence-Grounded Findings

CLAIM: hardest gap should `block release until replay is understood` because blocks=3 reviews=2 mean_severity=3.333. [EVID: ev_0077]
CLAIM: hardest reviewer handoff should `block release until replay is understood` because blocks=2 reviews=4 mean_severity=2.583. [EVID: ev_0121]
CLAIM: jerry drift should `block release until replay is understood` because blocks=2 reviews=3 mean_severity=2.5. [EVID: ev_0022]
CLAIM: jerry evidence recall should `block release until replay is understood` because blocks=3 reviews=3 mean_severity=1.875. [EVID: ev_0000]
CLAIM: problem policy boundary should `block release until replay is understood` because blocks=2 reviews=3 mean_severity=1.708. [EVID: ev_0033]
CLAIM: unsolved failure replay should `block release until replay is understood` because blocks=2 reviews=4 mean_severity=3.333. [EVID: ev_0110]
