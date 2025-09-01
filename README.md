# re-frame Agents for Claude Code

12 specialized Claude Code agents for comprehensive re-frame ClojureScript development.

## What is re-frame?

re-frame is a mature, functional ClojureScript framework for building modern web applications. It emphasizes "data and functions" over object-oriented patterns, using a reactive architecture where "data coordinates functions."

### Core Features
- **Reactive Programming**: Changes flow through the system automatically
- **Functional Design**: Pure functions for predictable, testable code
- **Data-Oriented Architecture**: Application state as immutable data structures
- **Six Dominoes Pattern**: Event dispatch → Event handling → Effect handling → Query → View → DOM
- **Unidirectional Data Flow**: Predictable state changes through events

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

1. Copy the agent files from `/.claude/agents/` to your project's `/.claude/agents/` directory
2. Append the contents from `CLAUDE.md` to your project's `CLAUDE.md` file

## Contributing

This is a comprehensive agent collection covering all aspects of re-frame development. The agents are designed to work independently or in combination to support complex ClojureScript application development workflows.

## Resources

- [re-frame Documentation](https://day8.github.io/re-frame/re-frame/)
- [ClojureScript](https://clojurescript.org/)
- [Reagent](https://reagent-project.github.io/)
- [Shadow CLJS](https://shadow-cljs.github.io/docs/UsersGuide.html)