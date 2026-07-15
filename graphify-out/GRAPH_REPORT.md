# Graph Report - conciliacion-bancaria  (2026-07-15)

## Corpus Check
- 13 files · ~22,154 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 81 nodes · 69 edges · 15 communities (10 shown, 5 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `3a427390`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- ataraxia-dev.md
- What You Must Do When Invoked
- /graphify
- graphify reference: extra exports and benchmark
- 📐 REGLAS DE DESARROLLO — CUMPLIMIENTO OBLIGATORIO
- graphify reference: query, path, explain
- graphify reference: add a URL and watch a folder
- graphify reference: commit hook and native CLAUDE.md integration
- graphify reference: incremental update and cluster-only
- Step 3 - Extract entities and relationships
- graphify reference: GitHub clone and cross-repo merge
- graphify reference: transcribe video and audio
- CLAUDE.md
- CLAUDE.md
- extraction-spec.md

## God Nodes (most connected - your core abstractions)
1. `What You Must Do When Invoked` - 12 edges
2. `/graphify` - 10 edges
3. `graphify reference: extra exports and benchmark` - 8 edges
4. `📐 REGLAS DE DESARROLLO — CUMPLIMIENTO OBLIGATORIO` - 6 edges
5. `graphify reference: query, path, explain` - 5 edges
6. `⚙️ CORE LÓGICO Y MOTORES CRÍTICOS` - 4 edges
7. `Step 3 - Extract entities and relationships` - 4 edges
8. `🏗️ CONTEXTO DEL PROYECTO` - 3 edges
9. `graphify reference: add a URL and watch a folder` - 3 edges
10. `graphify reference: commit hook and native CLAUDE.md integration` - 3 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (15 total, 5 thin omitted)

### Community 0 - "ataraxia-dev.md"
Cohesion: 0.18
Nodes (10): A. Extracción Bancaria — BankParser y Diccionarios, B. Motor de Conciliación en Cascada — Jerarquía O(1), C. Estructura de Exportación — El Embudo, ✅ CONFIRMACIÓN INICIAL, 🏗️ CONTEXTO DEL PROYECTO, ⚙️ CORE LÓGICO Y MOTORES CRÍTICOS, 🧠 MENTALIDAD EJECUTIVA, Módulos del Sistema (+2 more)

### Community 1 - "What You Must Do When Invoked"
Cohesion: 0.18
Nodes (11): Step 0 - GitHub repos and multi-path merge (only if a URL or several paths), Step 1 - Ensure graphify is installed, Step 2.5 - Video and audio (only if video files detected), Step 2 - Detect files, Step 4.5 - Graph health check (read-only integrity gate), Step 4 - Build graph, cluster, analyze, generate outputs, Step 5 - Label communities, Step 6 - Generate Obsidian vault (opt-in) + HTML (+3 more)

### Community 2 - "/graphify"
Cohesion: 0.20
Nodes (9): For /graphify add and --watch, For /graphify query, For the commit hook and native CLAUDE.md integration, For --update and --cluster-only, /graphify, Honesty Rules, Interpreter guard for subcommands, Usage (+1 more)

### Community 3 - "graphify reference: extra exports and benchmark"
Cohesion: 0.22
Nodes (8): graphify reference: extra exports and benchmark, Step 6b - Wiki (only if --wiki flag), Step 7 - Neo4j export (only if --neo4j or --neo4j-push flag), Step 7a - FalkorDB export (only if --falkordb or --falkordb-push flag), Step 7b - SVG export (only if --svg flag), Step 7c - GraphML export (only if --graphml flag), Step 7d - MCP server (only if --mcp flag), Step 8 - Token reduction benchmark (only if total_words > 5000)

### Community 4 - "📐 REGLAS DE DESARROLLO — CUMPLIMIENTO OBLIGATORIO"
Cohesion: 0.33
Nodes (6): 1. Persistencia UI — No destruir el DOM, 2. Auditoría Inmutable, 3. Gestión de Errores — Visibilidad Total, 4. Código Asíncrono — Sin Callback Hell, 5. Escalabilidad Preparada, 📐 REGLAS DE DESARROLLO — CUMPLIMIENTO OBLIGATORIO

### Community 5 - "graphify reference: query, path, explain"
Cohesion: 0.33
Nodes (5): For /graphify explain, For /graphify path, graphify reference: query, path, explain, Step 0 — Constrained query expansion (REQUIRED before traversal), Step 1 — Traversal

### Community 6 - "graphify reference: add a URL and watch a folder"
Cohesion: 0.50
Nodes (3): For /graphify add, For --watch, graphify reference: add a URL and watch a folder

### Community 7 - "graphify reference: commit hook and native CLAUDE.md integration"
Cohesion: 0.50
Nodes (3): For git commit hook, For native CLAUDE.md integration, graphify reference: commit hook and native CLAUDE.md integration

### Community 8 - "graphify reference: incremental update and cluster-only"
Cohesion: 0.50
Nodes (3): For --cluster-only, For --update (incremental re-extraction), graphify reference: incremental update and cluster-only

### Community 9 - "Step 3 - Extract entities and relationships"
Cohesion: 0.50
Nodes (4): Part A - Structural extraction for code files, Part B - Semantic extraction (parallel subagents), Part C - Merge AST + semantic into final extraction, Step 3 - Extract entities and relationships

## Knowledge Gaps
- **56 isolated node(s):** `graphify`, `🧠 MENTALIDAD EJECUTIVA`, `Stack Tecnológico`, `Módulos del Sistema`, `A. Extracción Bancaria — BankParser y Diccionarios` (+51 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `What You Must Do When Invoked` connect `What You Must Do When Invoked` to `Step 3 - Extract entities and relationships`, `/graphify`?**
  _High betweenness centrality (0.071) - this node is a cross-community bridge._
- **Why does `/graphify` connect `/graphify` to `What You Must Do When Invoked`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Why does `Step 3 - Extract entities and relationships` connect `Step 3 - Extract entities and relationships` to `What You Must Do When Invoked`?**
  _High betweenness centrality (0.021) - this node is a cross-community bridge._
- **What connects `graphify`, `🧠 MENTALIDAD EJECUTIVA`, `Stack Tecnológico` to the rest of the system?**
  _56 weakly-connected nodes found - possible documentation gaps or missing edges._