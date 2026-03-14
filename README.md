# nextlevelbuilder-ui-ux-pro-max-skill-Public
An AI SKILL that provide design intelligence for building professional UI/UX multiple platforms
+----------------------------------------------------------------------------------------+
|  TARGET: Serenity Spa - RECOMMENDED DESIGN SYSTEM                                      |
+----------------------------------------------------------------------------------------+
|                                                                                        |
|  PATTERN: Hero-Centric + Social Proof                                                  |
|     Conversion: Emotion-driven with trust elements                                     |
|     CTA: Above fold, repeated after testimonials                                       |
|     Sections:                                                                          |
|       1. Hero                                                                          |
|       2. Services                                                                      |
|       3. Testimonials                                                                  |
|       4. Booking                                                                       |
|       5. Contact                                                                       |
|                                                                                        |
|  STYLE: Soft UI Evolution                                                              |
|     Keywords: Soft shadows, subtle depth, calming, premium feel, organic shapes        |
|     Best For: Wellness, beauty, lifestyle brands, premium services                     |
|     Performance: Excellent | Accessibility: WCAG AA                                    |
|                                                                                        |
|  COLORS:                                                                               |
|     Primary:    #E8B4B8 (Soft Pink)                                                    |
|     Secondary:  #A8D5BA (Sage Green)                                                   |
|     CTA:        #D4AF37 (Gold)                                                         |
|     Background: #FFF5F5 (Warm White)                                                   |
|     Text:       #2D3436 (Charcoal)                                                     |
|     Notes: Calming palette with gold accents for luxury feel                           |
|                                                                                        |
|  TYPOGRAPHY: Cormorant Garamond / Montserrat                                           |
|     Mood: Elegant, calming, sophisticated                                              |
|     Best For: Luxury brands, wellness, beauty, editorial                               |
|     Google Fonts: https://fonts.google.com/share?selection.family=...                  |
|                                                                                        |
|  KEY EFFECTS:                                                                          |
|     Soft shadows + Smooth transitions (200-300ms) + Gentle hover states                |
|                                                                                        |
|  AVOID (Anti-patterns):                                                                |
|     Bright neon colors + Harsh animations + Dark mode + AI purple/pink gradients       |
|                                                                                        |
|  PRE-DELIVERY CHECKLIST:                                                               |
|     [ ] No emojis as icons (use SVG: Heroicons/Lucide)                                 |
|     [ ] cursor-pointer on all clickable elements                                       |
|     [ ] Hover states with smooth transitions (150-300ms)                               |
|     [ ] Light mode: text contrast 4.5:1 minimum                                        |
|     [ ] Focus states visible for keyboard nav                                          |
|     [ ] prefers-reduced-motion respected                                               |
|     [ ] Responsive: 375px, 768px, 1024px, 1440px                                       |
|                                                                                        |
+----------------------------------------------------------------------------------------+


┌─────────────────────────────────────────────────────────────────┐
│  1. USER REQUEST                                                │
│     "Build a landing page for my beauty spa"                    │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  2. MULTI-DOMAIN SEARCH (5 parallel searches)                   │
│     • Product type matching (161 categories)                    │
│     • Style recommendations (67 styles)                         │
│     • Color palette selection (161 palettes)                    │
│     • Landing page patterns (24 patterns)                       │
│     • Typography pairing (57 font combinations)                 │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  3. REASONING ENGINE                                            │
│     • Match product → UI category rules                         │
│     • Apply style priorities (BM25 ranking)                     │
│     • Filter anti-patterns for industry                         │
│     • Process decision rules (JSON conditions)                  │
└─────────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────────┐
│  4. COMPLETE DESIGN SYSTEM OUTPUT                               │
│     Pattern + Style + Colors + Typography + Effects             │
│     + Anti-patterns to avoid + Pre-delivery checklist           │
└─────────────────────────────────────────────────────────────────┘

Features
67 UI Styles - Glassmorphism, Claymorphism, Minimalism, Brutalism, Neumorphism, Bento Grid, Dark Mode, AI-Native UI, and more
161 Color Palettes - Industry-specific palettes aligned 1:1 with the 161 product types
57 Font Pairings - Curated typography combinations with Google Fonts imports
25 Chart Types - Recommendations for dashboards and analytics
13 Tech Stacks - React, Next.js, Astro, Vue, Nuxt.js, Nuxt UI, Svelte, SwiftUI, React Native, Flutter, HTML+Tailwind, shadcn/ui, Jetpack Compose
99 UX Guidelines - Best practices, anti-patterns, and accessibility rules
161 Reasoning Rules - Industry-specific design system generation (NEW in v2.0)
Available Styles (67)
General Styles (49)
Landing Page Styles (8)
BI/Analytics Dashboard Styles (10)
Installation
Using Claude Marketplace (Claude Code)
Install directly in Claude Code with two commands:

/plugin marketplace add nextlevelbuilder/ui-ux-pro-max-skill
/plugin install ui-ux-pro-max@ui-ux-pro-max-skill
Using CLI (Recommended)
# Install CLI globally
npm install -g uipro-cli

# Go to your project
cd /path/to/your/project

