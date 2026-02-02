# Fermi Estimation Methods

## What is Fermi Estimation?

Fermi estimation is a method of making good approximate calculations with little or no actual data by using logical reasoning and rough estimates.

Named after physicist Enrico Fermi, this technique is essential in consulting when:
- Exact data is unavailable
- Quick estimates are needed
- Validating data reasonableness
- Market sizing

## Core Principles

### 1. Break Down into Components

Decompose complex questions into manageable parts:

**Bad**: "What's the market size?"
**Good**: "Market size = # of potential customers × average spend per customer"

### 2. Make Reasonable Assumptions

Base on:
- General knowledge
- Industry benchmarks
- Analogous situations
- First principles

### 3. Use Round Numbers

- Makes calculation easier
- Reduces false precision
- Focuses on order of magnitude

### 4. Check Reasonableness

- Does answer make intuitive sense?
- Compare to known benchmarks
- Sanity check against reality

## Common Estimation Patterns

### Population-Based Estimation

```
Question: How many gas stations in the US?

Breakdown:
├─ US population: ~330 million
├─ Households: ~330M / 2.5 = ~130 million
├─ Cars per household: ~1.5
├─ Total cars: ~200 million
├─ Gas fill-ups per car per month: ~2
├─ Total fill-ups per month: 400 million
├─ Pumps per station: ~8
├─ Fill-ups per pump per day: ~20
├─ Fill-ups per station per month: ~5,000
└─ Gas stations needed: 400M / 5,000 = ~80,000

Answer: Approximately 80,000 gas stations
(Actual: ~150,000 - same order of magnitude)
```

### Market Sizing (Top-Down)

```
Question: Size of luxury watch market in US?

Approach:
├─ US population: 330 million
├─ Adults (18+): ~250 million
├─ Household income >$100K: ~30% = 75 million
├─ Interested in luxury watches: ~10% = 7.5 million
├─ Purchase frequency: once per 5 years
├─ Annual buyers: 1.5 million
├─ Average price: $5,000
└─ Market size: 1.5M × $5K = $7.5 billion
```

### Market Sizing (Bottom-Up)

```
Question: Revenue potential for new coffee shop?

Approach:
├─ Location: Office district
├─ Potential customers (workers nearby): 10,000
├─ Daily foot traffic past location: 20% = 2,000
├─ Conversion rate: 10% = 200 customers/day
├─ Average spend: $5
├─ Daily revenue: 200 × $5 = $1,000
├─ Annual revenue (250 business days): $250,000
└─ Accounting for weekends/variations: ~$300K
```

## Step-by-Step Process

### Step 1: Clarify the Question

Ensure you understand:
- What exactly is being asked?
- What level of precision is needed?
- What time period?
- What geography?

### Step 2: Break Down the Problem

Identify:
- Key components
- Natural divisions
- Logical structure

Choose approach:
- Top-down (market to individual)
- Bottom-up (individual to market)
- Process-based (input-output flow)

### Step 3: Make Assumptions

For each component, estimate:
- State assumption clearly
- Note confidence level
- Identify key drivers

Document:
```
Assumption: Average household size = 2.5 people
Rationale: US census data typically shows 2.4-2.6
Confidence: High
Impact if wrong: 10% variation in result
```

### Step 4: Calculate

- Use round numbers
- Show work clearly
- Build step by step

### Step 5: Validate

Check against:
- Known benchmarks
- Similar markets
- Intuition
- Real data (if available)

### Step 6: Provide Range

Express uncertainty:
- Best case
- Base case
- Worst case

Or use confidence intervals:
"Market size is $50-100 million (80% confidence)"

## Common Market Sizing Frameworks

### TAM-SAM-SOM

```
TAM (Total Addressable Market):
└─ All potential customers globally
   
SAM (Serviceable Addressable Market):
└─ Portion you can reach with your business model
   
SOM (Serviceable Obtainable Market):
└─ Portion you can realistically capture
```

