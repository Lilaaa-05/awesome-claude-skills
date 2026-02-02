# Output Creation Guide

Best practices and guidelines for creating high-quality consulting deliverables in Markdown format.

## Output Philosophy

### Slide-First Approach

**Core Principle**: Each slide is a standalone, self-contained unit with:
- One clear message
- Supporting data/analysis
- Visual element (chart/diagram)
- Source citations
- "So What" insight

### Quality Standards

Every deliverable must meet:
1. **Clarity**: Immediately understandable
2. **Data-Driven**: Evidence-based claims
3. **Actionable**: Clear next steps
4. **Professional**: Consulting-grade quality
5. **Consistent**: Uniform formatting and style

---

## Slide Structure

### Basic Template

```markdown
## [Slide Title - Clear and Specific]

**Message**: [One sentence - the key takeaway]

### [Section Heading]

[Content with data, analysis, or explanation]

[Chart/Visual Description or Data Table]

**Key Insights**:
- [Insight 1 - What does the data mean?]
- [Insight 2 - Why does it matter?]
- [Insight 3 - What should be done?]

**Source**: [Data sources with URLs if available]

---
**So What**: [Bottom-line implication and recommended action]
```

### Example: Market Analysis Slide

```markdown
## Southeast Asian E-commerce Market Shows 25% Annual Growth

**Message**: Market is expanding rapidly, creating significant entry opportunity

### Market Size and Growth

The e-commerce market in Southeast Asia has grown from $50B in 2020 to $120B in 2025, 
representing a 19% CAGR. Growth is expected to accelerate to 25% through 2030.

**Market Size Trend (2020-2030)**
| Year | Market Size ($B) | Growth Rate |
|------|------------------|-------------|
| 2020 | 50 | - |
| 2023 | 85 | 19% |
| 2025 | 120 | 18% |
| 2030E | 360 | 25% |

**Key Drivers**:
- Smartphone penetration increasing from 60% to 85%
- Rising middle class (300M+ by 2030)
- Improved logistics infrastructure
- Digital payment adoption

**Key Insights**:
- Market growth outpacing global average (25% vs 12%)
- Indonesia and Vietnam showing highest growth (30%+)
- Mobile commerce represents 75% of transactions

**Source**: ASEAN E-commerce Report 2025, Statista, Company Analysis

---
**So What**: Strong growth fundamentals support market entry decision; 
recommend focusing on mobile-first strategy in Indonesia and Vietnam
```

---

## Chart Integration Guidelines

### One Slide = One Integrated Chart

**Don't**: Create multiple small charts
```markdown
❌ Bad Example:
Chart 1: Market Size
Chart 2: Growth Rate  
Chart 3: Market Share
Chart 4: Regional Breakdown
```

**Do**: Combine into one comprehensive visualization
```markdown
✅ Good Example:
Compound Chart: Market Size Evolution with Growth Rates and Regional Breakdown
- Primary Y-axis: Market Size ($B)
- Secondary Y-axis: Growth Rate (%)
- Segmentation: By region (color-coded)
```

### Chart Types by Purpose

**Comparison**: 
- Bar charts (side-by-side or stacked)
- Radar charts
- Comparison tables

**Trends**:
- Line charts
- Area charts
- Waterfall charts

**Composition**:
- Pie charts (use sparingly)
- Stacked bar/area charts
- Tree maps

**Relationship**:
- Scatter plots
- Bubble charts
- Matrix diagrams

**Process/Flow**:
- Flowcharts
- Gantt charts
- Swimlane diagrams

### Visual Description Format

Since Markdown doesn't render complex charts, describe clearly:

```markdown
**[Chart Title]**: [Chart Type]

**Visualization**:
```
[ASCII art or structured description]
```

**Data Points**:
| Category | Value | Change |
|----------|-------|--------|
| Item 1   | 100   | +10%   |
| Item 2   | 200   | +25%   |

**Visual Elements**:
- Color coding: [Describe color scheme]
- Emphasis: [What's highlighted]
- Annotations: [Key callouts]
```

---

## Writing Guidelines

### Message Clarity

**Formula**: Subject + Verb + Object + Impact

**Examples**:
- ✅ "Reducing price by 10% will increase volume by 25%, improving profit by $5M"
- ❌ "Price reduction analysis"

### Data Presentation

**Always Include**:
- Actual numbers (not just percentages)
- Time periods
- Comparison points
- Units clearly stated
- Sources cited

**Example**:
```markdown
Revenue grew from $50M (2023) to $75M (2025), representing 50% growth over 2 years 
and outpacing industry average of 20%.
Source: Company financials, Industry report 2025
```

### Insights vs. Observations

**Observation** (Describes): "Revenue declined by 15%"

**Insight** (Explains + Interprets): "Revenue declined by 15% primarily due to customer 
churn in the SMB segment (down 30%), which was triggered by competitor pricing actions 
in Q3 2024"

---

## Formatting Standards

### Hierarchy

```markdown
# Project Title (H1 - Once per document)

## Slide Title (H2 - Each slide)

### Section Heading (H3 - Within slides)

#### Subsection (H4 - Sparingly)
```

### Lists

**Bullet Points**:
- Use for non-sequential items
- Keep parallel structure
- Limit to 5-7 items per list
- Use sub-bullets sparingly

**Numbered Lists**:
1. Use for sequential steps
2. Or prioritized items
3. Or ranking

### Tables

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data     | Data     | Data     |
| Data     | Data     | Data     |

