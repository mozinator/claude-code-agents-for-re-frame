# re-frame Agents for Claude Code & opencode.ai

12 specialized agents for comprehensive re-frame ClojureScript development, compatible with both Claude Code and opencode.ai platforms.

**[re-frame](https://day8.github.io/re-frame/re-frame/)** is a mature, functional ClojureScript framework for building modern web applications with reactive programming and data-oriented design.

## Platform Support

This agent collection supports both **Claude Code** and **opencode.ai** platforms:

- **Claude Code**: Original agents optimized for Claude Code workflows
- **opencode.ai**: Converted agents with mapped tools and configurations
- **Dual Compatibility**: Use the same agents across both platforms

## Available Agents

### Core Architecture Agents
- **[reframe-setup-specialist](/.claude/agents/reframe-setup-specialist.md)** - Project initialization, toolchain setup, and development environment configuration
- **[reframe-event-architect](/.claude/agents/reframe-event-architect.md)** - Event handling patterns, interceptors, and event flow architecture  
- **[reframe-subscription-expert](/.claude/agents/reframe-subscription-expert.md)** - Subscription optimization, query patterns, and reactive data flow
- **[reframe-effects-coordinator](/.claude/agents/reframe-effects-coordinator.md)** - Side effects, coeffects, and asynchronous operations management

### Development & Patterns Agents
- **[reframe-component-designer](/.claude/agents/reframe-component-designer.md)** - Reagent components, view patterns, and UI architecture
- **[reframe-state-modeler](/.claude/agents/reframe-state-modeler.md)** - App-db design, data normalization, and state architecture
- **[reframe-routing-navigator](/.claude/agents/reframe-routing-navigator.md)** - Client-side routing with Secretary, Reitit, and Bidi
- **[reframe-async-handler](/.claude/agents/reframe-async-handler.md)** - HTTP requests, WebSockets, timers, and async patterns

### Quality & Optimization Agents  
- **[reframe-testing-engineer](/.claude/agents/reframe-testing-engineer.md)** - Unit, integration, and e2e testing strategies
- **[reframe-performance-optimizer](/.claude/agents/reframe-performance-optimizer.md)** - Bundle optimization, runtime efficiency, and performance monitoring
- **[reframe-debugging-detective](/.claude/agents/reframe-debugging-detective.md)** - Dev tools, tracing, and systematic troubleshooting
- **[reframe-migration-guide](/.claude/agents/reframe-migration-guide.md)** - Legacy upgrades, version migrations, and modernization

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

Each agent follows Claude Code sub-agent conventions:
- **Focused Expertise**: Single-responsibility specialization
- **Comprehensive Background**: Deep re-frame knowledge and context
- **Practical Implementation**: Real-world patterns and best practices
- **Quality Focus**: Testing, debugging, and optimization guidance

## Installation

### For Claude Code
1. Copy the agent files from `.claude/agents/` to your project's `.claude/agents/` directory
2. Append the contents from `CLAUDE.md` to your project's `CLAUDE.md` file

### For opencode.ai
1. Copy the agent files from `.claude/agents/` to your project's `.opencode/agent/` directory
2. Run the conversion script: `node scripts/convert-claude-agents.js`
3. The script will generate opencode.ai compatible agents and update `AGENTS.md`

### Conversion Script
The included conversion script provides additional functionality:
- `node scripts/convert-claude-agents.js` - Convert all agents and generate AGENTS.md
- `node scripts/convert-claude-agents.js --test` - Test conversion with sample
- `node scripts/convert-claude-agents.js --validate` - Validate all converted agents
- `node scripts/convert-claude-agents.js --agents-md` - Generate AGENTS.md only

## Contributing

This is a comprehensive agent collection covering all aspects of re-frame development. The agents are designed to work independently or in combination to support complex ClojureScript application development workflows.

## Resources

- [re-frame Documentation](https://day8.github.io/re-frame/re-frame/)
- [ClojureScript](https://clojurescript.org/)
- [Reagent](https://reagent-project.github.io/)
- [Shadow CLJS](https://shadow-cljs.github.io/docs/UsersGuide.html)