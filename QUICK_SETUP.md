# 🚀 Visionary Architects - Quick Setup

## Infrastructure Endpoints (Always Running)

### Local Services
```bash
http://localhost:8082        # MCP Tool Server (104 tools)
http://localhost:11434       # Ollama (64+ models)
http://localhost:3001        # AnythingLLM
http://localhost:3002        # MiniMax Multi-LLM
```

### Public Services
```bash
https://visionary-tool-server.ngrok.io  # MCP Public Endpoint
```

## Quick Start

### 1. Environment Setup
```bash
# Copy universal config
cp D:\DEV_PROJECTS\.env.universal.example .env

# Add your API keys from master
# Reference: D:\DEV_PROJECTS\.env.master
```

### 2. Verify Services
```bash
# Check MCP server
curl http://localhost:8082/health

# Check Ollama
ollama list

# Check GPU
nvidia-smi
```

### 3. Project Structure
```
D:\DEV_PROJECTS\
├── GitHub\                    # All 50 GitHub repos
├── dev_core\                  # Local projects
├── Obsidian Vault\            # Knowledge base
├── Visionary_Architects_OS\   # Main orchestrator
└── .env.master                # Master API keys (62+ services)
```

## MCP Tools Available (104)
- GitHub (13 tools)
- Discord (21 tools)
- Cloud AI (12 tools)
- Vector DBs (8 tools)
- Monitoring (7 tools)
- Automation (7 tools)
- Databases (8 tools)
- Plus agent orchestration, webhooks, shell commands

## Quick Commands
```powershell
# Start all services
cd D:\DEV_PROJECTS
.\START_CHATGPT_CONNECTOR.ps1

# System health check
.\HEALTH_CHECK_SYSTEM.ps1 -Mode Quick

# Deploy this project
.\DEPLOY_ORCHESTRATOR.ps1 -Phase Services
```

## Documentation
- **Master Context:** `D:\DEV_PROJECTS\VISIONARY_ARCHITECTS_MASTER_CONTEXT.md`
- **Agent System:** `D:\DEV_PROJECTS\AGENTS.md`
- **Boot Context:** `D:\DEV_PROJECTS\AGENT_BOOT_CONTEXT.md`

## Hardware
- **GPU:** RTX 4090 (16GB VRAM)
- **RAM:** 96GB
- **OS:** Windows 11
- **CUDA:** Enabled

## Organization
- **GitHub Org:** VisionaryArchitects
- **User:** visionaryarchitects
- **Repos:** 50 total

---

**For full documentation, see: VISIONARY_ARCHITECTS_MASTER_CONTEXT.md**