Alignment:
| Left | Center | Right |
|:-----|:------:|------:|
| Text | Text   | Text  |
```

### Emphasis

- **Bold** for key terms and emphasis
- *Italics* for subtle emphasis or definitions
- `Code format` for technical terms, tools, metrics
- > Blockquotes for important callouts

---

## Firm-Specific Formatting

### McKinsey Style
- Clean and minimal
- Data-first
- Blue color scheme references
- Strong "So What" statements

### BCG Style
- Visual and dynamic
- Storytelling flow
- Green color scheme references
- Strategic perspective

### Bain Style
- Action-oriented
- Implementation focus
- Red color scheme for actions
- ROI emphasis

### EY Style
- Nexus thinking indicators
- Wave-based approach
- Yellow highlights for insights
- Value creation focus

### Deloitte Style
- Comprehensive detail
- Risk callouts
- Multi-stakeholder view
- Green color scheme

---

## Quality Checklist

### Before Delivering Each Slide

**Content**:
- [ ] One clear message per slide
- [ ] Data supports message
- [ ] Sources cited
- [ ] "So What" stated
- [ ] Action-oriented

**Format**:
- [ ] Title is specific and clear
- [ ] One integrated chart (not multiple small ones)
- [ ] Proper hierarchy (H2, H3, H4)
- [ ] Consistent formatting
- [ ] No typos

**Logic**:
- [ ] Message follows from data
- [ ] Insights are meaningful
- [ ] Recommendations are actionable
- [ ] Fits overall storyline

---

## Common Mistakes to Avoid

### Content Mistakes

❌ **Too much information**: Keep to key points only
❌ **No clear message**: Every slide must have one
❌ **Data without insight**: Always provide "So What"
❌ **Vague recommendations**: Be specific and actionable
❌ **Missing sources**: Always cite data sources

### Formatting Mistakes

❌ **Inconsistent headers**: Use standard hierarchy
❌ **Multiple small charts**: Integrate into one
❌ **Wall of text**: Use bullets, tables, visuals
❌ **Unclear tables**: Format properly with alignment
❌ **Missing emphasis**: Use bold/italics strategically

### Logic Mistakes

❌ **Conclusion doesn't follow**: Ensure logical flow
❌ **Missing key information**: Address all critical points
❌ **Unclear storyline**: Each slide should connect
❌ **Assumptions not stated**: Make explicit
❌ **Risks not addressed**: Acknowledge and mitigate

---

## Progress Tracking in Outputs

### Status Indicators

Use in filenames and headers:
```markdown
# Market Entry Strategy - Status: 7/15 slides (47%)

✅ Completed slides
📝 In progress
⬜ Not started
```

### Version Control

```markdown
**Document Information**:
- Version: 2.1
- Date: 2026-02-02
- Status: Draft / Final
- Author: [Name]
- Reviewer: [Name]
```

---

## Markdown to Slides Conversion

### Recommended Tools

1. **Gamma AI** (https://gamma.app/)
   - AI-powered design
   - Multiple templates
   - Easy customization

2. **Beautiful.ai** (https://www.beautiful.ai/)
   - Smart templates
   - Team collaboration
   - Brand consistency

3. **Slides AI** (https://www.slidesai.io/)
   - Fast conversion
   - Style options
   - Export formats

### Conversion Tips

- Use clear H2 headers (becomes slide titles)
- Include visual descriptions (guides AI rendering)
- Keep formatting simple
- Test with your chosen tool
- Adjust Markdown based on output

---

## Example: Complete Slide

```markdown
## Cloud Migration Will Reduce IT Costs by 30% While Improving Scalability

**Message**: Migrating to cloud delivers significant cost savings and enables business growth

### Total Cost of Ownership (TCO) Comparison

**5-Year TCO Analysis ($M)**:

| Component | On-Premise | Cloud | Savings |
|-----------|------------|-------|---------|
| Infrastructure | $15M | $8M | $7M (47%) |
| Operations | $10M | $5M | $5M (50%) |
| Maintenance | $8M | $3M | $5M (63%) |
| **Total** | **$33M** | **$16M** | **$17M (52%)** |

**Cost Evolution**:
```
Year 1: Higher (migration costs)
Year 2-3: Break-even
Year 4-5: 30% savings achieved
```

**Additional Benefits**:
- Scalability: Can scale capacity up/down based on demand
- Agility: Deploy new services in days vs months
- Reliability: 99.95% uptime vs 99.5% current
- Innovation: Access to AI/ML services without capex

**Migration Approach**: Phased 6R strategy
- 40% Rehost (lift-and-shift) - Quick wins
- 30% Refactor (modernize) - Long-term value
- 20% Repurchase (SaaS) - Eliminate maintenance
- 10% Retire (decommission) - Remove waste

**Key Risks & Mitigation**:
- Data security → Implement zero-trust architecture
- Vendor lock-in → Use multi-cloud strategy
- Skills gap → Training program + managed services

**Source**: Internal IT assessment, Gartner Cloud Economics Report 2025, 
AWS/Azure pricing models

---
**So What**: Cloud migration is financially compelling with 30% cost reduction 
and strategic benefits. Recommend proceeding with phased approach starting Q2 2026, 
prioritizing rehost candidates for quick wins while planning refactoring roadmap.
```

---

## Final Tips

### For Efficiency
- Use templates for common slide types
- Build reusable components
- Keep formatting consistent from start
- Document decisions and rationale

### For Impact
- Lead with conclusions
- Use data to prove, not just describe
- Make recommendations specific
- Show implementation path

### For Quality
- Review against checklist
- Get feedback early
- Iterate based on input
- Maintain firm format standards

---

*This guide should be used in conjunction with FIRM_FORMATS.md for firm-specific styling*
