# Claude Code Multi-Agent System - MANDATORY GLOBAL WORKFLOW

A sophisticated multi-agent system for Claude Code that provides intelligent development assistance with **mandatory workflow enforcement**, automatic agent delegation, and continuous learning capabilities.

## 🚨 NEW: MANDATORY GLOBAL WORKFLOW ENFORCEMENT

**This system now includes MANDATORY workflow enforcement that applies to EVERY interaction:**

- **Automatic Activation**: Workflow applies to all prompts without user request
- **Cannot Be Bypassed**: Works regardless of prompt content
- **Universal Application**: Active across ALL projects and sessions
- **Mandatory Delegation**: Control-agent MUST delegate, never execute directly
- **Hook-Based Enforcement**: Automatic injection of workflow context

## 🌟 Overview

This repository contains a complete multi-agent system designed to work globally with Claude Code across all your projects. The system includes specialized agents for different aspects of development, coordinated by a control agent, and continuously improved by a dual-layer improvement agent.

## 🤖 Agent Roster

### Core Agents

1. **Planning Agent** (Claude Opus 4)
   - Strategic project planning and task distribution
   - Multi-agent orchestration
   - Dependency management

2. **Control Agent**
   - Quality gate enforcement
   - Architecture compliance
   - >99% confidence requirement for all changes

3. **UX Agent**
   - User experience design
   - Wireframing and workflows
   - Accessibility compliance (WCAG 2.1 AA)

4. **UI Agent**
   - React/TypeScript implementation
   - Component development with >90% test coverage
   - Tailwind CSS styling

5. **Backend Agent**
   - State management (Zustand)
   - API development
   - Database operations

6. **Documentation Agent**
   - API documentation
   - Developer guides
   - Architecture documentation

7. **Version Control Agent**
   - Git operations
   - Branch management
   - Release coordination

### Meta Agent

8. **Improvement Agent** (Dual-Layer)
   - **Project Layer** (Claude Sonnet 4): Continuous observation during projects
   - **Meta Layer** (Claude Opus 4): Post-project deep analysis
   - Global learning across all projects

## 📁 Directory Structure

```
~/.claude/
├── agents/                 # Global agent configurations
│   ├── planning-agent.md
│   ├── control-agent.md
│   ├── ux-agent.md
│   ├── ui-agent.md
│   ├── backend-agent.md
│   ├── documentation-agent.md
│   ├── version-control-agent.md
│   └── improvement-agent.md
├── global-observation/     # Improvement agent's knowledge base
│   └── observation-ledger.json
├── ledgers/               # Agent task tracking
│   ├── planning-tasks.json
│   ├── control-tasks.json
│   └── ...
├── observation/           # Observation infrastructure
│   ├── activity-stream.json
│   ├── agent-hooks.md
│   └── ...
├── agent-protocols.md     # Communication protocols
└── task-registry.json     # Global task registry
```

## 🚀 Installation

### Prerequisites
- Claude Code installed
- Git
- Unix-like environment (macOS/Linux)

### Quick Install

1. Clone this repository:
```bash
git clone https://github.com/[your-username]/claude-code-agent-system.git
cd claude-code-agent-system
```

2. Run the installation script:
```bash
./install.sh
```

This will:
- Create necessary directories in `~/.claude/`
- Copy all agent configurations
- Set up the observation infrastructure
- Initialize the global observation ledger

### Manual Installation

If you prefer to install manually:

```bash
# Create directories
mkdir -p ~/.claude/{agents,global-observation,ledgers,observation}

# Copy agent configurations
cp agents/*.md ~/.claude/agents/

# Copy observation infrastructure
cp -r observation/* ~/.claude/observation/
cp -r ledgers/* ~/.claude/ledgers/

# Copy global files
cp task-registry.json ~/.claude/
cp agent-protocols.md ~/.claude/

# Initialize global observation ledger
cp global-observation/observation-ledger.json ~/.claude/global-observation/
```

## 🎯 Features

