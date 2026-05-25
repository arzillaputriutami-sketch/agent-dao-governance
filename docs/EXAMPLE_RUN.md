# Example Run — DAO Governance Copilot

This artifact records a deterministic reviewer demo run for the MiMo approval pattern.

- Project: **DAO Governance Copilot**
- Domain: DAO governance
- Scenario: `treasury diversification proposal with admin execution payload`
- Status: `completed`
- Mode: `deterministic-reviewer-demo`
- Specialist agents: 5
- Estimated tokens: **32,806**
- Daily projection: **3,149,376 tokens/day**

## Findings

### Liquidity Scout
- Role: tracks pool depth, volatility spikes, and suspicious flow concentration
- Severity: `high`
- Confidence: `0.8`
- Estimated tokens: `9018`
- Finding: Liquidity Scout reviewed DeFi risk monitoring signal: treasury diversification proposal with admin execution payload. Risk pattern=high confidence=0.8.
- Recommendation: Run liquidity scout follow-up pass, capture artifacts, then prioritize high items first.

### Exploit Sentinel
- Role: maps events to known attack primitives and detects anomalous protocol behavior
- Severity: `low`
- Confidence: `0.87`
- Estimated tokens: `4208`
- Finding: Exploit Sentinel reviewed DeFi risk monitoring signal: treasury diversification proposal with admin execution payload. Risk pattern=low confidence=0.87.
- Recommendation: Run exploit sentinel follow-up pass, capture artifacts, then prioritize low items first.

### Oracle Auditor
- Role: checks oracle drift, stale feeds, and manipulation windows
- Severity: `critical`
- Confidence: `0.82`
- Estimated tokens: `6455`
- Finding: Oracle Auditor reviewed DeFi risk monitoring signal: treasury diversification proposal with admin execution payload. Risk pattern=critical confidence=0.82.
- Recommendation: Run oracle auditor follow-up pass, capture artifacts, then prioritize critical items first.

### Treasury Guardian
- Role: scores treasury exposure and proposes emergency controls
- Severity: `critical`
- Confidence: `0.63`
- Estimated tokens: `4703`
- Finding: Treasury Guardian reviewed DeFi risk monitoring signal: treasury diversification proposal with admin execution payload. Risk pattern=critical confidence=0.63.
- Recommendation: Run treasury guardian follow-up pass, capture artifacts, then prioritize critical items first.

### Incident Reporter
- Role: synthesizes operator-grade markdown incident reports
- Severity: `high`
- Confidence: `0.75`
- Estimated tokens: `8422`
- Finding: Incident Reporter reviewed DeFi risk monitoring signal: treasury diversification proposal with admin execution payload. Risk pattern=high confidence=0.75.
- Recommendation: Run incident reporter follow-up pass, capture artifacts, then prioritize high items first.