# Install for your AI assistant
uipro init --ai claude      # Claude Code
uipro init --ai cursor      # Cursor
uipro init --ai windsurf    # Windsurf
uipro init --ai antigravity # Antigravity
uipro init --ai copilot     # GitHub Copilot
uipro init --ai kiro        # Kiro
uipro init --ai codex       # Codex CLI
uipro init --ai qoder       # Qoder
uipro init --ai roocode     # Roo Code
uipro init --ai gemini      # Gemini CLI
uipro init --ai trae        # Trae
uipro init --ai opencode    # OpenCode
uipro init --ai continue    # Continue
uipro init --ai codebuddy   # CodeBuddy
uipro init --ai droid       # Droid (Factory)
uipro init --ai all         # All assistants
Other CLI Commands
uipro versions              # List available versions
uipro update                # Update to latest version
uipro init --offline        # Skip GitHub download, use bundled assets
Prerequisites
Python 3.x is required for the search script.

# Check if Python is installed
python3 --version

# macOS
brew install python3

# Ubuntu/Debian
sudo apt update && sudo apt install python3

# Windows
winget install Python.Python.3.12
Usage
Skill Mode (Auto-activate)
Supported: Claude Code, Cursor, Windsurf, Antigravity, Codex CLI, Continue, Gemini CLI, OpenCode, Qoder, CodeBuddy, Droid (Factory)

The skill activates automatically when you request UI/UX work. Just chat naturally:

Build a landing page for my SaaS product
Trae: Switch to SOLO mode first. The skill will activate for UI/UX requests.

Workflow Mode (Slash Command)
Supported: Kiro, GitHub Copilot, Roo Code

Use the slash command to invoke the skill:

/ui-ux-pro-max Build a landing page for my SaaS product
Example Prompts
Build a landing page for my SaaS product

Create a dashboard for healthcare analytics

Design a portfolio website with dark mode

Make a mobile app UI for e-commerce

Build a fintech banking app with dark theme
How It Works
You ask - Request any UI/UX task (build, design, create, implement, review, fix, improve)
Design System Generated - The AI automatically generates a complete design system using the reasoning engine
Smart recommendations - Based on your product type and requirements, it finds the best matching styles, colors, and typography
Code generation - Implements the UI with proper colors, fonts, spacing, and best practices
Pre-delivery checks - Validates against common UI/UX anti-patterns
Supported Stacks
The skill provides stack-specific guidelines for:

Category	Stacks
Web (HTML)	HTML + Tailwind (default)
React Ecosystem	React, Next.js, shadcn/ui
Vue Ecosystem	Vue, Nuxt.js, Nuxt UI
Other Web	Svelte, Astro
iOS	SwiftUI
Android	Jetpack Compose
Cross-Platform	React Native, Flutter
Just mention your preferred stack in the prompt, or let it default to HTML + Tailwind.

Design System Command (Advanced)
For direct access to the design system generator:

Note: If you installed via Continue, replace .claude/skills/ with .continue/skills/ in the commands below. For Droid (Factory), use .factory/skills/.

# Generate design system with ASCII output
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "beauty spa wellness" --design-system -p "Serenity Spa"

# Generate with Markdown output
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "fintech banking" --design-system -f markdown

# Domain-specific search
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "glassmorphism" --domain style
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "elegant serif" --domain typography
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "dashboard" --domain chart

# Stack-specific guidelines
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "form validation" --stack react
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "responsive layout" --stack html-tailwind
Persist Design System (Master + Overrides Pattern)
Save your design system to files for hierarchical retrieval across sessions:

# Generate and persist to design-system/MASTER.md
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp"

# Also create a page-specific override file
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "SaaS dashboard" --design-system --persist -p "MyApp" --page "dashboard"
This creates a design-system/ folder structure:

design-system/
├── MASTER.md           # Global Source of Truth (colors, typography, spacing, components)
└── pages/
    └── dashboard.md    # Page-specific overrides (only deviations from Master)
How hierarchical retrieval works:

When building a specific page (e.g., "Checkout"), first check design-system/pages/checkout.md
If the page file exists, its rules override the Master file
If not, use design-system/MASTER.md exclusively
Context-aware retrieval prompt:

I am building the [Page Name] page. Please read design-system/MASTER.md.
Also check if design-system/pages/[page-name].md exists.
If the page file exists, prioritize its rules.
If not, use the Master rules exclusively.
Now, generate the code...
Architecture & Contributing
For Users
The codebase has been restructured to use a template-based generation system. All platform-specific files (.cursor/, .windsurf/, .kiro/, .factory/, etc.) are now generated dynamically by the CLI.

Always use the CLI to install:

npm install -g uipro-cli
uipro init --ai <platform>
This ensures you get the latest templates and correct file structure for your AI assistant.

For Contributors
If you want to contribute to this project:

# 1. Clone the repository
git clone https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.git
cd ui-ux-pro-max-skill

# 2. Understand the structure
src/ui-ux-pro-max/           # Source of truth (data, scripts, templates)
cli/                         # CLI installer (generates files from templates)
.claude/                     # Local dev/test for Claude Code skill
.factory/                    # Local dev/test for Droid (Factory) skill

# 3. Make changes in src/ui-ux-pro-max/
# - data/*.csv              → Database files
# - scripts/*.py            → Search engine & design system
# - templates/              → Platform-specific templates

# 4. Sync to CLI and test locally
cp -r src/ui-ux-pro-max/data/* cli/assets/data/
cp -r src/ui-ux-pro-max/scripts/* cli/assets/scripts/
cp -r src/ui-ux-pro-max/templates/* cli/assets/templates/

# 5. Build and test CLI
cd cli && bun run build
node dist/index.js init --ai claude --offline  # Test in a temp folder

# 6. Create PR (never push directly to main)
git checkout -b feat/your-feature
git commit -m "feat: description"
git push -u origin feat/your-feature
gh pr create
See CLAUDE.md for detailed development guidelines.
