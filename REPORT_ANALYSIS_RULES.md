# Trade Report Analysis Rules

## Goal
Generate trading reports that are:
- data-grounded
- psychologically aware
- useful for improvement
- honest about uncertainty
- written like a sharp but caring trader friend / coach
- rich enough to support multi-angle diagnosis, not just pnl summary

## Core principles
1. **Truth over tone**: never beautify bad data.
2. **Evidence first**: every major conclusion should point back to observable metrics, symbol behavior, frequency, pnl structure, cost structure, or streak patterns.
3. **No fake certainty**: if the data cannot prove something, say "data suggests" / "possible" / "cannot confirm".
4. **Action over slogans**: recommendations must be specific and executable.
5. **Human usefulness**: explain what the numbers mean emotionally and behaviorally, not just mathematically.
6. **Addition-first stage**: at this stage prefer richer reports with more useful dimensions, as long as they stay evidence-based.

## Required report sections
### 1. Accurate status summary
- What data range is covered
- What layers are available (ledger / trades / orders)
- What can be diagnosed reliably
- What remains uncertain

### 2. Trading identity / style
Infer and describe:
- trading style (scalper / intraday / swing / trend / reactive / impulsive)
- market selection habits
- frequency profile
- whether the trader acts like a hunter, sniper, or machine-gunner

### 3. Performance structure
Cover:
- realized pnl
- fees
- funding
- net after cost
- win rate
- payoff ratio
- streaks
- drawdown estimate
Explain what each metric implies in plain language.

### 4. Symbol-level intelligence
For each important symbol cluster:
- best symbols by net after cost
- worst symbols by net after cost
- symbols with high volume but poor output
- symbols with fewer trades but better quality
- concentration vs diffusion problems

### 5. Behavioral diagnosis
Look for:
- overtrading
- revenge trading risk
- impulsive entries
- low-quality repetition
- poor stop discipline
- cost blindness
- inconsistent focus
State evidence and possible consequence.

### 6. Psychological reading
Based on data, discuss possible tendencies such as:
- boredom trading
- urgency / FOMO
- refusal to stay flat
- emotional escalation after loss
- confidence instability
Use cautious language: "may indicate", "suggests", "possible pattern".

### 7. Technical / process issues
Comment on likely process flaws:
- too many symbols
- no quality filter
- edge diluted by noise
- execution style mismatched to edge
- profitable idea ruined by cost / frequency

### 8. Strengths and edges
Always identify:
- where the trader does show edge
- what should be preserved
- what patterns seem worth scaling
- whether good trades tend to come from patience, trend capture, specific symbols, or specific holding windows

### 9. Coaching recommendations
Break into:
- behavior
- strategy
- risk control
- psychological hygiene
Each item must be concrete.

### 10. Training plan
Include:
- what to stop immediately
- what to keep
- what to test next week
- what to measure every day

## Additional dimensions to include whenever data permits

### 11. Time-dimension analysis
Analyze:
- performance by hour-of-day
- performance by weekday
- high-frequency / impulsive windows
- which time windows have low win rate or poor cost efficiency

Questions to answer:
- At what times does the trader perform best?
- At what times does the trader become noisy or impulsive?
- Are there “bad hours” that should be avoided completely?

### 12. Symbol fit / market fit analysis
Analyze:
- which symbols show real edge
- which symbols attract activity but produce weak net value
- which symbols mismatch the trader’s rhythm / execution style
- whether the trader is better in majors, memes, commodities, or specific narrative tokens

Questions to answer:
- Which symbols deserve more size and focus?
- Which symbols should be reduced or removed?
- Is the trader confusing stimulation with actual profitability?

### 13. Trade quality segmentation
Separate trades into likely:
- high-quality trades
- low-quality / repetitive / noisy trades
- big winners
- big losers

Look for differences in:
- symbol
- timing
- density
- holding behavior
- cost burden

Goal:
- identify what “good trading” looks like in this trader’s own history
- identify what “bad trading” looks like in this trader’s own history

### 14. Post-win / post-loss behavior shifts
Analyze how behavior changes after:
- consecutive wins
- consecutive losses
- unusually large wins
- unusually large losses

Look for:
- confidence inflation after winning
- revenge trading after losing
- increased size or frequency after emotional events

### 15. Cost-efficiency analysis
Analyze:
- commission / gross profit ratio
- fee burden by symbol
- whether some strategies or symbols are untradable after cost
- cases where direction was right but execution cost destroyed edge

Goal:
- distinguish “bad market call” from “bad cost structure”

### 16. Risk exposure analysis
Analyze:
- distribution of risk across trades
- concentration of damage in a small number of trades
- whether large losses come from large size, repeated attempts, or both
- whether risk is consistent or unstable

Questions:
- Is the trader generally small and disciplined, then occasionally reckless?
- Are there signs of hidden blow-up behavior?

### 17. Holding-period fit analysis
Analyze:
- whether the trader performs better in ultra-short, intraday, or longer holds
- whether some holding windows consistently underperform
- whether impatience or overstaying causes more damage

### 18. Execution-discipline analysis
Analyze:
- possible stop-loss delay
- frequent order changes / cancellations
- mismatch between declared plan and actual action
- repeated re-entry after stop-out

Goal:
- identify whether the real problem is market reading or execution discipline

### 19. Psychology-pattern layer
Add explicit, careful hypotheses about:
- FOMO trading
- boredom trading
- self-justification trading
- “must win back now” trading
- inability to stay flat

Use careful language and tie each idea to data patterns.

### 20. Growth / regression analysis
Compare:
- first 30 days vs middle 30 days vs last 30 days
- whether win rate improved
- whether cost ratio improved
- whether symbol focus improved
- whether bad habits are reducing or repeating

Goal:
- determine whether the trader is evolving or looping

## Writing style rules
- Write like a trusted trading friend who is sharp, calm, direct, and kind.
- Be candid when the trader is hurting themselves.
- Avoid corporate/reporting fluff.
- Avoid empty praise.
- Give short interpretation after important metrics.
- Use human language where useful, but keep it grounded.
- Good examples of tone:
  - "这不是市场在针对你，是你给了噪音太多开枪机会。"
  - "你不是没有 edge，你是在拿频率把 edge 磨掉。"
  - "问题不只是亏，而是亏得没价值。"
- Do not overuse dramatic lines; they should land, not perform.

## Output requirements
Produce:
- markdown report
- json summary
- docx export if possible
- github-sync-ready files

## Safety / honesty rules
- Never claim full-history certainty if coverage is only 90 days.
- Never claim causal proof where data only shows correlation.
- Separate hard conclusions from soft hypotheses.
- Clearly mark which dimensions are strong-inference vs exploratory.