### 🚨 MANDATORY WORKFLOW ENFORCEMENT
- **Automatic Hook Injection**: Every prompt triggers workflow enforcement
- **Cannot Be Bypassed**: Applies regardless of user request
- **Control-Agent Delegation**: Automatic delegation to specialized agents
- **Universal Application**: Works across ALL projects and sessions
- **Memory Integration**: Persistent workflow awareness

### Continuous Learning
- Every project contributes to the global knowledge base
- Patterns emerge across multiple implementations
- Improvements are evidence-based and tested

### Multi-Agent Coordination
- Task distribution through ledger system
- Dependency tracking and management
- Quality gates at every stage
- **Mandatory reporting protocols** between agents

### Two-Layer Improvement System
- **Project Layer**: Silent observation during development
- **Meta Layer**: Deep analysis after project completion
- Cross-project pattern recognition
- Safe, tested improvements with user approval

### Global Availability
- Works across all Claude Code projects
- Persistent knowledge accumulation
- Shared learning between projects
- **Enforced consistency** across all environments

## 📊 How It Works

### Architecture Overview

The system operates with a **global + project-scoped** architecture:

#### 🌍 Global Level (Shared Across All Projects)
```bash
~/.claude/
├── agents/                    # Available in every project
│   ├── planning-agent.md     # Strategic planning
│   ├── control-agent.md      # Quality assurance  
│   ├── improvement-agent.md  # Continuous learning
│   └── ... (8 agents total)
├── global-observation/       # Cross-project learning
│   └── observation-ledger.json
└── ...
```

#### 📁 Project Level (Specific to Each Project)
```bash
/your-project/
├── .claude/
│   ├── settings.local.json   # Project-specific config
│   ├── ledgers/             # Task tracking for this project
│   └── project-data/        # Local observations
└── your-files...
```

### Workflow

1. **Install Once**: Agents become available in ALL Claude Code projects
2. **Auto-Activation**: Improvement Agent starts observing from first prompt
3. **Global Learning**: Every project contributes to shared knowledge base
4. **Cross-Project Benefits**: Patterns from Project A help Project B
5. **Continuous Evolution**: System gets smarter with each project

### Example Usage

```bash
# Install system
git clone https://github.com/emanuelgrammenos/claude-code-agent-system.git
cd claude-code-agent-system
./install.sh

# Now available everywhere
cd ~/my-react-app     # All 8 agents available
cd ~/my-python-app    # Same 8 agents available  
cd ~/any-project      # Consistent experience everywhere
```

### Learning Flow

- **Project A**: UI Agent learns React best practices
- **Project B**: UI Agent applies React knowledge to Vue project
- **Project C**: Benefits from both React and Vue experiences
- **Result**: Each project improves the entire system

## 🔧 Configuration

### Agent Permissions
Each agent has specific tool permissions defined in their YAML frontmatter:
- Planning Agent: Full access (`["*"]`)
- UX Agent: Read-only tools
- UI/Backend Agents: Development tools
- Control Agent: Full access for oversight

### Customization
You can customize agents by editing their configuration files in `~/.claude/agents/`. Each agent file contains:
- YAML frontmatter with name, description, and tools
- Detailed role description and competencies
- Specific workflows and standards

## 📈 Optimization Goals

The Improvement Agent optimizes for:
1. **Efficiency**: Faster task completion
2. **Quality**: Fewer errors and bugs
3. **Collaboration**: Better agent synchronization
4. **Code**: Cleaner, simpler implementations
5. **Architecture**: Better design patterns
6. **Testing**: Higher first-pass success
7. **Best Practices**: Latest frameworks and patterns

## 🔐 Security & Privacy

- All data stored locally in `~/.claude/`
- No external data transmission
- User approval required for all improvements
- Safe rollback procedures for all changes

## 🤝 Contributing

This is a personal configuration system, but feel free to:
- Fork for your own use
- Submit issues for bugs or suggestions
- Share improvements via pull requests

## 📝 License

MIT License - See LICENSE file for details

## 🙏 Acknowledgments

- Built for use with [Claude Code](https://claude.ai/code) by Anthropic
- Inspired by best practices in multi-agent systems
- Designed for continuous improvement and learning

---

**Note**: This system is designed to work with Claude Code and requires proper Claude Code installation and configuration.