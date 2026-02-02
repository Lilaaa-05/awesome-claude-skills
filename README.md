# Awesome Claude Consulting Skills

A curated collection of professional consulting skills designed to transform Claude Code into an enterprise-grade business consultant. Leverage proven methodologies from top-tier consulting firms to deliver strategic analysis, business proposals, and professional deliverables.

**🌟 Star this repo** if you find these skills useful! **Contributions welcome** — [see how to contribute](#contributing).

---

## 📚 What are Skills?

Skills are specialized knowledge modules (markdown files) that extend AI agents' capabilities in specific domains. By adding skills to your project:

- **Claude Code recognizes domain-specific tasks** and applies appropriate methodologies
- **Structured workflows** guide the AI through complex, multi-step processes  
- **Industry best practices** are automatically incorporated into outputs
- **Professional frameworks** ensure high-quality, standardized deliverables

Think of skills as expert consultants embedded directly into your AI assistant.

---

## 🎯 Available Skills

<!-- SKILLS:START -->

### Professional Consulting

| Skill | Version | Language | Description |
|-------|---------|----------|-------------|
| **[all-consulting](consulting-skills/all-consulting/)** | v1.0.0 | 🇬🇧 English | Enterprise-grade consulting deliverable generator. Produces strategic analysis reports and business proposals using methodologies from top-tier consulting firms (McKinsey, BCG, Bain, Big 4, and Japanese majors). Covers 23+ scenario types across business strategy and technology domains. Features incremental build approach, web search integration, hypothesis-driven analysis, and multi-firm formatting. |
| **[jp-consulting](consulting-skills/jp-consulting/)** | v1.0.0 | 🇯🇵 Japanese | Enterprise-grade consulting deliverable generator. Produces strategic analysis reports and business proposals using methodologies from top-tier consulting firms (McKinsey, BCG, Bain, Big 4, and Japanese majors). Covers 23+ scenario types across business strategy and technology domains. Features incremental build approach, web search integration, hypothesis-driven analysis, and multi-firm formatting. |

<!-- SKILLS:END -->

#### Supported Consulting Scenarios (23+)

**Business Strategy**
- 🎯 Market Entry & Expansion
- 📊 Industry & Competitive Analysis  
- 🤝 M&A Strategy & Due Diligence
- 🚀 Product Launch & Go-to-Market
- 💰 Pricing & Monetization Strategy
- 📈 Growth & Revenue Strategy
- 💡 New Business Development & Innovation
- ⚔️ Competitive Response Strategy
- 💵 Revenue Optimization
- ✂️ Cost Reduction & Efficiency
- 📉 Profit Improvement
- 🔄 Turnaround & Restructuring

**Technology Consulting**
- 🖥️ IT System Selection & Implementation
- 🤖 AI/ML Strategy & Deployment
- ☁️ Cloud Migration & Modernization
- 🔄 Digital Transformation (DX)
- 🔒 Cybersecurity Strategy
- 📊 Data Platform & Analytics
- 🔧 RPA & Process Automation
- 🚀 DevOps Transformation
- 🏗️ Application Modernization
- 📋 IT Governance & Architecture
- ⚡ Infrastructure Optimization

**ESG & Sustainability**
- 🌱 ESG Strategy Development
- ♻️ Sustainability Roadmap

---

## ⚡ Quick Start with Claude

### 3-Minute Setup

**Step 1: Install the Skill (10 seconds)**
```bash
npx skills add <your-github-username>/awesome-claude-skills
```

**Step 2: Open Claude Code (10 seconds)**
- Open your project in Claude Code
- Or reference this skill in your Claude conversation

**Step 3: Start Using (Just ask!)**
```
User: "I want to develop a market entry strategy"
Claude: 🎯 Activating jp-consulting-output skill...
```

**That's it!** Claude automatically detects consulting scenarios and applies professional frameworks.

---

### Example Session

```
You: "Please create a market entry strategy for an e-commerce site"

Claude: Understood. I'll develop a market entry strategy.
         
         First, let me confirm a few things:
         1. Which region is the target market?
         2. Do you have a preferred firm format?
            (McKinsey/BCG/Bain/Deloitte/EY/PwC/Accenture/Abeam/NRI/Standard)
         
         Once you provide this information, I'll begin work immediately.

You: "Japanese market. Please use McKinsey format."

Claude: ⚫ Starting market entry strategy development...
        📝 Conducting market research and framework analysis...
        ✅ [Generated comprehensive research report in Markdown format]
```

---

### Prerequisites & Setup

<details>
<summary><strong>🔧 What You Need</strong></summary>

**Required:**
- [Claude Code](https://claude.ai/code) or Claude with access to your codebase
- Access to add custom skills/instructions to Claude

**Optional but Recommended:**
- Node.js (for npx commands)
- Git (for alternative installation methods)

</details>

<details>
<summary><strong>🎯 Enable Claude Skills</strong></summary>

**Using Claude Code:**
1. Add the skill files to your project workspace
2. Claude Code automatically detects and uses skills in your workspace
3. Simply start asking Claude to perform the tasks

**Using Claude.ai:**
1. Upload the skill markdown files to your conversation
2. Reference the skills in your prompts
3. Claude will apply the frameworks automatically

</details>

<details>
<summary><strong>📁 Skills Directory Structure</strong></summary>

After installation, your project should have:
```
your-project/
├── .claude/
│   └── skills/
│       └── jp-consulting/
│           ├── SKILL.md         # Main skill definition
│           ├── README.md        # Documentation
│           └── references/      # Frameworks & templates
└── [your project files]
```

</details>

<details>
<summary><strong>🔍 Verify Installation</strong></summary>

**Check 1: Files exist**
```bash
ls .claude/skills/jp-consulting/
# Should show: SKILL.md, README.md, references/
```

**Check 2: Test in Claude**
```
You: /jp-consulting
Claude: [Should show skill activation message]
```

**Check 3: Try a real scenario**
```
You: "I want to develop a cloud migration strategy"
Claude: [Should recognize and activate skill]
```

</details>

<details>
<summary><strong>❓ Troubleshooting</strong></summary>

**Skills not recognized?**
- ✅ Check `.claude/skills/` directory exists
- ✅ Restart VS Code
- ✅ Try direct invocation: `/jp-consulting`
- ✅ Verify SKILL.md has correct frontmatter

**Claude not available?**
- ✅ Update GitHub Copilot extension
- ✅ Check model selector in Copilot settings
- ✅ Ensure Copilot subscription is active
- ✅ Try signing out/in from GitHub

**Japanese text issues?**
- ✅ Set encoding to UTF-8 in VS Code settings
- ✅ Install Japanese language pack
- ✅ Use UTF-8 file encoding for outputs

</details>

---

## 💻 Quick Start with VS Code

### Step-by-Step VS Code Setup

#### 1️⃣ Install VS Code Extension

**GitHub Copilot**
```bash
# Install via VS Code marketplace
code --install-extension GitHub.copilot
```

Or install manually:
1. Open VS Code
2. Press `Ctrl+Shift+X` / `Cmd+Shift+X` (Extensions)
3. Search "GitHub Copilot"
4. Click Install

#### 2️⃣ Configure Claude Model

1. Open VS Code Settings (`Ctrl+,` / `Cmd+,`)
2. Search: **"Copilot Chat Model"**
3. Select: `claude-3.5-sonnet` or `claude-sonnet-4.5`
4. Restart VS Code

#### 3️⃣ Install Skills

**In VS Code Terminal** (`Ctrl+\`` / `Cmd+\``):

```bash
# Create skills directory
mkdir -p .claude/skills

# Install this skill collection
npx skills add <your-github-username>/awesome-claude-skills
```

#### 4️⃣ Verify Installation

**Check in File Explorer:**
- Press `Ctrl+Shift+E` / `Cmd+Shift+E`
- Navigate to `.claude/skills/jp-consulting-output/`
- Confirm files exist: `SKILL.md`, `README.md`, `references/`

**Test in Copilot Chat:**
- Press `Ctrl+Shift+I` / `Cmd+Shift+I` to open Copilot Chat
- Type: `/jp-consulting-output`
- Claude should respond with skill activation

#### 5️⃣ Start Using

**Open Copilot Chat** and try:
```
"I want to develop a market entry strategy"
```

**Pro Tips for VS Code:**
- 📌 **Pin Chat Panel**: Drag chat to side for split view
- 🔄 **Use @workspace**: Give Claude project context
- 💾 **Save Outputs**: Ask Claude to save reports to specific folders
- ⌨️ **Keyboard Shortcuts**:
  - `Ctrl+Shift+I` / `Cmd+Shift+I` - Open/Close Chat
  - `Ctrl+L` / `Cmd+L` - Clear chat
  - `Ctrl+\`` / `Cmd+\`` - Toggle terminal

#### 🔧 VS Code-Specific Troubleshooting

<details>
<summary>Extension not working?</summary>

1. Update GitHub Copilot to latest version
2. Check GitHub authentication: `Copilot: Sign in to GitHub`
3. Verify subscription is active
4. Reload VS Code window: `Developer: Reload Window`
</details>

<details>
<summary>Skills folder not found?</summary>

```bash
# Check current directory
pwd

# Create from project root
cd /path/to/your/project
mkdir -p .claude/skills

# Verify
ls -la .claude/skills
```
</details>

<details>
<summary>Claude model not available?</summary>

1. Ensure Copilot subscription includes Claude access
2. Check for Copilot updates in Extensions panel
3. Try selecting different Claude model version
4. Contact GitHub support if still unavailable
</details>

---


## ✨ Key Features

### 🎯 Consulting Methodology Excellence

<table>
<tr>
<td width="50%">

**Issue-Driven Structuring**
- MECE principle application
- Hypothesis tree development
- Issue decomposition
- Priority setting

</td>
<td width="50%">

**Hypothesis-Driven Analysis**
- Framework selection
- Data collection & validation
- Insight generation
- Recommendation synthesis

</td>
</tr>
<tr>
<td>

**Data-Driven Insights**
- Integrated web search
- Market intelligence gathering
- Fermi estimation
- Quantitative analysis

</td>
<td>

**Slide-First Approach**
- Presentation-ready format
- Executive summary focus
- Visual structure
- Action-oriented output

</td>
</tr>
</table>

### 📊 Built-in Frameworks & Tools

**Business Analysis**
- 3C Analysis (Customer, Competitor, Company)
- SWOT Analysis
- Porter's Five Forces
- Value Chain Analysis
- Business Model Canvas
- PEST Analysis
- Ansoff Matrix
- BCG Matrix

**Technology Analysis**  
- Cloud Migration 6R Framework
- Zero Trust Architecture
- AI Readiness Assessment
- DevOps Maturity Model
- Digital Transformation Framework
- Cybersecurity Framework (NIST/ISO)
- Data Governance Framework

**Analytical Tools**
- Market sizing & estimation
- Fermi estimation
- Scenario planning
- Sensitivity analysis
- ROI calculation
- TCO analysis

### 📈 Progress Visualization

Real-time tracking of deliverable creation:

- ⚫ **Planning** - Scoping and structuring
- 📝 **In Progress** - Research and analysis
- ✅ **Completed** - Finalized sections

---

## 🌏 Language Support

| Skill | Language | Notes |
|-------|----------|-------|
| all-consulting | 🇬🇧 English | Designed for international business contexts and global consulting methodologies |
| jp-consulting | 🇯🇵 Japanese | Designed for Japanese business contexts and communication conventions |

**Future roadmap includes:**
- 🌏 Additional language versions
- 🌐 Regional adaptations

---

## 🤝 Contributing

We welcome contributions! Whether you want to:

- 🐛 **Report bugs** or issues
- 💡 **Suggest new skills** or improvements  
- 🔧 **Fix bugs** or enhance existing skills
- 📝 **Improve documentation**
- 🌐 **Add language support**

**[Read the full contributing guide →](CONTRIBUTING.md)**

### Quick Contribution Guide

1. **Fork** this repository
2. **Create** a feature branch (`git checkout -b feature/amazing-skill`)
3. **Commit** your changes (`git commit -m 'Add amazing skill'`)
4. **Push** to the branch (`git push origin feature/amazing-skill`)
5. **Open** a Pull Request

### Skill Contribution Checklist

- [ ] Follow the [skill structure](CONTRIBUTING.md#skill-structure)
- [ ] Include comprehensive `SKILL.md` with methodology
- [ ] Add user-friendly `README.md` documentation
- [ ] Provide usage examples
- [ ] Test with Claude Code
- [ ] Update main README skill table
- [ ] Add MIT license metadata

---

## 🗺️ Roadmap

### In Development
- [ ] English version
- [ ] Additional business frameworks
- [ ] More technology frameworks

### Planned Skills
- [ ] **Financial Modeling** - DCF, LBO, merger models, valuation
- [ ] **Data Analysis** - Statistical analysis, visualization, insights

### Language Expansion
- [ ] English consulting skills
- [ ] Multi-language framework

**Want to help?** Comment on [open issues](../../issues) or propose new skills!

---

## 📖 Learn More

### Resources

- **[Claude Code Documentation](https://docs.claude.ai/code)** - Official Claude Code guide
- **[Skills Specification](https://github.com/vercel-labs/skills)** - Skills format and structure
- **[SkillKit Documentation](https://github.com/rohitg00/skillkit)** - Multi-agent skill installer

### Related Projects

- **[Marketing Skills](https://github.com/coreyhaines31/marketingskills)** - Marketing-focused Claude skills
- **[Claude Skills Examples](https://github.com/anthropics/claude-code-skills)** - Official examples
- **[Awesome Claude](https://github.com/aaronwangy/awesome-claude)** - Curated Claude resources

---

## 📄 License

[MIT License](LICENSE) - Use freely in personal and commercial projects.

```
MIT License - Copyright (c) 2026 Awesome Claude Consulting Skills Contributors
```

---

## 🙏 Acknowledgments

- Inspired by professional consulting methodologies from McKinsey, BCG, Bain, and leading firms worldwide
- Built on the [Claude Code skills ecosystem](https://github.com/vercel-labs/skills)
- Special thanks to the AI agent community for innovation in agentic workflows
- Co-authored-by: Claude (Anthropic AI Assistant)

---

## 📬 Contact & Support

- **Issues**: [GitHub Issues](../../issues)
- **Discussions**: [GitHub Discussions](../../discussions)
- **Pull Requests**: Always welcome!

---

<div align="center">

**[⬆ Back to Top](#awesome-claude-consulting-skills)**

**If this helped you, consider giving it a ⭐**

</div>
