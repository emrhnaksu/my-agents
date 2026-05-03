# Data & ML Agents

Internal Copilot agent plugin for data engineering and ML optimization.

## Features

- **Data Engineer Agent** - Help design and optimize data pipelines
- **Spark Optimizer Skill** - Optimize Spark jobs for better performance

## Installation

### VSCode Copilot Chat

1. Open VSCode Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Run: `Chat: Install Plugin From Source`
3. Enter repository URL:
   ```
   https://github.com/emrhnaksu/my-agents
   ```

## Plugin Structure

```
my-agents/
├── plugin.json           # Plugin manifest
├── agents/
│   └── data-engineer.agent.md    # Data engineer role definition
└── skills/
    └── spark-optimizer/
        └── SKILL.md      # Spark optimization skill
```

## Agents

### Data Engineer
- **Role**: Senior data engineer
- **Task**: Help design and optimize data pipelines
- **Focus**: Practical solutions, concise recommendations

## Skills

### Spark Optimizer
- **Purpose**: Optimize Spark jobs
- **Input**: Spark code
- **Output**: Performance improvements and optimizations

## Development

To add new agents or skills:
1. Create a new `.agent.md` or `SKILL.md` file in respective directories
2. Follow the metadata format in existing files
3. Update `plugin.json` if needed

## License

MIT
