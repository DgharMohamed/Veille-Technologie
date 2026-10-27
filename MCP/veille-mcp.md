---
marp: true
theme: default
paginate: true
size: 16:9
---

# MCP (Model Context Protocol)

### How AI connects to tools and information

---

## Veille Plan

1. Introduction
2. Problems Encountered
3. Solutions Implemented

---

<!-- _class: light -->

## 1. Introduction

**MCP (Model Context Protocol)** is a standard way for an AI application to connect to tools and information from other services.

Think of it like a connector between an AI app and an app such as GitHub.

### You → AI app → MCP server → Service

---

<!-- _class: light -->

## 2. Problems Encountered

- AI apps need information and tools that live in other services.
- Without a shared standard, each connection may need a custom integration.
- Connecting tools also raises questions about access and safety.

---

<!-- _class: light -->

## 3. Solutions Implemented

MCP gives AI apps and services a shared way to communicate.

An MCP server can provide:

- **Tools** to perform actions or search for information.
- **Resources** to share data.
- **Prompts** to offer reusable instructions.

---

## Example: GitHub MCP

**You ask:** “Find my open GitHub issues.”

1. The AI sends the request to a GitHub MCP server.
2. The server searches issues you can access.
3. The server returns matching issues.
4. The AI shows the results to you.

### You → AI → GitHub MCP → GitHub issues

---

## Sources

- [MCP specification](https://modelcontextprotocol.io/specification/2026-07-28) · Version `2026-07-28`
- [Introducing the Model Context Protocol](https://www.anthropic.com/news/model-context-protocol) · November 25, 2024
- [GitHub MCP Server](https://github.com/github/github-mcp-server) · Official repository
