# 🧠 Learn Claude — The Complete Mastery Roadmap 

> **A structured, end-to-end guide to mastering every Claude skill, service, tool, and API.**   
> From zero to production-grade AI engineering with Anthropic's Claude ecosystem.

<p align="center">
  <img src="https://img.shields.io/badge/Claude-Sonnet%204-orange?style=for-the-badge&logo=anthropic" />
  <img src="https://img.shields.io/badge/Level-Beginner%20→%20Expert-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge" />
</p>
 
---  
  
## 📖 Table of Contents 

- [Why This Roadmap](#-why-this-roadmap)
- [Claude Ecosystem Overview](#-claude-ecosystem-overview)
- [Phase 0 — Foundations](#-phase-0--foundations-week-1)
- [Phase 1 — Claude.ai Mastery](#-phase-1--claudeai-mastery-week-12)
- [Phase 2 — Prompt Engineering](#-phase-2--prompt-engineering-week-23)
- [Phase 3 — Claude API Fundamentals](#-phase-3--claude-api-fundamentals-week-34)
- [Phase 4 — Advanced API Patterns](#-phase-4--advanced-api-patterns-week-45)
- [Phase 5 — Tool Use & Function Calling](#-phase-5--tool-use--function-calling-week-56)
- [Phase 6 — Claude Code](#-phase-6--claude-code-week-67)
- [Phase 7 — Agents & Orchestration](#-phase-7--agents--orchestration-week-78)
- [Phase 8 — RAG with Claude](#-phase-8--rag-with-claude-week-910)
- [Phase 9 — Evals & Production](#-phase-9--evals--production-week-1112)
- [Phase 10 — Claude in Enterprise](#-phase-10--claude-in-enterprise-week-1213)
- [Resources & References](#-resources--references)
- [Contributing](#-contributing)

---

## 🎯 Why This Roadmap

Claude is not just a chatbot — it's a full-featured AI platform with:

- **Multiple interfaces**: Claude.ai, Claude Code, Claude API, Claude in Chrome/Excel/PowerPoint
- **Unique capabilities**: Extended thinking, computer use, tool use, multimodal reasoning
- **Enterprise-grade features**: Projects, Memory, Model Context Protocol (MCP), Batch API
- **A distinct model philosophy**: Constitutional AI, careful reasoning, and nuanced judgment

Most learners pick up Claude piecemeal. This roadmap gives you a **deliberate, compounding path** — each phase builds on the last, and you exit each phase with working artifacts you can show.

---

## 🗺️ Claude Ecosystem Overview

```
┌──────────────────────────────────────────────────────────────┐
│                     CLAUDE ECOSYSTEM                         │
├──────────────────┬───────────────────┬───────────────────────┤
│   INTERFACES     │      MODELS       │      CAPABILITIES     │
│                  │                   │                       │
│  claude.ai       │  Claude Opus 4    │  Multimodal           │
│  Claude Code     │  Claude Sonnet 4  │  Extended Thinking    │
│  Claude API      │  Claude Haiku 4   │  Tool / Function Use  │
│  Claude in Excel │                   │  Computer Use         │
│  Claude in PPT   │                   │  RAG / Memory         │
│  Claude in Chrome│                   │  MCP Integration      │
└──────────────────┴───────────────────┴───────────────────────┘
```

---

## ✅ Skill Progress Tracker

| Phase | Topic | Beginner | Intermediate | Advanced |
|-------|-------|----------|--------------|---------|
| 0 | Foundations | ⬜ | — | — |
| 1 | Claude.ai | ⬜ | ⬜ | — |
| 2 | Prompt Engineering | ⬜ | ⬜ | ⬜ |
| 3 | API Fundamentals | ⬜ | ⬜ | — |
| 4 | Advanced API | ⬜ | ⬜ | ⬜ |
| 5 | Tool Use | ⬜ | ⬜ | ⬜ |
| 6 | Claude Code | ⬜ | ⬜ | ⬜ |
| 7 | Agents | ⬜ | ⬜ | ⬜ |
| 8 | RAG | ⬜ | ⬜ | ⬜ |
| 9 | Evals & Prod | ⬜ | ⬜ | ⬜ |
| 10 | Enterprise | ⬜ | ⬜ | ⬜ |

> Copy and check off ✅ as you complete each level.

---

## 🟢 Phase 0 — Foundations (Week 1)

**Goal**: Understand the Claude landscape before writing a single line of code.

### Concepts to Master
- [ ] What is Anthropic? Constitutional AI explained
- [ ] Claude model family: Opus vs Sonnet vs Haiku — when to use each
- [ ] Claude's unique traits vs GPT-4 / Gemini (context window, reasoning, safety)
- [ ] The difference between Claude.ai (product) and Claude API (platform)
- [ ] Claude's knowledge cutoff and how to work around it
- [ ] Understanding tokens: input/output pricing, context windows

### Key Resources
- [Anthropic Model Docs](https://docs.claude.com/en/docs/about-claude/models/overview)
- [Claude's Character & Values](https://www.anthropic.com/claude)
- [Anthropic Research Blog](https://www.anthropic.com/research)

### Exit Criteria
> You can explain the Claude model lineup, pick the right model for a use case, and estimate token costs for a given task.

---

## 🔵 Phase 1 — Claude.ai Mastery (Week 1–2)

**Goal**: Squeeze maximum value from the Claude.ai interface before touching the API.

### Concepts to Master
- [ ] **Chat Interface**: Conversation management, branching, regeneration
- [ ] **Projects**: Creating project contexts, adding instructions, uploading docs
- [ ] **Memory**: How Claude remembers across conversations, managing memories
- [ ] **Artifacts**: Generating and iterating on code, docs, SVGs in-chat
- [ ] **Voice Mode**: Use cases for voice-driven workflows
- [ ] **File uploads**: PDFs, images, spreadsheets — what Claude can do with each
- [ ] **Web Search**: When it triggers, how to guide it
- [ ] **Deep Research**: Running multi-step research tasks
- [ ] **Plans**: Free vs Pro vs Team vs Enterprise differences
- [ ] **Styles**: Customizing Claude's tone and output style

### Skills to Build
- [ ] Set up a Project for a recurring task (e.g., coding assistant, writing editor)
- [ ] Build a Project with a system prompt + knowledge base documents
- [ ] Use Artifacts to generate a working React component, iterate on it

### Exit Criteria
> You have a working Claude Project with custom instructions and at least one uploaded knowledge document. You can use Artifacts to generate and refine code end-to-end.

---

## 🟡 Phase 2 — Prompt Engineering (Week 2–3)

**Goal**: Write prompts that consistently produce high-quality, structured outputs.

### Core Techniques
- [ ] **Zero-shot vs Few-shot prompting** — when each works best
- [ ] **Chain-of-thought (CoT)** — getting Claude to reason step by step
- [ ] **XML tags** — structuring inputs and outputs with `<tags>`
- [ ] **System prompts** — crafting effective personas and constraints
- [ ] **Role assignment** — expert roles and their effect on output quality
- [ ] **Output formatting** — JSON, Markdown, structured schemas
- [ ] **Negative prompting** — telling Claude what NOT to do
- [ ] **Temperature & top-p** — controlling creativity vs determinism
- [ ] **Prefilling** — starting Claude's response to steer it

### Advanced Techniques
- [ ] **Extended Thinking** — enabling deep reasoning with `thinking` blocks
- [ ] **Long context strategies** — working with 200K token windows
- [ ] **Prompt chaining** — breaking tasks into sequential prompts
- [ ] **Meta-prompting** — using Claude to write and improve its own prompts
- [ ] **Adversarial robustness** — making prompts resistant to injection

### Prompt Patterns Reference

```xml
<!-- Structured Output Pattern -->
<task>
  Analyze the following text and extract key entities.
  Return your response as valid JSON only, no markdown.
</task>

<text>
  {{USER_INPUT}}
</text>

<format>
{
  "entities": [...],
  "sentiment": "...",
  "summary": "..."
}
</format>
```

```python
# Few-shot pattern
SYSTEM = """You are a SQL expert. Format all queries consistently.

Examples:
User: get all users who signed up last week
SQL: SELECT * FROM users WHERE created_at >= NOW() - INTERVAL '7 days';

User: count orders by status
SQL: SELECT status, COUNT(*) as total FROM orders GROUP BY status;
"""
```

### Exit Criteria
> You can write a system prompt + user prompt combo that reliably returns structured JSON from Claude. You understand when to use extended thinking.

---

## 🟠 Phase 3 — Claude API Fundamentals (Week 3–4)

**Goal**: Make your first API calls and understand the full request/response lifecycle.

### Setup
```bash
pip install anthropic
export ANTHROPIC_API_KEY=sk-ant-...
```

### Concepts to Master
- [ ] **Authentication**: API keys, environment variables, key rotation
- [ ] **Basic Messages API**: `client.messages.create()`
- [ ] **Model selection**: Choosing the right model string
- [ ] **System + User messages**: Multi-turn conversation structure
- [ ] **Max tokens**: Setting output limits appropriately
- [ ] **Streaming**: Real-time token streaming with `stream=True`
- [ ] **Stop sequences**: Controlling where Claude stops
- [ ] **Response object**: Parsing `content`, `usage`, `stop_reason`

### Core SDK Patterns

```python
import anthropic

client = anthropic.Anthropic()

# Basic call
message = client.messages.create(
    model="claude-sonnet-4-5",
    max_tokens=1024,
    system="You are a helpful assistant.",
    messages=[
        {"role": "user", "content": "Explain transformers in 3 sentences."}
    ]
)
print(message.content[0].text)
```

```python
# Streaming
with client.messages.stream(
    model="claude-sonnet-4-5",
    max_tokens=1024,
    messages=[{"role": "user", "content": "Write a short story."}]
) as stream:
    for text in stream.text_stream:
        print(text, end="", flush=True)
```

```python
# Multi-turn conversation
messages = []

def chat(user_input):
    messages.append({"role": "user", "content": user_input})
    response = client.messages.create(
        model="claude-sonnet-4-5",
        max_tokens=1024,
        messages=messages
    )
    assistant_msg = response.content[0].text
    messages.append({"role": "assistant", "content": assistant_msg})
    return assistant_msg
```

### Exit Criteria
> You can build a multi-turn CLI chatbot with streaming output. You understand all fields in the API request and response.

---

## 🔴 Phase 4 — Advanced API Patterns (Week 4–5)

**Goal**: Master production-grade API usage patterns.

### Concepts to Master
- [ ] **Extended Thinking API**: `thinking` parameter, budget tokens, thought blocks
- [ ] **Vision / Multimodal**: Sending images as base64 or URL
- [ ] **Document input**: PDFs, text files as message content
- [ ] **Message Batches API**: Processing thousands of prompts efficiently
- [ ] **Token counting**: Pre-flight token estimates before sending
- [ ] **Caching (Prompt Cache)**: `cache_control` for long system prompts
- [ ] **Rate limits**: Tiers, retry logic, exponential backoff
- [ ] **Error handling**: `APIStatusError`, `RateLimitError`, `APIConnectionError`

### Extended Thinking Example

```python
response = client.messages.create(
    model="claude-sonnet-4-5",
    max_tokens=16000,
    thinking={
        "type": "enabled",
        "budget_tokens": 10000
    },
    messages=[{
        "role": "user",
        "content": "Solve this step by step: If a train travels..."
    }]
)

for block in response.content:
    if block.type == "thinking":
        print("REASONING:", block.thinking)
    elif block.type == "text":
        print("ANSWER:", block.text)
```

### Vision Example

```python
import base64

with open("diagram.png", "rb") as f:
    image_data = base64.b64encode(f.read()).decode("utf-8")

response = client.messages.create(
    model="claude-sonnet-4-5",
    max_tokens=1024,
    messages=[{
        "role": "user",
        "content": [
            {
                "type": "image",
                "source": {
                    "type": "base64",
                    "media_type": "image/png",
                    "data": image_data
                }
            },
            {"type": "text", "text": "Describe this architecture diagram."}
        ]
    }]
)
```

### Prompt Caching Example

```python
response = client.messages.create(
    model="claude-sonnet-4-5",
    max_tokens=1024,
    system=[
        {
            "type": "text",
            "text": "<your_long_system_prompt_here>",  # 2000+ tokens
            "cache_control": {"type": "ephemeral"}
        }
    ],
    messages=[{"role": "user", "content": "Question about the doc above"}]
)
```

### Exit Criteria
> You can send multimodal requests, use extended thinking, implement prompt caching, and handle rate limits with proper retry logic.

---

## 🟣 Phase 5 — Tool Use & Function Calling (Week 5–6)

**Goal**: Build Claude-powered systems that interact with external APIs and data.

### Concepts to Master
- [ ] **Tool definition schema**: JSON Schema for tool parameters
- [ ] **Tool use flow**: The full request → tool call → result → response loop
- [ ] **Parallel tool use**: Multiple tools called in one response
- [ ] **Forced tool use**: `tool_choice` to require specific tools
- [ ] **Error handling in tools**: What to return when a tool fails
- [ ] **Computer Use (beta)**: Letting Claude control a browser/desktop

### Tool Use Flow

```
User Message
    ↓
Claude Response (tool_use block)
    ↓
Your Code Executes the Tool
    ↓
tool_result sent back to Claude
    ↓
Claude Final Response (text)
```

### Implementation Pattern

```python
tools = [
    {
        "name": "get_weather",
        "description": "Get current weather for a city.",
        "input_schema": {
            "type": "object",
            "properties": {
                "city": {"type": "string", "description": "City name"},
                "unit": {"type": "string", "enum": ["celsius", "fahrenheit"]}
            },
            "required": ["city"]
        }
    }
]

def run_tool_loop(user_message):
    messages = [{"role": "user", "content": user_message}]
    
    while True:
        response = client.messages.create(
            model="claude-sonnet-4-5",
            max_tokens=1024,
            tools=tools,
            messages=messages
        )
        
        if response.stop_reason == "end_turn":
            return response.content[0].text
        
        # Process tool calls
        tool_results = []
        for block in response.content:
            if block.type == "tool_use":
                result = execute_tool(block.name, block.input)
                tool_results.append({
                    "type": "tool_result",
                    "tool_use_id": block.id,
                    "content": str(result)
                })
        
        # Continue the conversation
        messages.append({"role": "assistant", "content": response.content})
        messages.append({"role": "user", "content": tool_results})
```

### Model Context Protocol (MCP)

MCP is Claude's standardized protocol for connecting to external tools and data sources.

- [ ] **MCP Architecture**: Server, Client, Transport layers
- [ ] **Built-in MCP Servers**: Filesystem, GitHub, Slack, Google Drive
- [ ] **Writing a Custom MCP Server**: Tools, Resources, Prompts primitives
- [ ] **MCP in Claude Code**: Using `--mcp-config` flag
- [ ] **MCP in the API**: `mcp_servers` parameter for Artifacts

```python
# MCP server config (claude_mcp_config.json)
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/dir"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {"GITHUB_TOKEN": "ghp_..."}
    }
  }
}
```

### Exit Criteria
> You've built a working agentic loop with at least 3 tools (e.g., web search, file read, API call). You can write and register a custom MCP server.

---

## ⚫ Phase 6 — Claude Code (Week 6–7)

**Goal**: Use Claude Code as an autonomous coding agent in your development workflow.

### Setup
```bash
npm install -g @anthropic-ai/claude-code
claude  # Launch in current directory
```

### Concepts to Master
- [ ] **CLI Usage**: Basic commands, slash commands, flags
- [ ] **CLAUDE.md**: Writing effective repo instructions for Claude Code
- [ ] **Context management**: What gets included, how to guide it
- [ ] **Agentic coding tasks**: Feature implementation, debugging, refactoring
- [ ] **MCP with Claude Code**: Connecting external tools via `--mcp-config`
- [ ] **IDE Integration**: VS Code and JetBrains extensions
- [ ] **Headless mode**: `--print` flag for CI/CD automation
- [ ] **Permissions model**: What Claude Code can and cannot do
- [ ] **Multi-agent with Claude Code**: Orchestrator + subagent patterns

### Key Commands

```bash
# One-shot task
claude "add input validation to all API endpoints"

# Interactive session
claude

# With MCP servers
claude --mcp-config ./mcp_config.json

# Headless / CI mode
claude --print "Write unit tests for src/utils.py"

# Continue last session
claude --continue
```

### Writing CLAUDE.md

```markdown
# CLAUDE.md

## Project Overview
This is a FastAPI backend for a SaaS product.

## Code Standards
- Use type hints on all functions
- Follow PEP 8
- Tests go in /tests/ mirroring src structure

## Common Tasks
- To run tests: `pytest tests/`
- To start server: `uvicorn main:app --reload`

## Important Files
- `src/models.py` — all SQLAlchemy models
- `src/routes/` — all API route handlers
```

### Exit Criteria
> You can use Claude Code to implement a complete feature (endpoint + tests + docs) from a single natural language prompt. You have a working CLAUDE.md in at least one project.

---

## 🤖 Phase 7 — Agents & Orchestration (Week 7–8)

**Goal**: Build multi-step autonomous agents that can complete complex tasks.

### Concepts to Master
- [ ] **Agent architecture**: Planning, memory, tool use, reflection loops
- [ ] **Subagents pattern**: Orchestrator delegates to specialist Claude instances
- [ ] **ReAct pattern**: Reasoning + Acting interleaved
- [ ] **Memory strategies**: In-context, external (vector DB), summary compression
- [ ] **Long-running agents**: Checkpointing, human-in-the-loop interrupts
- [ ] **Agent safety**: Minimal footprint principle, permission scoping
- [ ] **Multi-agent coordination**: Claude spawning and directing other Claudes

### Minimal Agent Loop

```python
class ClaudeAgent:
    def __init__(self, tools, system_prompt):
        self.client = anthropic.Anthropic()
        self.tools = tools
        self.system = system_prompt
        self.messages = []
    
    def run(self, task: str, max_iterations: int = 10):
        self.messages.append({"role": "user", "content": task})
        
        for i in range(max_iterations):
            response = self.client.messages.create(
                model="claude-sonnet-4-5",
                max_tokens=4096,
                system=self.system,
                tools=self.tools,
                messages=self.messages
            )
            
            self.messages.append({"role": "assistant", "content": response.content})
            
            if response.stop_reason == "end_turn":
                return self._extract_final_answer(response)
            
            # Execute tools and feed results back
            tool_results = self._execute_tools(response.content)
            self.messages.append({"role": "user", "content": tool_results})
        
        return "Max iterations reached."
```

### Exit Criteria
> You've built an agent that can complete a multi-step research or coding task autonomously, with tool use, across at least 5 turns.

---

## 📚 Phase 8 — RAG with Claude (Week 9–10)

**Goal**: Build retrieval-augmented systems that ground Claude in your own data.

### Concepts to Master
- [ ] **Embedding models**: Choosing between Voyage AI (Anthropic's recommended), OpenAI, etc.
- [ ] **Vector databases**: Pinecone, Weaviate, ChromaDB, pgvector
- [ ] **Chunking strategies**: Fixed size, semantic, recursive, document-aware
- [ ] **Retrieval strategies**: Similarity search, MMR, hybrid (BM25 + semantic)
- [ ] **Contextual retrieval**: Anthropic's technique for prepending chunk context
- [ ] **Reranking**: Cross-encoder models to improve retrieved chunk quality
- [ ] **Citations**: Getting Claude to cite its sources accurately
- [ ] **Evaluation**: Faithfulness, relevance, context recall (RAGAS)

### Contextual Retrieval (Anthropic's Technique)

```python
# For each chunk, prepend document context using Claude
def contextualize_chunk(doc_text, chunk_text):
    response = client.messages.create(
        model="claude-haiku-4-5",
        max_tokens=150,
        messages=[{
            "role": "user",
            "content": f"""<document>
{doc_text}
</document>

<chunk>
{chunk_text}
</chunk>

Write a short 1-2 sentence context that situates this chunk within the document. 
Output only the context, nothing else."""
        }]
    )
    contextual_text = response.content[0].text
    return f"{contextual_text}\n\n{chunk_text}"
```

### RAG Query Pattern

```python
def rag_query(user_question, vector_db, top_k=5):
    # Retrieve
    chunks = vector_db.similarity_search(user_question, k=top_k)
    context = "\n\n---\n\n".join([c.page_content for c in chunks])
    
    # Generate
    response = client.messages.create(
        model="claude-sonnet-4-5",
        max_tokens=1024,
        system="Answer using only the provided context. If not in context, say so.",
        messages=[{
            "role": "user",
            "content": f"<context>\n{context}\n</context>\n\nQuestion: {user_question}"
        }]
    )
    return response.content[0].text
```

### Exit Criteria
> You've built a RAG pipeline over a document corpus with chunking, embedding, retrieval, and a Claude-powered answer generator. RAGAS score > 0.7.

---

## 🔬 Phase 9 — Evals & Production (Week 11–12)

**Goal**: Build evaluation systems and deploy Claude applications reliably.

### Concepts to Master

#### Evaluation
- [ ] **LLM-as-judge**: Using Claude to score Claude outputs
- [ ] **RAGAS framework**: Faithfulness, answer relevancy, context recall
- [ ] **PromptFoo**: Automated prompt testing and regression
- [ ] **Behavioral evals**: Red-teaming, adversarial testing
- [ ] **Regression tracking**: Detecting prompt quality changes over time
- [ ] **Human eval baselines**: Building golden datasets

#### Production Engineering
- [ ] **Structured outputs**: Enforcing JSON schemas reliably
- [ ] **Fallback chains**: Primary model → fallback model → graceful error
- [ ] **Caching layers**: Semantic cache with exact + fuzzy matching
- [ ] **Observability**: Logging prompts, responses, latency, token usage
- [ ] **Cost control**: Token budgeting, model routing by complexity
- [ ] **Load testing**: Concurrent request handling, rate limit management

### LLM-as-Judge Pattern

```python
def evaluate_response(question, context, answer):
    judge_prompt = f"""You are evaluating an AI answer for quality.

Question: {question}
Context: {context}
Answer: {answer}

Score the answer on these criteria (1-5 each):
1. Faithfulness: Is the answer grounded in the context?
2. Relevance: Does it address the question?
3. Completeness: Is anything important missing?

Return JSON only:
{{"faithfulness": N, "relevance": N, "completeness": N, "reasoning": "..."}}"""

    response = client.messages.create(
        model="claude-sonnet-4-5",
        max_tokens=512,
        messages=[{"role": "user", "content": judge_prompt}]
    )
    return json.loads(response.content[0].text)
```

### Exit Criteria
> You have an eval suite for a Claude application with at least 20 test cases, automated scoring, and a dashboard tracking quality over prompt iterations.

---

## 🏢 Phase 10 — Claude in Enterprise (Week 12–13)

**Goal**: Understand Claude's enterprise offerings and build for organizational scale.

### Concepts to Master
- [ ] **Claude for Work (Team/Enterprise)**: Differences from Pro
- [ ] **Admin controls**: SSO, user management, usage policies
- [ ] **Data privacy**: How prompts are handled, zero data retention options
- [ ] **Claude in Google Workspace**: Integration patterns
- [ ] **Claude in Microsoft 365**: Excel + PowerPoint plugins
- [ ] **Compliance**: SOC 2, HIPAA considerations
- [ ] **Fine-tuning considerations**: When to fine-tune vs prompt engineer
- [ ] **Workspaces & API keys**: Multi-team management
- [ ] **Usage analytics**: Monitoring org-wide Claude usage

### Claude Product Matrix

| Product | Use Case | Access |
|---------|----------|--------|
| Claude.ai Free | Personal exploration | claude.ai |
| Claude.ai Pro | Power users, heavy usage | claude.ai |
| Claude.ai Team | Small teams, collaboration | claude.ai |
| Claude.ai Enterprise | Large orgs, SSO, admin | claude.ai |
| Claude API | Developers, builders | api.anthropic.com |
| Claude Code | Software engineers | npm / IDE |
| Claude in Excel | Data analysts | Microsoft Store |
| Claude in PowerPoint | Presenters | Microsoft Store |
| Claude in Chrome | Browser automation | Chrome Store |

### Exit Criteria
> You can design a Claude deployment strategy for an organization, including model selection, cost estimation, access controls, and eval/monitoring plan.

---

## 📁 Suggested Repo Structure

```
learn-claude/
├── README.md                    ← You are here
├── phase-00-foundations/
│   └── notes.md
├── phase-01-claude-ai/
│   ├── project-setup.md
│   └── artifacts-demo/
├── phase-02-prompting/
│   ├── templates/
│   │   ├── structured-output.xml
│   │   ├── chain-of-thought.txt
│   │   └── few-shot.txt
│   └── exercises/
├── phase-03-api-basics/
│   ├── 01_basic_message.py
│   ├── 02_streaming.py
│   ├── 03_multi_turn.py
│   └── 04_vision.py
├── phase-04-advanced-api/
│   ├── 01_extended_thinking.py
│   ├── 02_prompt_caching.py
│   ├── 03_batch_api.py
│   └── 04_error_handling.py
├── phase-05-tool-use/
│   ├── 01_single_tool.py
│   ├── 02_tool_loop.py
│   ├── 03_parallel_tools.py
│   └── mcp/
│       ├── custom_server.py
│       └── mcp_config.json
├── phase-06-claude-code/
│   ├── CLAUDE.md
│   └── demo-project/
├── phase-07-agents/
│   ├── agent_loop.py
│   ├── react_agent.py
│   └── multi_agent.py
├── phase-08-rag/
│   ├── chunking.py
│   ├── contextual_retrieval.py
│   ├── rag_pipeline.py
│   └── evaluation/
├── phase-09-evals/
│   ├── llm_judge.py
│   ├── promptfoo_config.yaml
│   └── golden_dataset.json
└── phase-10-enterprise/
    └── deployment_guide.md
```

---

## 📚 Resources & References

### Official Docs
- [Claude Docs](https://docs.claude.com) — API reference, guides, models
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) — Official code examples
- [Claude Prompt Library](https://docs.claude.com/en/prompt-library/library) — Ready-to-use prompts
- [Prompt Engineering Guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview)
- [MCP Documentation](https://modelcontextprotocol.io/introduction)

### Community
- [Anthropic Discord](https://discord.gg/anthropic)
- [r/ClaudeAI](https://reddit.com/r/ClaudeAI)
- [Anthropic Forum](https://forum.anthropic.com)

### Recommended Papers
- [Constitutional AI (Anthropic, 2022)](https://arxiv.org/abs/2212.08073)
- [Model Card for Claude 3](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/claude-3-model-card.pdf)
- [Contextual Retrieval Blog Post](https://www.anthropic.com/news/contextual-retrieval)

---

## 🤝 Contributing

Pull requests are welcome! If you've built something interesting with Claude, have a better explanation for a concept, or found an error — please contribute.

1. Fork the repo
2. Create your branch: `git checkout -b feature/phase-X-improvement`
3. Commit your changes: `git commit -m 'Add extended thinking examples'`
4. Push to the branch: `git push origin feature/phase-X-improvement`
5. Open a Pull Request

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<p align="center">
  Built for the AI engineering community.<br>
  Star ⭐ if this helped you level up with Claude.
</p>
