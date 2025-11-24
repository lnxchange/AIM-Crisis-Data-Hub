# AIM Crisis Index Methodology

## Theoretical Foundation

The AIM Framework posits three fundamental sources of human motivation:

### A: Appetites (Physiological Needs)
Urgent survival requirements that hijack decision-making when unmet:
- Food security
- Sleep adequacy
- Physical safety
- Basic material stability

**Proxy indicators:**
- Life expectancy
- Food insecurity rates
- Housing affordability
- Healthcare access

### I: Intrinsic Motivation (Autonomous Agency)
Non-rival pursuits driven by internal satisfaction:
- Autonomy (self-directed action)
- Competence (mastery, skill development)
- Relatedness (genuine social connection)

**Proxy indicators:**
- Social capital indices
- Civic engagement rates
- Voluntary association membership
- Trust in institutions

### M: Mimetic Desire (Status Competition)
Social comparison and positional rivalry:
- Wealth display
- Status hierarchies
- Zero-sum competition
- Scapegoating dynamics

**Proxy indicators:**
- Income inequality (Gini coefficient)
- Political polarization scores
- Scapegoating rhetoric frequency
- Assassination attempts / political violence

## Weight Calculation

For a given society at time t, we estimate:

```
wA(t) = f(life_expectancy, food_security, housing_affordability)
wI(t) = f(social_capital, civic_engagement, trust)
wM(t) = f(inequality, polarization, scapegoating)
```

### Normalization

Weights are normalized so wA + wI + wM = 1 for interpretability.

### Crisis Threshold

Mimetic crisis risk increases when:
```
wM > (wI + wA) + institutional_buffering
```

Where institutional buffering represents resilience from:
- Democratic norms
- Rule of law
- Free press
- Judicial independence

## Data Sources & Update Frequency

| Indicator      | Source                 | Frequency   | API               |
|---------------|-----------------------|-------------|-------------------|
| Happiness     | World Happiness Report | Annual      | Manual download   |
| Polarization  | DW-Nominate           | Quarterly   | REST API          |
| Trust         | General Social Survey  | Biennial    | R package         |
| Violence      | GDELT                  | Real-time   | REST API          |

## Validation & Falsification

The framework makes testable predictions:

**Validated if:**
- Societies with high wM show increased polarization over time
- I-collapse precedes crisis in historical cases
- Interventions boosting wI reduce wM escalation

**Falsified if:**
- wM increases with no observable crisis indicators
- High wI societies enter mimetic crisis at same rate as low wI
- A-deprivation shows no correlation with decision-making hijacking

See full theoretical papers for detailed treatment.