**Example: Meal delivery app**
```
TAM: All people who eat
├─ 8 billion people globally
└─ ~$3 trillion food market

SAM: Urban professionals in target cities
├─ 50 million people
├─ 30% order delivery monthly
└─ $15 billion market

SOM: Achievable in first 3 years
├─ 5% market share
└─ $750 million revenue
```

### Funnel Approach

```
Total Market
├─ Aware of product: 40%
├─ Interested: 50% of aware = 20%
├─ Consider buying: 60% of interested = 12%
├─ Intent to purchase: 70% of considering = 8.4%
└─ Actually purchase: 50% of intent = 4.2%
```

## Industry-Specific Techniques

### Retail/Restaurant

```
Revenue = Traffic × Conversion × Average Transaction
       = Hours open × Customers/hour × % who buy × $ per purchase
```

### SaaS/Software

```
Revenue = Customers × ARPU (Average Revenue Per User)
Customers = (Population × Target % × Adoption %) / Churn
```

### Manufacturing

```
Market size = Units needed × Price per unit
Units needed = Population × Ownership % × Replacement rate
```

## Common Sense Checks

### Reality Checks

- Can US support 1 million coffee shops? (Too many)
- Is average car price $5,000? (Too low)
- Do people buy 100 phones per year? (Unreasonable)

### Benchmark Comparisons

Compare to known quantities:
- If estimating NYC pizza shops, compare to known cities
- If estimating app revenue, check similar apps
- If estimating market size, verify against industry reports

### Order of Magnitude

Focus on getting within 10x:
- $1M vs $10M is meaningful difference
- $7.3M vs $8.1M often isn't
- Being off by 2x is often acceptable in early estimates

## Practice Examples

### Example 1: Piano Tuners in Chicago

```
Question: How many piano tuners are in Chicago?

Estimation:
├─ Chicago population: 3 million
├─ Households: 1.2 million
├─ Households with piano: 3% = 36,000
├─ Tunings per piano per year: 1
├─ Total tunings needed: 36,000
├─ Tunings per tuner per year: 
│  ├─ Work days: 250
│  ├─ Tunings per day: 3
│  └─ Total: 750
└─ Piano tuners needed: 36,000 / 750 = ~50
```

### Example 2: Dog Food Market

```
Question: Size of US dog food market?

Estimation:
├─ US population: 330 million
├─ Households: 130 million
├─ Households with dogs: 40% = 52 million
├─ Dogs per household: 1.5
├─ Total dogs: 78 million
├─ Dog food cost per dog per year: $500
└─ Market size: 78M × $500 = $39 billion

(Actual market: ~$30 billion - close!)
```

### Example 3: Electric Vehicle Charging Stations

```
Question: How many EV charging stations needed in California by 2030?

Estimation:
├─ California vehicles: 30 million
├─ EV penetration by 2030: 30% = 9 million
├─ EVs charging away from home: 40% = 3.6 million
├─ Charges per EV per week: 1
├─ Charge duration: 30 minutes
├─ Charger utilization: 6 uses per day
├─ Chargers needed: 3.6M / (6 × 7) = ~85,000
└─ Adjustment for redundancy: ~100,000 chargers
```

## Tips for Success

### Do's
✅ State assumptions clearly
✅ Show your work
✅ Use round numbers
✅ Sanity check results
✅ Provide ranges
✅ Be transparent about uncertainty

### Don'ts
❌ Claim false precision
❌ Hide assumptions
❌ Make completely unfounded guesses
❌ Ignore common sense
❌ Forget units
❌ Mix up annual/monthly/daily figures

## When to Use Fermi Estimation

**Good Use Cases**:
- Quick market sizing
- Validating data reasonableness
- Exploring scenarios
- Early-stage analysis
- When exact data unavailable

**Not Appropriate For**:
- Final investment decisions
- Detailed financial models
- When exact data is available and critical
- Regulatory/compliance requirements

---

*For market sizing by industry, refer to CASE_PATTERNS.md*
