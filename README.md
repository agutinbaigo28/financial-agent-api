<!-- AGENTS-META {"title":"AgentStack README","version":"1.0.43","applies_to":"/","last_updated":"2026-04-14","status":"stable"} -->

![Home Page v1.0.0](page-2026-04-15T07-04-23-082Z.png)

<!-- Core Project Badges -->

[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D20.9.0-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<!-- Stats Badges -->

[![Agents](https://img.shields.io/badge/Agents-25+-blue?logo=robot&logoColor=white)](src/mastra/agents)
[![Tools](https://img.shields.io/badge/Tools-57-orange?logo=hammer&logoColor=white)](src/mastra/tools)
[![Workflows](https://img.shields.io/badge/Workflows-10+-purple?logo=workflow&logoColor=white)](src/mastra/workflows)
[![Networks](https://img.shields.io/badge/Networks-12+-teal?logo=network-wired&logoColor=white)](src/mastra/networks)
[![UI Components](https://img.shields.io/badge/UI%20Components-105-pink?logo=react&logoColor=white)](ui/)

<!-- Quality Badges -->

[![Tests](https://img.shields.io/badge/Tests-97%25%20Coverage-brightgreen?logo=vitest&logoColor=white)](https://vitest.dev/)
[![Zod](https://img.shields.io/badge/Schema-Zod-3E67B1?logo=zod&logoColor=white)](https://zod.dev/)
[![ESLint](https://img.shields.io/badge/Lint-ESLint-4B32C3?logo=eslint&logoColor=white)](https://eslint.org/)

<!-- Repository Links -->

[![GitHub](https://img.shields.io/badge/GitHub-ssdeanx/AgentStack-181717?logo=github)](https://github.com/ssdeanx/AgentStack)
[![GitMCP](https://img.shields.io/endpoint?url=https://gitmcp.io/badge/ssdeanx/AgentStack)](https://gitmcp.io/ssdeanx/AgentStack)
[![wakatime](https://wakatime.com/badge/user/7a2fb9a0-188b-4568-887f-7645f9249e62/project/e52d02a1-f64a-4f8d-bc13-caaa2dc37461.svg)](https://wakatime.com/badge/user/7a2fb9a0-188b-4568-887f-7645f9249e62/project/e52d02a1-f64a-4f8d-bc13-caaa2dc37461)

**AgentStack** is a **production-grade AI agent platform** built on Mastra, delivering **57 enterprise tools**, **25+ specialized agents**, **10+ workflows**, **12+ supervisor networks**, **105 UI components** (50+ AI Elements + 55+ base), and **A2A/MCP orchestration** for scalable AI systems. Features **supervisor networks with delegation hooks**, **workspace management** (AgentFS/Daytona/Local), **TanStack Query integration**, and **LibSQL-backed persistence** for agents, workspaces, supervisor networks, and auth. Focuses on **financial intelligence**, **RAG pipelines**, **enterprise observability**, **secure governance**, and **AI chat interfaces**.

<!-- Mastra Ecosystem -->

[![@mastra/core](https://img.shields.io/npm/v/@mastra/core?label=@mastra/core&logo=npm)](https://www.npmjs.com/package/@mastra/core)
[![libSQL](https://img.shields.io/badge/Storage-libSQL-FFAB00?logo=sqlite&logoColor=white)](https://libsql.org/)
[![@mastra/rag](https://img.shields.io/npm/v/@mastra/rag?label=@mastra/rag&logo=npm)](https://www.npmjs.com/package/@mastra/rag)
[![@mastra/memory](https://img.shields.io/npm/v/@mastra/memory?label=@mastra/memory&logo=npm)](https://www.npmjs.com/package/@mastra/memory)
[![@mastra/ai-sdk](https://img.shields.io/npm/v/@mastra/ai-sdk?label=@mastra/ai-sdk&logo=npm)](https://www.npmjs.com/package/@mastra/ai-sdk)

<!-- AI/ML Stack -->

[![@ai-sdk/google](https://img.shields.io/npm/v/@ai-sdk/google?label=AI%20SDK%20Google&logo=google&logoColor=white)](https://www.npmjs.com/package/@ai-sdk/google)
[![@ai-sdk/react](https://img.shields.io/npm/v/@ai-sdk/react?label=AI%20SDK%20React&logo=react)](https://www.npmjs.com/package/@ai-sdk/react)
[![Langfuse](https://img.shields.io/badge/Observability-Langfuse-FF6B6B?logo=opentelemetry&logoColor=white)](https://langfuse.com/)
[![libSQL Vector Search](https://img.shields.io/badge/Vector-libSQL%20Search-FFAB00?logo=sqlite&logoColor=white)](https://libsql.org/)

<!-- LLM Providers -->

[![Gemini](https://img.shields.io/badge/LLM-Gemini%202.5-4285F4?logo=google&logoColor=white)](https://ai.google.dev/)
[![OpenAI](https://img.shields.io/badge/LLM-OpenAI-412991?logo=openai&logoColor=white)](https://openai.com/)
[![Anthropic](https://img.shields.io/badge/LLM-Claude-D4A373?logo=anthropic&logoColor=white)](https://anthropic.com/)

</div>

## 🎯 **Why AgentStack?**

AgentStack bridges the gap between basic AI chatbots and enterprise-grade multi-agent orchestration. While other AI agent platforms offer simple automation, AgentStack delivers the observability, security, and scalability required for production deployment.

| Feature                       | AgentStack                                                      | Fleece AI   | Botpress   | Vellum AI   |
| ----------------------------- | --------------------------------------------------------------- | ----------- | ---------- | ----------- |
| **Production Observability**  | ✅ **Real-time traces via TanStack + Langfuse ready**           | ⚠️ Basic    | ⚠️ Basic   | ✅ Partial  |
| **Dataset Management**        | ✅ **Full dataset/eval/experiment API with versioning**         | ❌ None     | ❌ None    | ⚠️ Basic    |
| **Supervisor Networks**       | ✅ **12+ coordinator agents with delegation hooks**             | ❌ None     | ❌ None    | ❌ None     |
| **Financial Intelligence**    | ✅ **Polygon/Finnhub/AlphaVantage (30+ endpoints)**             | ❌ None     | ❌ None    | ❌ None     |
| **RAG Pipeline**              | ✅ **LibSQL HNSW + rerank + graphRAG**                          | ⚠️ Basic    | ⚠️ Basic   | ✅ External |
| **Multi-Agent Orchestration** | ✅ **A2A MCP + supervisor networks (25+ agents)**               | ✅ Advanced | ✅ Basic   | ✅ Partial  |
| **Live Browser Automation**   | ✅ **Local Chrome/CDP browser agent + shared runtime**          | ⚠️ Basic    | ⚠️ Partial | ⚠️ Partial  |
| **Workspaces / Sandboxes**    | ✅ **AgentFS + Daytona + local sandboxes + persistence**        | ⚠️ Basic    | ❌ None    | ⚠️ Partial  |
| **Enterprise Security**       | ✅ **Better Auth + RBAC + path traversal protection + HTML sanitization** | ⚠️ Partial  | ⚠️ Partial | ✅ Partial  |
| **Type Safety**               | ✅ **Zod schemas everywhere (57 tools)**                        | ⚠️ Limited  | ⚠️ Limited | ✅ Partial  |
| **UI Components**             | ✅ **105 components (AI Elements + shadcn/ui)**                 | ✅ 30+      | ✅ 50+     | ✅ 30+      |
| **Testing**                   | ✅ **Vitest + 97% coverage + comprehensive mocks**              | ⚠️ Partial  | ⚠️ Partial | ✅ Partial  |

### 🚀 **Production-Ready from Day One**

While other AI agent platforms offer basic chatbot functionality, AgentStack provides enterprise-grade multi-agent orchestration:

- **Zero-config RAG**: LibSQL with 3072D embeddings works out of the box
- **Supervisor Networks**: 12+ coordinator agents with delegation hooks and scoring
- **Workspace Management**: AgentFS, Daytona, and local sandboxes with LSP support and LibSQL-backed persistence
- **Financial Intelligence**: Polygon, Finnhub, AlphaVantage with 30+ endpoints
- **Full Observability**: Every agent call, tool execution, and workflow step is traced
- **Enterprise Security**: Better Auth, RBAC, path validation, HTML sanitization, LibSQL session storage

## ✨ **Core Capabilities**

- **💰 Financial Intelligence**: 30+ tools (Polygon quotes/aggs/fundamentals, Finnhub analysis, AlphaVantage indicators)
- **🔍 Semantic RAG**: LibSQL (3072D embeddings) + MDocument chunking + rerank + graph traversal
- **📊 Dataset Management**: Full dataset API with versioning, experiments, and evaluation
- **🤖 25+ Agents**: Individual specialized agents (research, stock analysis, copywriting, etc.)
- **📋 10+ Workflows**: Multi-step orchestrated processes (weather analysis, content creation, financial reports)
- **🌐 12+ Supervisor Networks**: Coordinator agents that route tasks to specialized agents using delegation hooks (primary router, coding team, financial intelligence, content creation, etc.)
- **🧭 Live Browser Automation**: Shared Chrome/CDP browser runtime for local verification, screenshots, and interaction testing
- **🧩 Workspaces & Sandboxes**: AgentFS, Daytona, and local sandbox support with persistent LibSQL-backed state
- **🔌 A2A/MCP**: MCP server coordinates parallel agents (research+stock→report), A2A coordinator for cross-agent communication
- **🎨 105 UI Components**: AI Elements (50 chat/reasoning/canvas components) + shadcn/ui (55 base primitives)
- **📊 Enterprise Observability**: Default tracing + Langfuse integration + 10+ custom scorers + middleware logging
- **🛡️ Enterprise Security**: JWT auth, RBAC, path validation, HTML sanitization, secrets masking, middleware protection
- **⚡ Extensible**: Model registry (Gemini/OpenAI/Anthropic/OpenRouter), Zod schemas everywhere, MastraClient SDK integration

## ⚛️ **TanStack Query Integration**

Production-grade data fetching with comprehensive React hooks:

```typescript
// lib/hooks/use-mastra-query.ts - 1590+ lines of typed hooks
import { useAgentsQuery } from '@/lib/hooks/use-mastra-query'

export function AgentsDashboard() {
    const { data: agents, isLoading, error } = useAgentsQuery()

    // 15+ specialized hooks for agents, workflows, tools, memory, vectors
    // Automatic caching, background refetching, optimistic updates
    // Type-safe with Zod schemas throughout
}
```

**Key Features:**

- **1590+ Lines**: Comprehensive hook coverage for all Mastra APIs
- **Type Safety**: Full TypeScript with Zod schema validation
- **Caching**: Intelligent cache management with React Query
- **Real-time**: Automatic background updates and invalidation
- **DevTools**: Integrated with @tanstack/react-query-devtools

## 📊 **Dataset Management & Evaluation**

Complete dataset and evaluation pipeline with versioning and experiments:

```typescript
// lib/hooks/use-mastra-query.ts - Full dataset API
const { data: datasets } = useDatasets()
const { data: experiments } = useDatasetExperiments(datasetId)

// Dataset operations
const createDataset = useCreateDatasetMutation()
const addItems = useAddDatasetItemsMutation()
const runExperiment = useTriggerDatasetExperimentMutation()
```

**Features:**

- **Dataset Versioning**: Full history tracking and rollback capabilities
- **Experiment Management**: Compare model performance across datasets
- **Evaluation Scorers**: Custom scoring functions for quality assessment
- **Batch Operations**: Efficient bulk data operations
- **Type Safety**: Full TypeScript support with Zod validation

## 🔍 **Observability & Monitoring**

Enterprise-grade observability with easy Langfuse integration:

```typescript
// src/mastra/index.ts - Default observability setup
observability: new Observability({
  configs: {
    default: {
      sampling: { type: SamplingStrategyType.RATIO, probability: 0.75 },
      spanOutputProcessors: [new SensitiveDataFilter({...})],
      exporters: [new DefaultExporter({...})],
      // Easy Langfuse integration: uncomment and configure
      // exporters: [new LangfuseExporter({...})],
    }
  }
})
```

**Features:**

- **Default Tracing**: Built-in observability with no setup required
- **Real-time Trace Viewing**: View traces in real-time via TanStack Query hooks
- **Langfuse Ready**: Drop-in integration for advanced analytics and persistence
- **Custom Scorers**: 10+ evaluation metrics for agent performance
- **Sensitive Data Protection**: Automatic redaction of credentials
- **Performance Monitoring**: Latency, token usage, error tracking

**Real-time Trace Monitoring:**

```typescript
// View traces in real-time with TanStack hooks
const { data: traces } = useTraces({ limit: 10 })
const { data: trace } = useTrace(traceId)

// Monitor agent performance metrics
const { data: scores } = useScoresByRun({ runId })
```

## 🌐 **Middleware & Request Context**

AgentStack uses server-side Mastra middleware to populate request context for agents, tools, workflows, and supervisor routes. The frontend does not import these helpers directly.

```typescript
// src/mastra/index.ts - Middleware configuration
middleware: [
  async (c, next) => {
    const authHeader = c.req.header('Authorization') ?? ''
    const requestContext = c.get('requestContext')

    const authenticatedUser = await getAuthenticatedUser({
      mastra,
      token: authHeader.startsWith('Bearer ')
        ? authHeader.slice('Bearer '.length)
        : '',
      request: c.req.raw,
    })

    if (requestContext?.set) {
      requestContext.set('userId', authenticatedUser?.user.id)
      requestContext.set(
        'role',
        authenticatedUser?.user.role === 'admin' ? 'admin' : 'user'
      )
      requestContext.set('language', 'en')
      requestContext.set('provider-id', 'google')
      requestContext.set(
        'model-id',
        'gemini-3.1-flash-lite-preview'
      )
    }

    await next()
  },
]
```

**How it works:**

- **Server-only request context**: defined in `src/mastra/agents/request-context.ts`
- **Auth integration**: `src/mastra/auth.ts` stores Better Auth data in LibSQL
- **Role-based access**: `role` is either `admin` or `user`
- **Model overrides**: `provider-id` and `model-id` can be passed through request context
- **Workspace identity**: `workspaceId`, `threadId`, and `resourceId` are reserved for server-side routing and persistence
- **Localization**: language and region can still be inferred server-side
- **LibSQL fallback**: Turso URLs are optional; if missing, the app falls back to local `file:./database.db`

## 🔧 **Harness - Multi-Mode Agent Orchestration** (Alpha)

Advanced multi-mode agent orchestration with state persistence and workspace management:

```typescript
// src/mastra/harness.ts - 8 specialized agent modes
export const mainHarness = new Harness({
    id: 'agentstack-harness',
    resourceId: 'agentstack',
    storage: pgStore,
    workspace: mainWorkspace,

    modes: [
        { id: 'plan', name: 'Planner', agent: codeArchitectAgent },
        { id: 'code', name: 'Builder', agent: codeArchitectAgent },
        { id: 'review', name: 'Reviewer', agent: codeReviewerAgent },
        { id: 'test', name: 'Tester', agent: testEngineerAgent },
        { id: 'refactor', name: 'Refactorer', agent: refactoringAgent },
        { id: 'research', name: 'Researcher', agent: researchAgent },
        { id: 'edit', name: 'Editor', agent: editorAgent },
        { id: 'report', name: 'Reporter', agent: reportAgent },
    ],
})
```

**Available Modes:**

- **🏗️ Plan**: Architecture and planning (codeArchitectAgent)
- **💻 Code**: Implementation and coding (codeArchitectAgent)
- **🔍 Review**: Code review and quality assessment (codeReviewerAgent)
- **🧪 Test**: Test generation and validation (testEngineerAgent)
- **🔄 Refactor**: Code refactoring and optimization (refactoringAgent)
- **🔬 Research**: Research and information gathering (researchAgent)
- **✏️ Edit**: Content editing and refinement (editorAgent)
- **📊 Report**: Report generation and synthesis (reportAgent)

**Key Features:**

- **State Persistence**: Thread management with LibSQL storage
- **Workspace Integration**: Full filesystem and sandbox access
- **Mode Switching**: Dynamic agent mode transitions
- **Tool Approvals**: Security controls for sensitive operations
- **Event Streaming**: Real-time progress and result streaming

**Usage (Alpha):**

```typescript
// Switch to planning mode
await harness.switchMode('plan')
await harness.execute('Design a new authentication system')

// Switch to implementation mode
await harness.switchMode('code')
await harness.execute('Implement the auth system using JWT')

// Switch to testing mode
await harness.switchMode('test')
await harness.execute('Generate comprehensive tests for auth')
```

**⚠️ Alpha Status**: The harness is currently in active development. APIs may change without notice.

## 🏗️ **Workspace Management**

Multi-provider workspace system with LSP support:

```typescript
// src/mastra/workspaces.ts - 14 workspace variants
export const workspaceVariants = {
    mainWorkspace, // Local filesystem + sandbox
    agentFsWorkspace, // AgentFS integration
    daytonaWorkspace, // Daytona cloud sandboxes
    localReadOnlyWorkspace, // Read-only operations
    localApprovalWorkspace, // Manual approval required
    localLspWorkspace, // TypeScript/ESLint LSP
    // ... 8 more variants
}
```

**Providers:**

- **Local**: Filesystem and sandbox with process management
- **AgentFS**: Distributed filesystem with persistence
- **Daytona**: Cloud-based development environments
- **LSP**: TypeScript and ESLint language server integration
- **Approval**: Security-controlled operations

**Features:**

- **Process Management**: Spawn, kill, and monitor workspace processes
- **LSP Integration**: Real-time TypeScript/ESLint diagnostics
- **Security Controls**: Path validation and approval workflows
- **Multi-tenant**: Isolated workspaces with proper boundaries

## 🌟 **Feature Highlights**

### 💰 **Financial Intelligence Suite**

Real-time market data from 30+ endpoints:

```typescript
// Example: Multi-source stock analysis
const analysis = await stockAnalysisAgent.execute({
    symbol: 'AAPL',
    includeFundamentals: true,
    includeNews: true,
    timeRange: '1Y',
})
// → Combines Polygon quotes, Finnhub analysis, AlphaVantage indicators
// → Returns: Price action, valuation metrics, sentiment analysis
```

**Supported Data Providers:**

- **Polygon.io**: Real-time quotes, historical aggregates, fundamentals
- **Finnhub**: Company profiles, insider transactions, earnings surprises
- **Alpha Vantage**: Technical indicators (RSI, MACD, Bollinger Bands)

### 🔍 **Production RAG Pipeline**

Zero-config semantic search with libSQL:

```typescript
// 1. Index documents
await documentProcessingWorkflow.execute({
    documents: ['./annual-report.pdf', './market-data.csv'],
    chunkingStrategy: 'semantic',
    indexName: 'financial-reports',
})

// 2. Query with context
const answer = await governedRagAnswerWorkflow.execute({
    query: 'What were Q3 revenue drivers?',
    indexName: 'financial-reports',
    rerankTopK: 5,
})
// → Returns: Synthesized answer + source citations + confidence score
```

**Features:**

- **10 Chunking Strategies**: Semantic, recursive, markdown-aware
- **3072D Embeddings**: Gemini embedding-001
- **Hybrid Search**: Vector similarity + BM25 reranking
- **Graph Traversal**: Relationship-aware context expansion

### 🤖 **Agent Networks (Supervisor Agents)**

Supervisor agents that coordinate multiple specialized agents using delegation hooks:

```typescript
// Networks are supervisor agents that route tasks to specialized subagents
const result = await agentNetwork.execute({
    query: 'Analyze renewable energy market trends',
    // Uses delegation hooks to route to researchAgent, learningAgent, etc.
})
// → Supervisor agent analyzes request and delegates to appropriate subagents
// → Results synthesized into unified response
```

**Network Architecture:**

- **Supervisor Pattern**: Networks are supervisor agents, not parallel execution
- **Delegation Hooks**: Use `onDelegationStart`/`onDelegationComplete` for coordination
- **Scoring System**: Custom scorers ensure task completion and synthesis quality
- **Context Preservation**: Maintain conversation context across delegations

**Pre-configured Networks:**

- **Primary Network**: Routes to research, stock, weather, content, support agents
- **Coding Team Network**: Architecture → Code Review → Testing → Refactoring
- **Financial Intelligence Network**: Research → Analysis → Charts → Reports
- **Content Creation Network**: Writing → Editing → Strategy → SEO

### 📊 **Full Observability**

Every operation traced with Langfuse:

```typescript
// Traces automatically captured
const trace = await langfuse.getTrace(traceId)
// → Agent execution steps
// → Tool calls with latency
// → Token usage per step
// → Custom scorer results (quality, diversity, completeness)
```

**Dashboard Views:**

- Real-time trace visualization
- Performance metrics (latency, error rates)
- Cost tracking by agent/workflow
- Custom scorer analytics

### 🎨 **AI Elements UI Library**

50+ production-ready React components:

```tsx
import { AgentArtifact, AgentChainOfThought, AgentSources } from '@/ai-elements'

// Render streaming AI responses
<AgentChainOfThought
  steps={reasoningSteps}
  isStreaming={true}
  duration={1500}
/>

// Display code artifacts with syntax highlighting
<AgentArtifact
  artifact={{
    type: 'code',
    language: 'typescript',
    content: generatedCode
  }}
  onCodeUpdate={handleUpdate}
/>

// Show source citations
<AgentSources
  sources={citedSources}
  maxVisible={5}
/>
```

## 🚀 **What You Can Build**

Real-world applications powered by AgentStack:

### 📈 **Financial Analysis Platform**

```typescript
// Supervisor network coordinates specialized agents
const report = await financialIntelligenceNetwork.execute({
    symbol: 'TSLA',
    includeTechnicalAnalysis: true,
    includeNewsSentiment: true,
    generateCharts: true,
})
// → Supervisor network delegates to: researchAgent → stockAnalysisAgent → chartGeneratorAgent → reportAgent
// → Generates PDF report with charts and citations
```

**Features:**

- Real-time market data from multiple providers
- Automated technical analysis (RSI, MACD, Bollinger Bands)
- News sentiment analysis with SerpAPI
- Interactive chart generation
- PDF report export with source citations

### 📚 **Enterprise Knowledge Base**

```typescript
// Ingest and query company documents
await documentProcessingWorkflow.execute({
    source: 'https://company.com/docs',
    includeSubpages: true,
    chunkingStrategy: 'semantic',
    extractMetadata: true,
})

const answer = await knowledgeBaseAgent.execute({
    query: 'What is our refund policy?',
    includeSources: true,
    confidenceThreshold: 0.8,
})
// → Searches across all indexed documents
// → Returns answer with source URLs
```

**Features:**

- Web scraping with recursive crawling
- PDF/CSV/JSON document processing
- Semantic chunking with 10 strategies
- Hybrid search (vector + keyword)
- Source attribution for every answer

### 🤖 **AI Coding Assistant**

```typescript
// Supervisor network coordinates coding team
const result = await codingTeamNetwork.execute({
    task: 'Refactor authentication module',
    code: './src/auth/*',
    requirements: [
        'Improve security',
        'Add rate limiting',
        'Better error handling',
    ],
})
// → Supervisor network delegates: codeArchitectAgent → codeReviewerAgent → testEngineerAgent → refactoringAgent
// → Each agent handles specific aspect using delegation hooks
```

**Features:**

- Multi-agent code review pipeline
- Automatic test generation
- Security vulnerability detection
- TypeScript/React expertise
- GitHub integration for PR automation

### 📊 **Content Creation Studio**

```typescript
// Supervisor network orchestrates content pipeline
const content = await contentCreationNetwork.execute({
    topic: 'Sustainable investing trends',
    formats: ['blog', 'social', 'newsletter'],
    tone: 'professional',
    seoOptimize: true,
})
// → Supervisor network delegates: copywriterAgent → editorAgent → contentStrategistAgent → seoAgent
// → Each agent specializes in different aspect of content creation
```

**Features:**

- Multi-format content generation
- SEO optimization with keyword research
- Tone and style consistency
- Social media post generation
- Editorial calendar integration

### 🔍 **Research Synthesis Engine**

```typescript
// Supervisor network coordinates research pipeline
const research = await researchPipelineNetwork.execute({
    query: 'Latest advances in LLM safety',
    sources: ['arxiv', 'serpapi', 'web'],
    synthesizeFindings: true,
    generateReport: true,
})
// → Supervisor network delegates: researchAgent → documentProcessingAgent → knowledgeIndexingAgent → reportAgent
// → Research → Process → Index → Synthesize results
```

**Features:**

- ArXiv paper analysis
- Web scraping with content extraction
- Citation tracking and verification
- Consensus detection across sources
- Automated report generation

## 🏗️ **System Architecture**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22', 'fontFamily': 'JetBrains Mono, monospace' }}}%%
graph TB
    subgraph "🎨 Frontend Layer"
        direction TB
        UI[AI Elements Library<br/>• 50 Chat/Reasoning/Canvas Components<br/>• Real-time Streaming]
        Base[shadcn/ui Foundation<br/>• 55 Base Primitives<br/>• Accessible & Themable]
        App[Next.js 16 App Router<br/>• React 19 + Server Components<br/>• Tailwind CSS 4 + oklch]
        Query[TanStack Query<br/>• 1590+ Lines of Hooks<br/>• Type-Safe Data Fetching]
    end

    subgraph "🌐 External Interfaces"
        direction LR
        Client[MCP Clients<br/>Cursor / Claude / Windsurf]
        API[REST API<br/>OpenAPI + Typed SDK]
        SDK[MastraClient SDK<br/>Supervisor Agent Integration]
    end

    subgraph "⚡ AgentStack Runtime"
        direction TB
        Coord[A2A Coordinator<br/>Parallel Agent Orchestration]
        Supervisor[Supervisor Agents<br/>• Scoring & Delegation<br/>• Context-Aware Prompts]

        subgraph "Intelligent Agents"
            Agents[25+ Specialized Agents]
            Research[Research Suite]
            Financial[Financial Intelligence]
            Coding[Coding Team]
            Content[Content Creation]
        end

        subgraph "Tool Ecosystem"
            Tools[57 Enterprise Tools]
            APIs[Financial APIs<br/>Polygon / Finnhub / AlphaVantage]
            Search[Search & Research<br/>SerpAPI / ArXiv / Web Scraping]
            RAG[RAG Pipeline<br/>LibSQL + Embeddings]
        end

        subgraph "Workflow Engine"
            Workflows[10+ Multi-Step Workflows]
            Sequential[Sequential Execution]
            Parallel[Parallel Branches]
            Suspense[Suspend/Resume]
        end

        subgraph "Workspace Management"
            Workspaces[14 Workspace Variants<br/>• AgentFS • Daytona • Local]
            LSP[LSP Integration<br/>TypeScript • ESLint]
            Security[Security Controls<br/>Approval • Path Validation]
        end

        subgraph "Supervisor Networks"
            Networks[12+ Supervisor Networks]
            Routing[Delegation Hooks]
            Coordination[Subagent Orchestration]
        end
    end

    subgraph "🗄️ Data & Persistence Layer"
        direction TB
        VectorStore[(LibSQL<br/>3072D Embeddings<br/>HNSW/Flat Indexes)]
        Relational[(LibSQL<br/>Memory Threads<br/>Workflow State)]
        Cache[(Redis-ready<br/>Session Management)]
    end

    subgraph "📊 Observability Stack"
        direction LR
        Tracing[Langfuse Tracing<br/>100% Coverage]
        Metrics[Custom Scorers<br/>10+ Quality Metrics]
        Analytics[Performance Analytics<br/>Latency / Errors / Usage]
    end

    %% Connections
    UI --> App
    Base --> UI
    Query --> App
    App --> SDK
    SDK --> Coord

    Client --> Coord
    API --> Coord

    Coord --> Supervisor
    Supervisor --> Agents
    Coord --> Workflows
    Coord --> Networks

    Agents --> Tools
    Agents --> VectorStore
    Agents --> Relational
    Agents --> Workspaces

    Workflows --> Agents
    %% Networks (supervisors) delegate to subagents
    Networks --> Agents

    Tools --> VectorStore
    Tools --> Relational

    Workspaces --> LSP
    Workspaces --> Security

    Agents --> Tracing
    Workflows --> Tracing
    Networks --> Tracing
    Tools --> Tracing

    Tracing --> Metrics
    Tracing --> Analytics

    %% Styling
    classDef frontend fill:#1e3a5f,stroke:#58a6ff,stroke-width:3px,color:#fff
    classDef runtime fill:#2d4a22,stroke:#7ee787,stroke-width:3px,color:#fff
    classDef storage fill:#3d2817,stroke:#ffa657,stroke-width:3px,color:#fff
    classDef observe fill:#2a2a4a,stroke:#d2a8ff,stroke-width:3px,color:#fff
    classDef external fill:#3d3d3d,stroke:#8b949e,stroke-width:2px,color:#fff

    class UI,Base,App,Query frontend
    class Coord,Agents,Tools,Workflows,Networks,Research,Financial,Coding,Content,APIs,Search,RAG,Sequential,Parallel,Suspense,Routing,Coordination,Supervisor,Workspaces,LSP,Security runtime
    class VectorStore,Relational,Cache storage
    class Tracing,Metrics,Analytics observe
    class Client,API,SDK external
```

## 🔍 **Chat UI-Backend Architecture**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
sequenceDiagram
    participant UI as ChatUI
    participant Msg as MessageItem
    participant TG as TypeGuards
    participant ADS as AgentDataSection
    participant WDS as WorkflowDataSection
    participant NDS as NetworkDataSection
    participant AT as AgentTool

    UI->>Msg: render(message)
    Msg->>Msg: compute dataParts via useMemo

    loop for each part in dataParts
        Msg->>TG: isAgentDataPart(part)
        alt part is AgentDataPart
            Msg->>ADS: render part
            ADS-->>Msg: Agent execution collapsible
        else not AgentDataPart
            Msg->>TG: isWorkflowDataPart(part)
            alt part is WorkflowDataPart
                Msg->>WDS: render part
                WDS-->>Msg: Workflow execution collapsible
            else not WorkflowDataPart
                Msg->>TG: isNetworkDataPart(part)
                alt part is NetworkDataPart
                    Msg->>NDS: render part
                    NDS-->>Msg: Network execution collapsible
                else other data-tool-* part
                    alt part.type startsWith data-tool-
                        Msg->>AT: render custom tool UI
                        AT-->>Msg: Tool-specific panel
                    else generic data-* part
                        Msg-->>Msg: render generic Collapsible with JSON
                    end
                end
            end
        end
    end

    Msg-->>UI: message body with nested sections
```

## 📊 **System Flowchart**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
classDiagram
    direction LR

    class UIMessage {
      +string id
      +parts MastraDataPart[]
    }

    class MastraDataPart {
      +string type
      +string id
      +unknown data
    }

    class AgentDataPart {
      +string type
      +string id
      +AgentExecutionData data
    }

    class WorkflowDataPart {
      +string type
      +string id
      +WorkflowExecutionData data
    }

    class NetworkDataPart {
      +string type
      +string id
      +NetworkExecutionData data
    }

    class AgentExecutionData {
      +string text
      +unknown usage
      +toolResults unknown[]
    }

    class WorkflowExecutionData {
      +string name
      +string status
      +WorkflowStepMap steps
      +WorkflowOutput output
    }

    class NetworkExecutionData {
      +string name
      +string status
      +NetworkStep[] steps
      +NetworkUsage usage
      +unknown output
    }

    class WorkflowStepMap {
      <<map>>
      +string key
      +WorkflowStep value
    }

    class WorkflowStep {
      +string status
      +unknown input
      +unknown output
      +unknown suspendPayload
    }

    class NetworkStep {
      +string name
      +string status
      +unknown input
      +unknown output
    }

    class NetworkUsage {
      +number inputTokens
      +number outputTokens
      +number totalTokens
    }

    class MessageItem {
      +UIMessage message
      -MastraDataPart[] dataParts
      +render()
    }

    class AgentDataSection {
      +AgentDataPart part
      +render()
    }

    class WorkflowDataSection {
      +WorkflowDataPart part
      +render()
    }

    class NetworkDataSection {
      +NetworkDataPart part
      +render()
    }

    class AgentTool {
      +string id
      +string type
      +unknown data
      +render()
    }

    class TypeGuards {
      +bool hasStringType(unknown part)
      +bool isAgentDataPart(unknown part)
      +bool isWorkflowDataPart(unknown part)
      +bool isNetworkDataPart(unknown part)
    }

    class KeyHelpers {
      +string getToolCallId(unknown tool, number fallbackIndex)
    }

    UIMessage "1" o-- "*" MastraDataPart
    MastraDataPart <|-- AgentDataPart
    MastraDataPart <|-- WorkflowDataPart
    MastraDataPart <|-- NetworkDataPart

    MessageItem ..> MastraDataPart : filters dataParts
    MessageItem ..> AgentDataPart : uses when isAgentDataPart
    MessageItem ..> WorkflowDataPart : uses when isWorkflowDataPart
    MessageItem ..> NetworkDataPart : uses when isNetworkDataPart

    MessageItem --> AgentDataSection : renders nested agent
    MessageItem --> WorkflowDataSection : renders nested workflow
    MessageItem --> NetworkDataSection : renders nested network
    MessageItem --> AgentTool : renders other data-tool-* parts

    MessageItem ..> TypeGuards
    MessageItem ..> KeyHelpers

    AgentDataSection --> AgentExecutionData
    WorkflowDataSection --> WorkflowExecutionData
    NetworkDataSection --> NetworkExecutionData

    WorkflowExecutionData o-- WorkflowStepMap
    WorkflowStepMap o-- WorkflowStep
    NetworkExecutionData o-- NetworkStep
    NetworkExecutionData o-- NetworkUsage


    style UIMessage stroke:#64b5f6
    style MastraDataPart  stroke:#64b5f6
    style AgentDataPart stroke:#64b5f6
    style WorkflowDataPart stroke:#64b5f6
    style NetworkDataPart stroke:#64b5f6
    style AgentExecutionData stroke:#64b5f6
    style WorkflowExecutionData stroke:#64b5f6
    style NetworkExecutionData stroke:#64b5f6
    style MessageItem stroke:#64b5f6
    style TypeGuards stroke:#64b5f6
    style KeyHelpers stroke:#64b5f6
    style AgentDataSection stroke:#64b5f6
    style WorkflowDataSection stroke:#64b5f6
    style NetworkDataSection stroke:#64b5f6
    style AgentTool stroke:#64b5f6
    style NetworkUsage stroke:#64b5f6
    style NetworkStep stroke:#64b5f6
    style WorkflowStep stroke:#64b5f6
    style WorkflowStepMap stroke:#64b5f6
    style uses when stroke:#64b5f6
```

## 🔄 **RAG Pipeline (Production-Grade)**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
flowchart TB
    subgraph Indexing ["📥 Ingestion Pipeline"]
        A[Documents<br/>PDF/Web/MDX] --> B{MDocument<br/>Chunker}
        B -->|10 Strategies| C[Chunks +<br/>Metadata]
        C --> D[text-embedding-004<br/>3072D Vectors]
        D --> E[(LibSQL<br/>HNSW Index)]
    end

    subgraph Querying ["🔍 Retrieval Pipeline"]
        F[User Query] --> G[Query<br/>Embedding]
        G --> H{Vector<br/>Search}
        E -.->|Top-K| H
        H -->|Cosine Similarity| I[Candidates]
        I --> J[Rerank<br/>Cross-Encoder]
        J --> K[GraphRAG<br/>Relations]
        K --> L[Context<br/>Assembly]
    end

    subgraph Generation ["💬 Answer Pipeline"]
        L --> M[Supervisor Agent<br/>Scoring & Synthesis]
        M --> N[Generated<br/>Response]
        N --> O[Citations<br/>Verification]
        O --> P[Sources +<br/>Confidence Score]
    end

    subgraph Observability ["📊 Full Observability"]
        M -.->|Spans| Q[Langfuse<br/>Traces]
        E -.->|Usage| Q
        N -.->|Metrics| R[Custom Scorers<br/>10+ Metrics]
    end

    style A fill:#1a237e,color:#fff
    style B fill:#0d47a1,color:#fff
    style C fill:#1565c0,color:#fff
    style D fill:#1976d2,color:#fff
    style E fill:#2e7d32,color:#fff
    style F fill:#e65100,color:#fff
    style G fill:#ef6c00,color:#fff
    style H fill:#f57c00,color:#fff
    style I fill:#ff8f00,color:#fff
    style J fill:#ffa000,color:#000
    style K fill:#ffb300,color:#000
    style L fill:#4a148c,color:#fff
    style M fill:#6a1b9a,color:#fff
    style N fill:#8e24aa,color:#fff
    style O fill:#ab47bc,color:#fff
    style P fill:#ce93d8,color:#000
    style Q fill:#004d40,color:#fff
    style R fill:#00695c,color:#fff
```

## 🤝 **Flowcharts**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
sequenceDiagram
    actor User as User
    participant Assistant as Assistant_Message
    participant NetworkProvider as NetworkProvider
    participant WorkflowProvider as WorkflowProvider
    participant ProgressPanel as ProgressPanel

    User->>Assistant: Run network or workflow
    Assistant->>NetworkProvider: Stream messages with parts
    Assistant->>WorkflowProvider: Stream messages with parts

    loop For_each_assistant_message_in_network
        NetworkProvider->>NetworkProvider: Iterate parts with index partIndex
        NetworkProvider->>NetworkProvider: Build id using messageId_partType_partIndex
        NetworkProvider->>NetworkProvider: Append ProgressEvent to allProgressEvents
    end

    loop For_each_assistant_message_in_workflow
        WorkflowProvider->>WorkflowProvider: Iterate parts with index partIndex
        WorkflowProvider->>WorkflowProvider: Build id using messageId_partType_partIndex
        WorkflowProvider->>WorkflowProvider: Append ProgressEvent to allProgressEvents
    end

    NetworkProvider->>ProgressPanel: Provide progressEvents for network view
    WorkflowProvider->>ProgressPanel: Provide progressEvents for workflow view
    ProgressPanel->>User: Render grouped progress items with stable IDs
```

## 🚀 **Hooks** (5 Minutes to Production)

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
classDiagram
  class MastraQueryHooks {
    <<interface>>
    %% Core access
    +useAgents()
    +useAgent(agentId, requestContext)
    +useAgentModelProviders()
    +useAgentSpeakers(agentId, requestContext)
    +useAgentListener(agentId, requestContext)

    %% Tools and processors
    +useTools(requestContext)
    +useTool(toolId, requestContext)
    +useToolProviders()
    +useToolProvider(providerId)
    +useToolProviderToolkits(providerId)
    +useToolProviderTools(providerId, params)
    +useToolProviderToolSchema(providerId, toolSlug)
    +useProcessors(requestContext)
    +useProcessor(processorId, requestContext)
    +useProcessorProviders()
    +useProcessorProvider(providerId)
    +useProcessorExecuteMutation(processorId)

    %% Workflows and runs
    +useWorkflows(requestContext, partial)
    +useWorkflow(workflowId, requestContext)
    +useWorkflowRun(workflowId, runId, options)
    +useWorkflowRuns(workflowId, params, requestContext)
    +useWorkflowSchema(workflowId)
    +useWorkflowStartMutation(workflowId)
    +useWorkflowStartAsyncMutation(workflowId)
    +useWorkflowDeleteRunMutation(workflowId)
    +useWorkflowResumeMutation(workflowId)
    +useWorkflowResumeAsyncMutation(workflowId)
    +useWorkflowCancelMutation(workflowId)
    +useWorkflowRestartMutation(workflowId)
    +useWorkflowRestartAsyncMutation(workflowId)
    +useWorkflowTimeTravelMutation(workflowId)
    +useWorkflowTimeTravelAsyncMutation(workflowId)

    %% Memory and threads
    +useThreads(params)
    +useThread(threadId, agentId, requestContext)
    +useThreadMessages(threadId, opts)
    +useThreadMessagesPaginated(threadId, opts)
    +useWorkingMemory(params)
    +useMemorySearch(params)
    +useMemoryStatus(agentId, requestContext, opts)
    +useMemoryConfig(params)
    +useObservationalMemory(params)
    +useAwaitBufferStatus(params)
    +useCreateThreadMutation()
    +useDeleteThreadMutation()
    +useUpdateMemoryThreadMutation(threadId, agentId)
    +useUpdateWorkingMemoryMutation(agentId, threadId)
    +useSaveMessageToMemoryMutation()
    +useDeleteThreadMessagesMutation(threadId, agentId)
    +useCloneThreadMutation(threadId, agentId)

    %% Stored agents and versions
    +useStoredAgents(params)
    +useStoredAgent(id, requestContext, options)
    +useStoredAgentVersions(storedAgentId, params, requestContext)
    +useStoredAgentVersion(storedAgentId, versionId, requestContext)
    +useCompareStoredAgentVersions(storedAgentId, fromId, toId, requestContext)
    +useCreateStoredAgentMutation()
    +useUpdateStoredAgentMutation(storedAgentId)
    +useDeleteStoredAgentMutation(storedAgentId)
    +useCreateStoredAgentVersionMutation(storedAgentId)
    +useActivateStoredAgentVersionMutation(storedAgentId)
    +useRestoreStoredAgentVersionMutation(storedAgentId)
    +useDeleteStoredAgentVersionMutation(storedAgentId)

    %% Stored prompt blocks
    +useStoredPromptBlocks(params)
    +useStoredPromptBlock(id, requestContext, options)
    +useStoredPromptBlockVersions(storedPromptBlockId, params, requestContext)
    +useStoredPromptBlockVersion(storedPromptBlockId, versionId, requestContext)
    +useCompareStoredPromptBlockVersions(storedPromptBlockId, fromId, toId, requestContext)
    +useCreateStoredPromptBlockMutation()
    +useUpdateStoredPromptBlockMutation(storedPromptBlockId)
    +useDeleteStoredPromptBlockMutation(storedPromptBlockId)
    +useCreateStoredPromptBlockVersionMutation(storedPromptBlockId)
    +useActivateStoredPromptBlockVersionMutation(storedPromptBlockId)
    +useRestoreStoredPromptBlockVersionMutation(storedPromptBlockId)
    +useDeleteStoredPromptBlockVersionMutation(storedPromptBlockId)

    %% Stored scorers
    +useStoredScorers(params)
    +useStoredScorer(id, requestContext, options)
    +useStoredScorerVersions(storedScorerId, params, requestContext)
    +useStoredScorerVersion(storedScorerId, versionId, requestContext)
    +useCompareStoredScorerVersions(storedScorerId, fromId, toId, requestContext)
    +useCreateStoredScorerMutation()
    +useUpdateStoredScorerMutation(storedScorerId)
    +useDeleteStoredScorerMutation(storedScorerId)
    +useCreateStoredScorerVersionMutation(storedScorerId)
    +useActivateStoredScorerVersionMutation(storedScorerId)
    +useRestoreStoredScorerVersionMutation(storedScorerId)
    +useDeleteStoredScorerVersionMutation(storedScorerId)

    %% Stored MCP clients and skills
    +useStoredMcpClients(params)
    +useStoredMcpClient(id, requestContext)
    +useCreateStoredMcpClientMutation()
    +useUpdateStoredMcpClientMutation(storedMcpClientId)
    +useDeleteStoredMcpClientMutation(storedMcpClientId)
    +useStoredSkills(params)
    +useStoredSkill(id, requestContext)
    +useCreateStoredSkillMutation()
    +useUpdateStoredSkillMutation(storedSkillId)
    +useDeleteStoredSkillMutation(storedSkillId)

    %% Vectors and embedders
    +useVectorIndexes()
    +useVectorDetails(indexName)
    +useVectors()
    +useEmbedders()
    +useVectorQueryMutation(vectorName, indexName)
    +useVectorUpsertMutation(vectorName, indexName)

    %% Workspaces and skills
    +useWorkspaces()
    +useWorkspace(id)
    +useWorkspaceInfo(id)
    +useWorkspaceFiles(id, params)
    +useWorkspaceReadFile(id, path)
    +useWorkspaceSearch(id, params)
    +useWorkspaceSkills(id)
    +useWorkspaceSearchSkills(workspaceId, params)
    +useWorkspaceSkill(workspaceId, skillName)
    +useWorkspaceSkillReferences(workspaceId, skillName)
    +useWorkspaceSkillReference(workspaceId, skillName, referencePath)
    +useWorkspaceWriteFileMutation(workspaceId)
    +useWorkspaceDeleteMutation(workspaceId)
    +useWorkspaceMkdirMutation(workspaceId)
    +useWorkspaceRenameMutation(workspaceId)

    %% A2A and Agent Builder
    +useA2ASendMessageMutation(agentId)
    +useA2ASendStreamingMessageMutation(agentId)
    +useA2AGetTask(agentId, params)
    +useA2ACancelTaskMutation(agentId)
    +useAgentBuilderActions()
    +useAgentBuilderAction(actionId)
    +useAgentBuilderRuns(actionId, params)
    +useAgentBuilderRun(actionId, runId, options)
    +useAgentBuilderCreateRunMutation(actionId)
    +useAgentBuilderStartAsyncMutation(actionId)
    +useAgentBuilderStartRunMutation(actionId)
    +useAgentBuilderResumeMutation(actionId)
    +useAgentBuilderResumeAsyncMutation(actionId)
    +useAgentBuilderCancelRunMutation(actionId)
  }

  class MastraClient {
    +listTools(requestContext)
    +getTool(toolId)
    +listToolProviders()
    +getToolProvider(providerId)
    +listProcessors(requestContext)
    +getProcessor(processorId)
    +listStoredAgents(params)
    +getStoredAgent(id)
    +listStoredPromptBlocks(params)
    +getStoredPromptBlock(id)
    +listStoredScorers(params)
    +getStoredScorer(id)
    +listStoredMCPClients(params)
    +getStoredMCPClient(id)
    +listStoredSkills(params)
    +getStoredSkill(id)
    +listWorkflows(requestContext, partial)
    +getWorkflow(workflowId)
    +getWorkingMemory(params)
    +searchMemory(params)
    +getObservationalMemory(params)
    +awaitBufferStatus(params)
    +listVectors()
    +listEmbedders()
    +getWorkspace(id)
    +getA2A(agentId)
    +getAgentBuilderActions()
    +getAgentBuilderAction(actionId)
  }

  class ReactQueryClient {
    +useQuery(options)
    +useMutation(options)
    +invalidateQueries(options)
  }

  MastraQueryHooks ..> MastraClient : uses
  MastraQueryHooks ..> ReactQueryClient : uses
  MastraClient <|.. MastraClientStoredAgent
  class MastraClientStoredAgent {
    +details(requestContext, options)
    +listVersions(params, requestContext)
    +getVersion(versionId, requestContext)
    +compareVersions(fromId, toId, requestContext)
    +update(params)
    +delete(requestContext)
    +createVersion(params, requestContext)
    +activateVersion(versionId, requestContext)
    +restoreVersion(versionId, requestContext)
    +deleteVersion(versionId, requestContext)
  }

  MastraClient <|.. MastraClientWorkflow
  class MastraClientWorkflow {
    +details(requestContext)
    +runs(params, requestContext)
    +runById(runId, options)
    +getSchema()
    +createRun(params)
    +deleteRunById(runId)
  }

  MastraClient <|.. MastraClientProcessor
  class MastraClientProcessor {
    +details(requestContext)
    +execute(params)
  }

  MastraClient <|.. MastraClientAgentBuilderAction
  class MastraClientAgentBuilderAction {
    +details()
    +runs(params)
    +runById(runId, options)
    +createRun(params)
    +startAsync(params, runId)
    +startActionRun(params, runId)
    +resume(params, runId)
    +resumeAsync(params, runId)
    +cancelRun(runId)
  }

  MastraQueryHooks ..> MastraClientStoredAgent : stored agent hooks
  MastraQueryHooks ..> MastraClientWorkflow : workflow hooks
  MastraQueryHooks ..> MastraClientProcessor : processor hooks
  MastraQueryHooks ..> MastraClientAgentBuilderAction : agent builder hooks
```

### 1️⃣ Prerequisites

Before you begin, ensure you have:

| Requirement    | Version | Purpose              | Install                                                                                               |
| -------------- | ------- | -------------------- | ----------------------------------------------------------------------------------------------------- |
| **Node.js**    | ≥20.9.0 | Runtime              | [Download](https://nodejs.org/)                                                                       |
| **libSQL**     | -       | Primary persistence for auth, agents, workspaces, and supervisors | [Turso](https://turso.tech/) or local file fallback (`file:./database.db`) |
| **API Keys**   | -       | LLM & Tools          | See [Configuration](#configuration) below                                                          |

**One-liner for local libSQL:**

```bash
echo "TURSO_DATABASE_URL=file:./data/mastra.db" >> .env
```

### 2️⃣ Clone & Install

```bash
# Clone the repository
git clone https://github.com/ssdeanx/AgentStack.git
cd AgentStack

# Install dependencies (includes Mastra, Next.js, AI SDK)
npm install

# Verify installation
npm run typecheck  # Should pass with 0 errors
```

### 3️⃣ Configure Environment

```bash
# Copy the example environment file
cp .env.example .env

# Edit .env and add your API keys
# Minimum required for basic functionality:
# - GOOGLE_GENERATIVE_AI_API_KEY (for Gemini)
# - TURSO_DATABASE_URL (for libSQL)
```

**Quick .env setup:**

```bash
# Required - Get free API keys from Google AI Studio
echo "GOOGLE_GENERATIVE_AI_API_KEY=your-key-here" >> .env

# Database - libSQL
echo "TURSO_DATABASE_URL=file:./data/mastra.db" >> .env

# Optional - For enhanced tools
echo "SERPAPI_API_KEY=your-key" >> .env      # Search tools
echo "POLYGON_API_KEY=your-key" >> .env      # Financial data
echo "OPENAI_API_KEY=your-key" >> .env       # Alternative LLM
```

### 4️⃣ Start Development Server

```bash
# Single command starts both Mastra backend + Next.js frontend
npm run dev

# Services will be available at:
# - Frontend: http://localhost:3000
# - Mastra API: http://localhost:4111
# - MCP Server: http://localhost:6969/mcp (optional)
```

**Expected startup output:**

```bash
✓ Mastra Dev Server: http://localhost:4111
✓ Next.js Dev Server: http://localhost:3000
✓ 48 agents registered
✓ 60+ tools loaded
✓ 15 workflows ready
```

### 5️⃣ Verify & Start Building

Open your browser and navigate to:

| URL                               | What You'll See                       |
| --------------------------------- | ------------------------------------- |
| `http://localhost:3000`           | Landing page with agent overview      |
| `http://localhost:3000/chat`      | AI chat interface with 48+ agents     |
| `http://localhost:3000/dashboard` | Admin dashboard with traces & metrics |
| `http://localhost:3000/workflows` | Interactive workflow canvas           |

**Test your setup:**

```bash
# Run the test suite
npm test

# Should show: ✓ 100+ tests passed (97% coverage)
```

---

**🎉 You're ready!** Check out [Development](#development) to start building custom tools and agents.

### Next.js + Mastra Client SDK

The frontend uses `@mastra/client-js` with TanStack Query for robust state management:

```typescript
// lib/mastra-client.ts - Base client configuration
import { MastraClient } from '@mastra/client-js'

// lib/hooks/use-mastra-query.ts - 1590+ lines of TanStack Query hooks
import { useQuery } from '@tanstack/react-query'
import { mastraClient } from '@/lib/mastra-client'

// lib/types/ - Zod schemas and TypeScript types
import { z } from 'zod'
```

**Key Features:**

- **Type Safety**: All API responses validated with Zod schemas
- **Caching**: Centralized query keys for efficient cache management
- **Mutations**: useExecuteToolMutation, useCreateThreadMutation, useVectorQueryMutation
- **Real-time**: Automatic cache invalidation and refetch on mutations
- **Error Handling**: Built-in loading/error states

**Usage in client components:**

```typescript
"use client";
import { useAgents } from "@/lib/hooks/use-mastra-query";

export function AgentsList() {
  const { data: agents, isLoading, error } = useAgents();

  if (isLoading) return <div>Loading agents...</div>;
  if (error) return <div>Error: {error.message}</div>;

  return agents.map(agent => <AgentCard key={agent.id} agent={agent} />);
}
```

**Pages:**

- `/` - Landing page with agent overview
- `/test` - Server action demo (SSR)
- `/chat` - AI chat with 48+ agents using AI Elements and @ai-sdk/react
- `/networks` - Advanced agent network orchestration with routing
- `/workflows` - Interactive workflow canvas with 11+ workflows
- `/dashboard` - Admin dashboard with TanStack Query hooks for agents/tools/workflows/traces/memory/vectors
- `/tools` - Tool documentation and execution interface
- `/docs` - Comprehensive documentation (AI SDK, components, RAG, security, runtime context)
- `/api-reference` - OpenAPI schema and API documentation

**Shared Libraries:**

- `lib/mastra-client.ts` - MastraClient configuration for frontend
- `lib/hooks/` - TanStack Query hooks for data fetching (1590+ lines)
  - `use-mastra-query.ts` - Comprehensive hooks for agents, workflows, datasets, evaluation, and observability
- `lib/types/` - Zod schemas and TypeScript types (auto-generated)
- `lib/utils.ts` - Shared utilities (cn, formatDate, etc.)
- `lib/a2a.ts` - Agent-to-agent coordination utilities
- `lib/auth.ts` - Authentication utilities
- `src/mastra/auth.ts` - Better Auth + LibSQL server auth configuration
- `src/mastra/workspaces.ts` - Workspace, sandbox, AgentFS, and LibSQL-backed workspace storage
- `src/mastra/agents/request-context.ts` - Server-side request context schema and helpers
- `src/mastra/tools/request-context.utils.ts` - Tool-side request context helpers

### MCP Server (A2A)

```bash
npm run mcp-server  # http://localhost:6969/mcp
```

### Production

```bash
npm run build
npm run start
```

## ⚡ **Performance Metrics**

AgentStack is engineered for high-performance production workloads with comprehensive benchmarking and optimization:

### **System Benchmarks**

| Metric                    | Value        | Details                                    |
| ------------------------- | ------------ | ------------------------------------------ |
| **Cold Start**            | < 2s         | Agent initialization with 57 tools         |
| **Memory Usage**          | ~180MB       | Base runtime with 25+ agents loaded        |
| **Concurrent Agents**     | 25+          | Parallel execution via A2A networks        |
| **Supervisor Scoring**    | < 100ms      | Task completion & synthesis evaluation     |
| **Dataset Operations**    | < 50ms       | Batch insert/update operations             |
| **Vector Search**         | < 50ms       | LibSQL HNSW top-k retrieval                |
| **Embedding Generation**  | ~120ms       | text-embedding-004 (3072D)                 |
| **RAG End-to-End**        | < 300ms      | Chunk → Embed → Search → Supervisor Answer |
| **Workspace Operations**  | < 50ms       | AgentFS/Daytona filesystem operations      |
| **Middleware Processing** | < 10ms       | Request context population and validation  |
| **Test Suite**            | 97% coverage | 100+ tests, ~45s runtime                   |

### **Throughput Metrics**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
sequenceDiagram
  participant Dev as Developer
  participant Script as npm run chrome:debug
  participant Chrome as Local Chrome
  participant CDP as CDP Endpoint<br/>127.0.0.1:9222
  participant BrowserAgent as browserAgent
  participant Browser as Shared Browser Runtime
  participant App as Target Web App

  Dev->>Script: Start remote-debug Chrome
  Script->>Chrome: Launch Chrome with CDP enabled
  Chrome-->>CDP: Publish DevTools endpoint
  BrowserAgent->>CDP: Connect via CHROME_CDP_URL
  BrowserAgent->>Browser: Reuse shared browser session
  BrowserAgent->>App: Navigate, click, type, inspect
  App-->>BrowserAgent: DOM, console, screenshots
  BrowserAgent-->>Dev: Structured result
```

| Endpoint             | RPS | Avg Latency | Use Case                           |
| -------------------- | --- | ----------- | ---------------------------------- |
| `/api/chat`          | 150 | 180ms       | AI chat with supervisor agents     |
| `/api/workflow`      | 85  | 420ms       | Multi-step workflows               |
| `/api/rag/query`     | 200 | 95ms        | Vector similarity search           |
| `/api/dataset`       | 180 | 120ms       | Dataset operations and experiments |
| `/api/tools/execute` | 120 | 250ms       | Tool execution                     |
| `/api/observability` | 95  | 140ms       | Tracing and metrics retrieval      |
| `/api/network`       | 75  | 350ms       | Agent network orchestration        |
| `/api/workspace`     | 110 | 120ms       | Workspace file operations          |

### **Observability Performance**

```bash
# Tracing overhead: < 5% latency increase
# Memory per trace: ~2KB (compressed)
# Trace retention: 30 days default
# Scorer latency: < 20ms per evaluation
```

**Monitoring Dashboard:**

- Real-time latency percentiles (p50, p95, p99)
- Token usage tracking by agent/model
- Tool execution heatmaps
- Error rate trending
- Custom scorer distributions

### **Optimization Tips**

```typescript
// Enable connection pooling for libSQL-backed storage
export const libsqlStorage = new LibsqlStorage({
    poolSize: 20, // Default: 10
    maxOverflow: 5,
    connectionTimeout: 5000,
})

// Configure embedding batch size
const batchEmbed = async (texts: string[]) => {
    const batchSize = 32 // Optimal for Gemini embeddings
    const batches = chunk(texts, batchSize)
    return Promise.all(batches.map((b) => embedBatch(b)))
}

// Use HNSW for high-recall RAG
const hnswIndex = await libsqlStorage.createIndex({
    tableName: 'embeddings',
    indexName: 'hnsw_cosine_idx',
    metric: 'cosine',
    method: 'hnsw', // Faster than ivfflat for most workloads
    efConstruction: 128,
    efSearch: 64,
})
```

---

## 📁 **Structure**

```bash
╭─────────────────────────────── AgentStack ───────────────────────────────╮
│ Files: 727+ | Size: 8.5MB+                                               │
│ Top Extensions: .tsx (314+), .ts (299+), .json (59), .md (27), .mdx (16) │
╰──────────────────────────────────────────────────────────────────────────╯
AgentStack

├──   app/ (24 directories, 298+ files, 1.2MB+)
│   ├──   about/ (410.0B)
│   │   └── page.tsx
│   ├──   api/ (6 files, 6.6KB)
│   │   ├──   chat/ route.ts
│   │   ├──   chat-extra/ route.ts
│   │   ├──   completion/ route.ts
│   │   ├──   contact/ route.ts
│   │   └──   v0/ route.ts
│   ├──   api-reference/ (5 files, 38.0KB)
│   │   ├──   agents/ page.mdx
│   │   ├──   openapi-schema/ page.mdx
│   │   ├──   tools/ page.mdx
│   │   ├──   workflows/ page.mdx
│   │   └── page.tsx
│   ├──   blog/ (4 files, 13.4KB)
│   │   ├──   hello-world-agentstack/ page.mdx
│   │   ├──   session-summary/ page.tsx
│   │   └── layout.tsx
│   ├──   careers/ page.tsx
│   ├──   changelog/ page.tsx
│   ├──   chat/ (16 directories, 27+ files, 175.7KB+)
│   │   ├──   components/ (16 files, 93.5KB)
│   │   │   └── AI Elements: agent-artifact, agent-chain-of-thought, agent-sources, etc.
│   │   ├──   config/ (7 files, 50.4KB)
│   │   │   └── Model configs: google-models, anthropic-models, openai-models, etc.
│   │   ├──   helpers/ tool-part-transform.ts
│   │   ├──   dataset/ dataset management
│   │   ├──   harness/ evaluation tools
│   │   ├──   logs/ logging interfaces
│   │   ├──   mcp-a2a/ MCP coordination
│   │   ├──   observability/ tracing & metrics
│   │   ├──   providers/ chat providers
│   │   ├──   tools/ tool interfaces
│   │   ├──   workflows/ workflow execution
│   │   └── workspaces/ workspace management
│   ├──   [other app routes...]
│   └──   page.tsx

├──   lib/ (React utilities & hooks)
│   ├──   hooks/ (1590+ lines of TanStack Query hooks)
│   │   └──   use-mastra-query.ts (comprehensive data fetching)
│   ├──   types/ (Zod schemas & TypeScript types, auto-generated)
│   ├──   mastra-client.ts (SDK configuration)
│   └──   [utilities & helpers]

├──   src/mastra/ (22 directories, backend orchestration)
│   ├──   index.ts (25+ agents, 10+ workflows, 12+ networks, middleware)
│   ├──   agents/ (31 agent definitions)
│   │   ├──   supervisor-agent.ts (scoring & delegation)
│   │   └──   [specialized agents: research, copywriter, stock analysis, etc.]
│   ├──   workflows/ (10+ multi-step workflows)
│   ├──   networks/ (12+ supervisor networks - primary coordination)
│   │   ├──   agentNetwork (primary router to all specialized agents)
│   │   ├──   codingTeamNetwork (architecture → review → test → refactor)
│   │   ├──   financialIntelligenceNetwork (research → analysis → charts)
│   │   └──   [other domain-specific supervisor networks]
│   ├──   tools/ (57 enterprise tools)
│   ├──   config/ (model & storage configuration)
│   ├──   workspaces.ts (14 workspace variants: AgentFS, Daytona, Local)
│   ├──   harness.ts (multi-mode agent orchestration - ⚠️ alpha)
│   ├──   a2a/ (agent-to-agent coordination)
│   ├──   mcp/ (MCP servers)
│   └──   [processors, evals, middleware, etc.]

├──   [other directories: docs, scripts, tests, etc.]
```

## 🛠️ **Development**

Building with AgentStack is designed to be intuitive and productive. Here's your development workflow:

### **Creating Custom Tools**

```typescript
// src/mastra/tools/my-tool.ts
import { createTool } from '@mastra/core/tools'
import { z } from 'zod'

export const myCustomTool = createTool({
    id: 'my-custom-tool',
    description: 'What this tool does',
    inputSchema: z.object({
        param: z.string().describe('Parameter description'),
    }),
    outputSchema: z.object({
        result: z.any(),
        error: z.string().optional(),
    }),
    execute: async ({ context }) => {
        // Your logic here
        return { result: 'success' }
    },
})
```

**Tool Development Best Practices:**

- ✅ Always define strict Zod schemas for inputs and outputs
- ✅ Keep tools stateless and pure (agents handle orchestration)
- ✅ Include comprehensive error handling with typed returns
- ✅ Add Vitest tests with mocked external dependencies
- ✅ Use structured logging for observability

### **Creating Custom Agents**

```typescript
// src/mastra/agents/my-agent.ts
import { Agent } from '@mastra/core/agent'
import { googleAI } from '../config/google'
import { myCustomTool } from '../tools'
import { LibsqlMemory, libsqlQueryTool } from '../config/libsql'

export const myAgent = new Agent({
    id: 'my-agent',
    name: 'My Custom Agent',
    description: 'What this agent specializes in',
    instructions: `
    You are an expert in... Use the available tools to...
    Always validate inputs and provide structured outputs.
  `,
    model: googleAI, // or openAI, anthropic, openrouter
    tools: {
        myCustomTool,
        libsqlQueryTool,
    },
    memory: LibsqlMemory, // Enable conversation memory
})
```

### **Live Browser Automation**

AgentStack can attach to a local Chrome session through Chrome DevTools
Protocol (CDP). This powers the live browser agent and the shared browser
runtime.

#### Start Chrome in remote-debug mode

```bash
npm run chrome:debug
```

That script launches Chrome with:

```bash
chrome.exe --remote-debugging-port=9222 --user-data-dir="%TEMP%\\chrome-debug"
```

#### Environment variables

```env
CHROME_CDP_URL=http://127.0.0.1:9222
CHROME_REMOTE_DEBUGGING_URL=http://127.0.0.1:9222
```

#### Browser runtime packages

| Package | Version | Purpose |
| --- | --- | --- |
| `@mastra/agent-browser` | `^0.1.0` | Browser agent integration over CDP |
| `@mastra/stagehand` | `^0.1.0` | Shared browser automation helpers |
| `playwright` | `^1.59.1` | Browser automation / verification |
| `@mastra/core` | `^1.24.1` | Agent runtime and browser orchestration |

#### How it works

```mermaid
sequenceDiagram
  participant Dev as Developer
  participant Script as npm run chrome:debug
  participant Chrome as Local Chrome
  participant CDP as CHROME_CDP_URL<br/>127.0.0.1:9222
  participant Agent as browserAgent / shared browser
  participant Page as Target Web App

  Dev->>Script: Start Chrome in remote-debug mode
  Script->>Chrome: Launch with remote debugging enabled
  Chrome-->>CDP: Expose DevTools endpoint
  Agent->>CDP: Connect through agentBrowser
  Agent->>Page: Navigate / click / type / inspect
  Page-->>Agent: DOM, console, screenshots, network state
  Agent-->>Dev: Structured result
```

#### Browser agent files

- `src/mastra/agents/browserAgent.ts` uses the shared browser runtime.
- `src/mastra/browsers.ts` centralizes the Chrome CDP configuration.
- `src/mastra/config/libsql.ts` provides the shared LibSQL-backed vector and
  memory utilities used by agents and workflows.

**Agent Development Best Practices:**

- ✅ Write clear, detailed instructions with examples
- ✅ Compose 3-5 focused tools per agent (avoid tool bloat)
- ✅ Use memory for conversational agents
- ✅ Add evaluation scorers for quality monitoring
- ✅ Document expected inputs/outputs

### **Development Commands**

```bash
# Run the full test suite (97% coverage target)
npm test

# Run tests for a specific tool
npx vitest src/mastra/tools/tests/my-tool.test.ts

# Run tests matching a pattern
npx vitest -t "financial"

# Check TypeScript types
npm run typecheck

# Lint and auto-fix issues
npm run lint:fix

# Format code with Prettier
npm run format

# Build for production
npm run build
```

### **Testing Strategy**

```typescript
// Example tool test
import { describe, it, expect, vi } from 'vitest'
import { myCustomTool } from '../my-tool'

describe('myCustomTool', () => {
    it('should process valid input correctly', async () => {
        const result = await myCustomTool.execute({
            context: { param: 'test-value' },
            runtimeContext: {} as any,
        })

        expect(result.result).toBeDefined()
        expect(result.error).toBeUndefined()
    })

    it('should handle errors gracefully', async () => {
        const result = await myCustomTool.execute({
            context: { param: '' }, // Invalid input
            runtimeContext: {} as any,
        })

        expect(result.error).toBeDefined()
    })
})
```

## 🔧 **Configuration**

| Env Var                        | Purpose                               | Required      |
| ------------------------------ | ------------------------------------- | ------------- |
| `TURSO_DATABASE_URL`           | LibSQL persistence for auth/RAG       | ✅            |
| `GOOGLE_GENERATIVE_AI_API_KEY` | Gemini LLM/Embeddings                 | ✅            |
| `SERPAPI_API_KEY`              | Search/News/Shopping (10+ tools)      | ✅            |
| `POLYGON_API_KEY`              | Stock/Crypto quotes/aggs/fundamentals | ✅            |
| `LANGFUSE_BASE_URL`            | Langfuse tracing                      | Observability |

**Full**: `.env.example` + `src/mastra/config/AGENTS.md`

## 🧪 **Testing Strategy (97% Coverage)**

AgentStack maintains rigorous testing standards with 97% code coverage across 100+ tests, ensuring production reliability and safe deployments.

### **Test Commands**

```bash
# Run complete test suite
npm test

# Generate coverage report
npm run coverage

# Run specific test files
npx vitest src/mastra/tools/tests/polygon-tools.test.ts

# Filter tests by pattern
npx vitest -t "financial"

# Watch mode for development
npx vitest --watch
```

### **Testing Philosophy**

```bash
┌─────────────────────────────────────────────────────────┐
│  Every Tool → Unit Test + Integration Test + Mock       │
│  Every Agent → Evaluation Scorer + Behavior Test        │
│  Every Workflow → E2E Test + Step Validation            │
│  Every API → Contract Test + Response Validation        │
└─────────────────────────────────────────────────────────┘
```

### **Test Categories**

| Type                  | Coverage | Tools          | Purpose                         |
| --------------------- | -------- | -------------- | ------------------------------- |
| **Unit Tests**        | 97%      | Vitest         | Tool/agent logic in isolation   |
| **Integration Tests** | 85%      | Vitest + MSW   | API interactions, DB operations |
| **E2E Tests**         | 60%      | Playwright     | User flows, critical paths      |
| **Eval Tests**        | 100%     | Custom Scorers | Agent quality metrics           |

### **Mock Strategy**

All external API calls are fully mocked for reliable, fast tests:

```typescript
// Example: Polygon API mock
vi.mock('../config/polygon', () => ({
    polygonClient: {
        aggregates: vi.fn().mockResolvedValue({
            results: [{ c: 150.25, h: 152.0, l: 149.5, v: 1000000 }],
        }),
    },
}))

// Example: Database mock
vi.mock('../config/libsql', () => ({
  libsqlQueryTool: {
        execute: vi.fn().mockResolvedValue({
            data: [{ id: 1, result: 'success' }],
            error: null,
        }),
    },
}))
```

### **Writing Tests**

```typescript
// src/mastra/tools/tests/my-tool.test.ts
import { describe, it, expect, vi } from 'vitest'
import { myTool } from '../my-tool'

describe('myTool', () => {
    beforeEach(() => {
        vi.clearAllMocks()
    })

    describe('execute', () => {
        it('returns success for valid input', async () => {
            const result = await myTool.execute({
                context: { param: 'valid-value' },
                runtimeContext: {} as any,
            })

            expect(result.data).toBeDefined()
            expect(result.error).toBeNull()
        })

        it('handles validation errors', async () => {
            const result = await myTool.execute({
                context: { param: '' }, // Invalid
                runtimeContext: {} as any,
            })

            expect(result.data).toBeNull()
            expect(result.error).toContain('validation')
        })

        it('handles external API failures', async () => {
            // Setup mock to throw
            vi.mocked(externalApi).mockRejectedValue(new Error('Network error'))

            const result = await myTool.execute({
                context: { param: 'test' },
                runtimeContext: {} as any,
            })

            expect(result.error).toContain('Network error')
        })
    })
})
```

## 🔒 **Security & Governance**

AgentStack implements enterprise-grade security controls for production deployments, protecting against common vulnerabilities and ensuring data privacy.

### **Security Layers**

```bash
┌─────────────────────────────────────────────────────────────┐
│                    Security Architecture                    │
├─────────────────────────────────────────────────────────────┤
│  🔐 Authentication    │  JWT tokens + Role-based access     │
│  🛡️ Authorization     │  RBAC with policy definitions       │
│  🔍 Input Validation  │  Zod schemas for all inputs         │
│  🧹 Output Sanitizing │  HTML/JS sanitization               │
│  🔒 Secrets Handling  │  Automatic masking in logs/traces   │
│  📁 File Security     │  Path traversal prevention          │
└─────────────────────────────────────────────────────────────┘
```

### **Key Security Features**

| Feature                      | Implementation               | Protection                              |
| ---------------------------- | ---------------------------- | --------------------------------------- |
| **JWT Authentication**       | `jwt-auth.tool.ts`           | Secure API access with token validation |
| **Role-Based Access**        | `src/mastra/policy/acl.yaml` | Granular permissions per user/agent     |
| **Path Validation**          | `validateDataPath()`         | Prevents directory traversal attacks    |
| **HTML Sanitization**        | JSDOM + Cheerio              | Removes scripts/malicious content       |
| **Secrets Masking**          | `maskSensitiveMessageData()` | Hides API keys in logs and traces       |
| **Rate Limiting**            | Built-in throttling          | Prevents API abuse and cost overruns    |
| **SQL Injection Prevention** | Parameterized queries        | Safe database operations                |

### **Security Best Practices**

```typescript
// Always validate file paths
import { validateDataPath } from '../config/utils'

export const fileTool = createTool({
    inputSchema: z.object({
        path: z.string(),
    }),
    execute: async ({ context }) => {
        // Validates and sanitizes the path
        const safePath = validateDataPath(context.path)
        if (!safePath) {
            return { error: 'Invalid path' }
        }
        // Proceed with safePath...
    },
})

// Mask sensitive data in logs
import { maskSensitiveMessageData } from '../config/libsql'

logger.info('Processing request', {
    data: maskSensitiveMessageData(requestData),
})
```

### **Compliance Ready**

- ✅ **GDPR**: Data anonymization and retention controls
- ✅ **SOC 2**: Audit trails and access logging
- ✅ **ISO 27001**: Security controls documentation
- ✅ **HIPAA**: PHI handling capabilities (with configuration)

## 📊 **Observability (Production-Ready)**

```bash
Langfuse Exporters:
├── Traces: 100% (spans/tools/agents)
├── Scorers: 10+ (diversity/quality/task-completion)
├── Metrics: Latency/errors/tool-calls
└── Sampling: Always-on + ratio (30-80%)
```

**Custom Scorers**: Source diversity, completeness, creativity, response quality.

### Dashboard Architecture

The admin dashboard provides comprehensive observability and management:

**Routes:**

- `/dashboard` - Overview with stat cards (agents, workflows, tools, recent activity)
- `/dashboard/agents` - Agent management (list, details, tools, evals)
- `/dashboard/workflows` - Workflow monitoring and execution history
- `/dashboard/tools` - Tool catalog and usage analytics
- `/dashboard/observability` - Traces, spans, and performance metrics
- `/dashboard/memory` - Memory threads, messages, and working memory
- `/dashboard/vectors` - Vector indexes and similarity search
- `/dashboard/logs` - System logs with transport filtering
- `/dashboard/telemetry` - Performance telemetry and metrics

**Components:**

```typescript
// Shared components (_components/)
;-data -
    table.tsx - // Reusable TanStack Table with sorting/filtering
    detail -
    panel.tsx - // Slide-over panel for item details
    empty -
    state.tsx - // Consistent empty states
    error -
    fallback.tsx - // Error boundary with retry
    loading -
    skeleton.tsx - // Skeleton loaders
    sidebar.tsx - // Navigation sidebar
    stat -
    card.tsx - // Metric display cards
    // Agent-specific (agents/_components/)
    agent -
    list.tsx - // Filterable agent list
    agent -
    list -
    item.tsx - // Individual agent card
    agent -
    details.tsx - // Agent configuration details
    agent -
    tab.tsx - // Agent overview tab
    agent -
    tools -
    tab.tsx - // Agent tools tab
    agent -
    evals -
    tab.tsx // Agent evaluations tab
```

**Data Fetching:**

All dashboard pages use TanStack Query hooks from `lib/hooks/use-mastra-query.ts`:

```typescript
import { useAgents, useTools, useTraces } from '@/lib/hooks/use-mastra-query'

function AgentsPage() {
    const { data: agents, isLoading } = useAgents()
    const { data: tools } = useToolsQuery()

    // Automatic caching, refetching, and error handling
}
```

## 🌐 **Integrations Matrix**

| Category             | Tools                                                  | Agents                                    | Frontend                                |
| -------------------- | ------------------------------------------------------ | ----------------------------------------- | --------------------------------------- |
| **🔍 Search**        | SerpAPI (News/Trends/Shopping/Scholar/Local/Yelp)      | ResearchAgent                             | Chat interface with citations           |
| **💰 Financial**     | Polygon (10+), Finnhub (6+), AlphaVantage (indicators) | StockAnalysis, CryptoAnalysis             | Dashboard with charts and metrics       |
| **📄 RAG**           | libSQL chunk/rerank/query/graph                        | Retrieve/Rerank/Answerer                  | Vector search interface                 |
| **📝 Content**       | PDF→MD, Web Scraper, Copywriter/Editor                 | CopywriterAgent, EditorAgent, ReportAgent | Chat with artifact preview              |
| **🎨 Visual**        | CSV↔Excalidraw, SVG/XML process                        | csvToExcalidrawAgent, imageToCsvAgent     | Workflow canvas visualization           |
| **🌐 Orchestration** | A2A MCP Server                                         | a2aCoordinatorAgent, codingA2ACoordinator | Network routing panel                   |
| **💻 UI**            | AI Elements (30), shadcn/ui (35), Radix primitives     | Chat/Reasoning/Canvas interfaces          | 65 components across 10+ app routes     |
| **📊 Observability** | Langfuse traces, Custom scorers                        | All agents instrumented                   | Dashboard with traces/logs/telemetry    |
| **🔄 State Mgmt**    | TanStack Query                                         | Memory threads, working memory            | 15+ hooks with caching and invalidation |

## 🤝 **Advanced Usage**

### 💬 Chat Interface

The chat interface (`/chat`) provides a production-ready AI chat experience with 48+ specialized agents:

**AI Elements Components** (16 integrated):

- `AgentArtifact` - Code/document artifacts with preview
- `AgentChainOfThought` - Step-by-step reasoning display
- `AgentCheckpoint` - Progress checkpoints
- `AgentConfirmation` - User confirmations
- `AgentInlineCitation` - Source citations
- `AgentPlan` - Multi-step plans
- `AgentQueue` - Task queues
- `AgentReasoning` - Reasoning traces
- `AgentSources` - Source documents
- `AgentSuggestions` - Follow-up suggestions
- `AgentTask` - Individual tasks
- `AgentTools` - Tool usage display
- `AgentWebPreview` - Web preview iframe

**Agent Categories** (48+ total):

- **Research** (5): researchAgent, researchPaperAgent, knowledgeIndexingAgent, learningExtractionAgent, dane
- **Content** (5): copywriterAgent, editorAgent, contentStrategistAgent, scriptWriterAgent, reportAgent
- **Financial** (6): stockAnalysisAgent, chartSupervisorAgent, chartTypeAdvisorAgent, chartDataProcessorAgent, chartGeneratorAgent
- **Data** (8): dataIngestionAgent, dataTransformationAgent, dataExportAgent, documentProcessingAgent, csvToExcalidrawAgent, imageToCsvAgent, excalidrawValidatorAgent, imageAgent
- **Coding** (9): codeArchitectAgent, codeReviewerAgent, testEngineerAgent, refactoringAgent, daneCommitMessage, daneIssueLabeler, daneLinkChecker, daneChangeLog, danePackagePublisher
- **Business** (4): legalResearchAgent, contractAnalysisAgent, complianceMonitoringAgent, businessStrategyAgent

**Model Providers** (40+ models):

- **Google**: 8 models (Gemini 2.5 Flash, Pro, Exp variants)
- **OpenAI**: 12 models (GPT-5, GPT-4o, o1, o3-mini)
- **Anthropic**: 8 models (Claude 4.5, 4 Sonnet/Opus/Haiku)
- **OpenRouter**: 12+ models (Llama, Mistral, Qwen)

### 🌐 Networks Interface

Advanced agent network orchestration (`/networks`) with routing and coordination:

**13 Pre-configured Networks:**

1. **Primary Agent Network** (8 agents): General routing to specialized agents
2. **Coding Team Network** (4 agents): Architecture → Review → Testing → Refactoring
3. **Data Pipeline Network** (3 agents): Ingestion → Transformation → Export
4. **Report Generation Network** (3 agents): Research → Analysis → Report
5. **Research Pipeline Network** (4 agents): Research → Learning → Knowledge Indexing → Synthesis
6. **Content Creation Network** (5 agents): Writing → Editing → Strategy → Scripting
7. **Financial Intelligence Network** (7 agents): Stock analysis → Charts → Research → Reporting
8. **Learning Network** (5 agents): Learning extraction → Knowledge indexing → Research
9. **Marketing Automation Network** (6 agents): Social media → SEO → Content → Translation
10. **DevOps Network** (7 agents): Architecture → Testing → Deployment → Monitoring
11. **Business Intelligence Network** (7 agents): Data ingestion → Analytics → Visualization
12. **Security Network** (4 agents): Code review → Compliance → Vulnerability management

**Features:**

- **Network Routing Panel**: Visualizes agent routing decisions in real-time
- **Parallel Execution**: Multiple agents work simultaneously
- **A2A Coordination**: Inter-agent communication management

### 🔄 Workflows Interface

Interactive workflow visualization (`/workflows`) with AI Elements Canvas:

**21 Pre-built Workflows:**

1. **Weather Workflow**: Fetch weather → Analyze → Suggest activities
2. **Content Studio**: Research → Write → Edit → Review
3. **Content Review**: Fetch → Analyze → Score → Report
4. **Financial Report**: Market data → Analysis → Report generation
5. **Document Processing**: Upload → Parse → Chunk → Embed → Index
6. **Research Synthesis**: Query → Search → Analyze → Synthesize
7. **Learning Extraction**: Read → Extract → Summarize → Store
8. **Governed RAG Index**: Validate → Chunk → Embed → Upsert
9. **Governed RAG Answer**: Query → Retrieve → Rerank → Answer
10. **Spec Generation**: Requirements → Design → Spec → Validation
11. **Stock Analysis**: Fetch data → Technical analysis → Report
12. **Repo Ingestion**: Repository analysis → Code indexing → Knowledge base
13. **Telephone Game**: Interactive user input workflows
14. **Changelog Generation**: Git diff analysis → AI changelog creation
15. **Marketing Campaign**: End-to-end campaign orchestration
16. **Automated Reporting**: Scheduled data gathering → Report generation
17. **Data Analysis**: Multi-source data ingestion → Transformation → Insights
18. **Financial Analysis**: Deep market analysis → Risk assessment → Strategy
19. **Safe Refactoring**: Code analysis → Refactor → Test validation
20. **Test Generation**: Code analysis → Unit/Integration test creation
21. **New Contributor**: Onboarding → Repo analysis → First task guidance

**AI Elements Components** (8 for workflows):

- `WorkflowCanvas` - Main canvas with pan/zoom
- `WorkflowNode` - Individual workflow steps
- `WorkflowEdge` - Connections between steps
- `WorkflowPanel` - Side panel with details
- `WorkflowControls` - Canvas controls
- `WorkflowLegend` - Node type legend
- `WorkflowOutput` - Execution output display

## 🚀 **Advanced Usage**

### Custom Agent

```ts
// src/mastra/agents/my-agent.ts
import { Agent } from '@mastra/core/agent'
import { googleAI } from '../config/google'
import { LibsqlMemory, libsqlQueryTool } from '../config/libsql'
export const myAgent = new Agent({
    id: 'my-agent',
  tools: { polygonStockQuotesTool, libsqlQueryTool },
    instructions: 'Analyze stocks with Polygon + RAG...',
    model: googleAI, // From model registry
  memory: LibsqlMemory,
})
// Auto-registers in index.ts
```

### MCP/A2A Client

```bash
# Start server
npm run mcp-server

# Use in Cursor/Claude
# coordinate_a2a_task({task: "AAPL analysis", agents: ["research", "stock"]})
```

## 🤝 **Contributing**

AgentStack is an open-source project powered by a community of developers, researchers, and AI enthusiasts. We welcome contributions of all kinds—from bug fixes and documentation improvements to new tools, agents, and innovative features.

### **Why Contribute?**

- 🚀 **Shape the Future**: Help define the standard for production-grade multi-agent systems
- 📚 **Learn & Grow**: Work with cutting-edge AI technologies (Mastra, RAG, A2A orchestration)
- 🌟 **Build Your Portfolio**: Contribute to a high-impact, enterprise-ready framework
- 🤝 **Join the Community**: Collaborate with passionate developers worldwide

### **Quick Start for Contributors**

```bash
# 1. Fork the repository on GitHub
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/AgentStack.git
cd AgentStack

# 3. Install dependencies
npm ci

# 4. Verify everything works
npm test  # Should pass with 97%+ coverage

# 5. Create a feature branch
git checkout -b feature/your-awesome-contribution
```

### **What to Contribute**

| Contribution Type | Examples                                           | Impact                         |
| ----------------- | -------------------------------------------------- | ------------------------------ |
| **New Tools**     | Financial APIs, data processors, web scrapers      | Expands framework capabilities |
| **New Agents**    | Domain-specific specialists (legal, medical, etc.) | Enhances AI workforce          |
| **Bug Fixes**     | Type errors, edge cases, performance issues        | Improves reliability           |
| **Documentation** | README updates, code comments, tutorials           | Helps other developers         |
| **Tests**         | Increase coverage, add integration tests           | Ensures quality                |
| **UI Components** | New AI Elements, dashboard features                | Improves UX                    |
| **Workflows**     | Multi-step automation patterns                     | Demonstrates best practices    |

### **Contribution Workflow**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
flowchart LR
    A[🍴 Fork] --> B[💻 Code]
    B --> C[🧪 Test]
    C --> D[📤 PR]
    D --> E[✅ Review]
    E --> F[🎉 Merge]

    style A fill:#1565c0,color:#fff
    style B fill:#2e7d32,color:#fff
    style C fill:#ef6c00,color:#fff
    style D fill:#6a1b9a,color:#fff
    style E fill:#00695c,color:#fff
    style F fill:#c62828,color:#fff
```

### **Development Standards**

#### **Code Quality Checklist**

Before submitting your PR, ensure:

- [ ] **Type Safety**: All TypeScript compiles with strict mode (`npm run typecheck`)
- [ ] **Test Coverage**: New code has 95%+ coverage (`npm test`)
- [ ] **Linting**: ESLint passes with zero warnings (`npm run lint`)
- [ ] **Zod Schemas**: All tool inputs/outputs use strict validation
- [ ] **Documentation**: New features include JSDoc comments
- [ ] **Error Handling**: Graceful failures with typed error returns
- [ ] **Observability**: Tracing spans for significant operations

#### **Commit Message Convention**

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```text
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

**Examples:**

```bash
feat(tools): add Alpha Vantage technical indicators

Add support for RSI, MACD, and Bollinger Bands with
comprehensive test coverage and documentation.

Closes #123
```

```bash
docs(readme): update contributing guidelines

Add detailed workflow diagram and code quality checklist
for new contributors.
```

### **Pull Request Template**

When opening a PR, please include:

```markdown
## Summary

Brief description of changes

## Type of Change

- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing

- [ ] Unit tests pass (`npm test`)
- [ ] Type check passes (`npm run typecheck`)
- [ ] Linting passes (`npm run lint`)

## Screenshots (if UI changes)

## Checklist

- [ ] Code follows project style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] Tests added for new functionality
```

### **Getting Help**

- 💬 **Discussions**: [GitHub Discussions](https://github.com/ssdeanx/AgentStack/discussions)
- 🐛 **Bug Reports**: [Open an Issue](https://github.com/ssdeanx/AgentStack/issues)
- 📧 **Email**: [ssdeanx@gmail.com](mailto:ssdeanx@gmail.com)
- 🐦 **Twitter**: [@ssdeanx](https://x.com/ssdeanx)

### **Code of Conduct**

We are committed to providing a welcoming and inclusive experience for everyone:

- Be respectful and constructive in all interactions
- Welcome newcomers and help them get started
- Focus on what is best for the community
- Show empathy towards others

**Report violations** to [ssdeanx@gmail.com](mailto:ssdeanx@gmail.com)

---

**🎉 Thank you for considering contributing to AgentStack! Every contribution, no matter how small, helps make this project better for everyone.**

## 📚 **Resources**

**Frontend Routes:**

- **[Chat Interface](app/chat/AGENTS.md)**: AI chat with 48+ agents using AI Elements and @ai-sdk/react
- **[Networks](app/networks/AGENTS.md)**: Advanced agent network orchestration with routing panel
- **[Workflows](app/workflows/AGENTS.md)**: Interactive workflow visualization with AI Elements Canvas
- **[Dashboard](app/dashboard/AGENTS.md)**: Admin dashboard with agents/tools/workflows/traces/memory/vectors
- **[Documentation](app/docs/)**: Comprehensive docs (AI SDK, components, RAG, security)
- **[API Reference](app/api-reference/)**: OpenAPI schema and API documentation

**Shared Libraries:**

- **[lib/hooks](lib/hooks/)**: TanStack Query hooks for data fetching (1590+ lines)
  - `use-mastra-query.ts` - Comprehensive hooks for all Mastra APIs
- **[lib/types](lib/types/)**: Zod schemas and TypeScript types (auto-generated)
- **[lib/](lib/)**: Client SDK, utilities, auth, A2A coordination
- **[src/mastra/auth.ts](src/mastra/auth.ts)**: Better Auth + LibSQL server auth configuration
- **[src/mastra/workspaces.ts](src/mastra/workspaces.ts)**: Workspace, sandbox, AgentFS, and LibSQL-backed workspace storage
- **[src/mastra/agents/request-context.ts](src/mastra/agents/request-context.ts)**: Server-side request context schema and helpers
- **[src/mastra/tools/request-context.utils.ts](src/mastra/tools/request-context.utils.ts)**: Tool-side request context helpers

**Core Components:**

- **[UI Components](ui/AGENTS.md)**: 55 shadcn/ui base components
- **[AI Elements](src/components/ai-elements/AGENTS.md)**: 50 AI chat/reasoning/canvas components
- **[Agents Catalog](src/mastra/agents/AGENTS.md)**: 48+ agents
- **[Tools Matrix](src/mastra/tools/AGENTS.md)**: 94+ tools
- **[Workflows](src/mastra/workflows/AGENTS.md)**: 21 multi-step workflows
- **[Networks](src/mastra/networks/AGENTS.md)**: 12 agent networks
- **[Config Guide](src/mastra/config/AGENTS.md)**: Setup + env vars
- **[MCP/A2A](src/mastra/mcp/AGENTS.md)**: Multi-agent federation
- **[Scorers](src/mastra/scorers/AGENTS.md)**: 10+ eval metrics

## 🏆 **Roadmap**

- [x] **Financial Suite**: Polygon/Finnhub/AlphaVantage (✅ Live - 30+ endpoints)
- [x] **RAG Pipeline**: libSQL + rerank/graph (✅ Live)
- [x] **A2A MCP**: Parallel orchestration (✅ Live)
- [x] **15 Workflows**: Sequential, parallel, branch, loop, foreach, suspend/resume (✅ Live)
- [x] **12 Agent Networks**: Routing and coordination (✅ Live)
- [x] **105 UI Components**: AI Elements + shadcn/ui (✅ Live)
- [x] **Chat Interface**: Full agent chat UI with AI Elements (✅ Live - 48+ agents)
- [x] **Dashboard**: Admin dashboard with TanStack Query (✅ Live - 8 routes)
- [x] **MastraClient SDK**: Type-safe client with Zod schemas (✅ Live)
- [x] **Marketing Suite**: Social media, SEO, translation, customer support (✅ Live)
- [x] **DevOps Suite**: CI/CD, testing, deployment, monitoring (✅ Live)
- [x] **Business Intelligence**: Data analytics, visualization, reporting (✅ Live)
- [x] **Security Suite**: Code review, compliance, vulnerability management (✅ Live)
- [ ] **LangSmith/Phoenix**: Enhanced eval dashboards
- [ ] **Docker/Helm**: K8s deployment templates
- [ ] **Multi-tenancy**: Tenant isolation and resource management

---

⭐ **Star [ssdeanx/AgentStack](https://github.com/ssdeanx/AgentStack)**
🐦 **Follow [@ssdeanx](https://x.com/ssdeanx)**
📘 **[Docs](https://agentstack.ai)** (Coming Q1 2026)

_Last updated: 2026-04-14 | v1.0.43_

## 🧠 **Chat**

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#58a6ff', 'primaryTextColor': '#c9d1d9', 'primaryBorderColor': '#30363d', 'lineColor': '#58a6ff', 'sectionBkgColor': '#161b22', 'altSectionBkgColor': '#0d1117', 'sectionTextColor': '#c9d1d9', 'gridColor': '#30363d', 'tertiaryColor': '#161b22' }}}%%
classDiagram
  direction LR

  class AgentPlanData {
    +string title
    +string description
    +PlanStep[] steps
    +bool isStreaming
    +number currentStep
  }

  class PlanStep {
    +string text
    +bool completed
  }

  class AgentTaskData {
    +string title
    +TaskStep[] steps
  }

  class TaskStep {
    +string id
    +string text
    +TaskStepStatus status
    +string file_name
    +string file_icon
  }

  class TaskStepStatus {
    <<enumeration>>
    pending
    running
    completed
    error
  }

  class ArtifactData {
    +string id
    +string title
    +string description
    +string type
    +string language
    +string content
  }

  class Citation {
    +string id
    +string number
    +string title
    +string url
    +string description
    +string quote
  }

  class QueuedTask {
    +string id
    +string title
    +string description
    +string status
    +Date createdAt
    +Date completedAt
    +string error
  }

  class WebPreviewData {
    +string id
    +string url
    +string title
    +string code
    +string language
    +string html
    +bool editable
    +bool showConsole
    +number height
  }

  class ReasoningStep {
    +string id
    +string label
    +string description
    +string status
    +string[] searchResults
    +number duration
  }

  class AgentSuggestionsProps {
    +string[] suggestions
    +onSelect(suggestion)
    +bool disabled
    +string className
  }

  class AgentSourcesProps {
    +SourceItem[] sources
    +string className
    +number maxVisible
  }

  class SourceItem {
    +string url
    +string title
  }

  class AgentReasoningProps {
    +string reasoning
    +bool isStreaming
    +number duration
    +string className
  }

  class AgentToolsProps {
    +ToolInvocation[] tools
    +string className
  }

  class ConfirmationSeverity {
    <<enumeration>>
    info
    warning
    danger
  }

  class InlineCitationToken {
    <<union>>
    text
    citation
  }

  class ChatUtils {
    +extractPlanFromText(text) AgentPlanData
    +parseReasoningToSteps(reasoning) ReasoningStep[]
    +tokenizeInlineCitations(content, sources) InlineCitationToken[]
    +getSuggestionsForAgent(agentId) string[]
  }

  class AgentPlan {
    +AgentPlanData plan
    +onExecuteCurrentStep()
    +onCancel()
    +onApprove()
  }

  class AgentTask {
    +AgentTaskData task
  }

  class AgentArtifact {
    +ArtifactData artifact
    +onCodeUpdate(artifactId, newCode)
  }

  class AgentInlineCitation {
    +Citation[] citations
    +string text
  }

  class AgentSuggestions {
    +AgentSuggestionsProps props
  }

  class AgentSources {
    +AgentSourcesProps props
  }

  class AgentReasoning {
    +AgentReasoningProps props
  }

  class AgentTools {
    +AgentToolsProps props
  }

  class AgentQueue {
    +QueuedTask[] tasks
  }

  class AgentWebPreview {
    +WebPreviewData preview
    +onCodeChange(code)
  }

  class AgentCodeSandbox {
    +onCodeChange(code)
  }

  %% Relationships between data types
  AgentPlanData --> "*" PlanStep
  AgentTaskData --> "*" TaskStep
  TaskStep --> TaskStepStatus
  AgentSourcesProps --> "*" SourceItem
  AgentToolsProps --> "*" ToolInvocation

  %% Components depending on shared chat types
  AgentPlan --> AgentPlanData
  AgentTask --> AgentTaskData
  AgentArtifact --> ArtifactData
  AgentInlineCitation --> Citation
  AgentSuggestions --> AgentSuggestionsProps
  AgentSources --> AgentSourcesProps
  AgentReasoning --> AgentReasoningProps
  AgentTools --> AgentToolsProps
  AgentQueue --> QueuedTask
  AgentWebPreview --> WebPreviewData
  AgentCodeSandbox --> WebPreviewData

  %% Utilities using shared types
  ChatUtils --> AgentPlanData
  ChatUtils --> ReasoningStep
  ChatUtils --> InlineCitationToken
  ChatUtils --> AgentSuggestionsProps
```
