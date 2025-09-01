# re-frame Agents for Claude Code & opencode.ai

12 specialized agents for comprehensive re-frame ClojureScript development.

**[re-frame](https://day8.github.io/re-frame/re-frame/)** is a mature, functional ClojureScript framework for building modern web applications with reactive programming and data-oriented design.

## Available Agents

### Core Architecture

- **reframe-effects-coordinator** - Agent for reframe effects coordinator
- **reframe-event-architect** - Agent for reframe event architect
- **reframe-setup-specialist** - Agent for reframe setup specialist

### Development & Patterns

- **reframe-async-handler** - Agent for reframe async handler
- **reframe-component-designer** - Agent for reframe component designer
- **reframe-routing-navigator** - Agent for reframe routing navigator
- **reframe-security-specialist** - Agent for reframe security specialist
- **reframe-state-modeler** - Agent for reframe state modeler
- **reframe-subscription-expert** - Agent for reframe subscription expert
- **reframe-ui-library-expert** - Agent for reframe ui library expert

### Quality & Optimization

- **reframe-debugging-detective** - Agent for reframe debugging detective
- **reframe-migration-guide** - Agent for reframe migration guide
- **reframe-performance-optimizer** - Agent for reframe performance optimizer
- **reframe-testing-engineer** - Agent for reframe testing engineer

## Usage

These agents work together to provide comprehensive re-frame development support, from initial project setup through advanced optimization and debugging.

### Getting Started
1. Use `reframe-setup-specialist` for new project initialization
2. Employ `reframe-event-architect` and `reframe-subscription-expert` for core application architecture
3. Leverage `reframe-component-designer` and `reframe-state-modeler` for UI and data patterns
4. Apply `reframe-testing-engineer` and `reframe-debugging-detective` for quality assurance

### Advanced Development
- Use `reframe-routing-navigator` for SPA navigation patterns
- Apply `reframe-async-handler` for complex async workflows
- Employ `reframe-performance-optimizer` for production optimization
- Use `reframe-migration-guide` for legacy system upgrades

## Agent Architecture

Each agent follows both Claude Code and opencode.ai sub-agent conventions:
- **Focused Expertise**: Single-responsibility specialization for specific re-frame development areas
- **Comprehensive Background**: Deep re-frame knowledge and ClojureScript context
- **Practical Implementation**: Real-world patterns and best practices
- **Quality Focus**: Testing, debugging, and optimization guidance

## Platform Support

### Claude Code
- Original agents in `.claude/agents/` directory
- Full Claude Code tool integration
- Optimized for Claude Code workflows

### opencode.ai
- Converted agents in `.opencode/agent/` directory
- Mapped tools and model configurations
- Compatible with opencode.ai specification

## Installation

### For Claude Code
1. Copy the agent files from `.claude/agents/` to your project's `.claude/agents/` directory
2. Append the contents from `CLAUDE.md` to your project's `CLAUDE.md` file

### For opencode.ai
1. Copy the agent files from `.claude/agents/` to your project's `.opencode/agent/` directory
2. Run the conversion script: `node scripts/convert-claude-agents.js`
3. The script will generate opencode.ai compatible agents and this AGENTS.md file

## Resources

- [re-frame Documentation](https://day8.github.io/re-frame/re-frame/)
- [ClojureScript](https://clojurescript.org/)
- [Reagent](https://reagent-project.github.io/)
- [Shadow CLJS](https://shadow-cljs.github.io/docs/UsersGuide.html)

---
