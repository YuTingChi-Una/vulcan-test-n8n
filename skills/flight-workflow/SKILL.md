---
name: flight-workflow
license: MIT
description: >
  n8n skill for an AI-powered workflow combining research, writing,
    and notification agents with MCP server integration.
    tools:
      - name: WebSearchTool
          description: Fetch data from external APIs and web endpoints
            - name: DataProcessorTool
                description: Transform and process data using JavaScript code
                ---

                # Flight Workflow Skill

                n8n workflow connecting AI agents with tools and MCP servers.

                ## Nodes
                - **ResearchAgent**: AI agent for gathering information.
                - **WriterAgent**: AI agent for producing content.
                - **WebSearchTool**: HTTP Request node for external data.
                - **DataProcessorTool**: Code node for data transformation.
                - **FilesystemMCPServer**: MCP client for filesystem access.
                - **BraveSearchMCPServer**: MCP client for web search.
                - **GPT4oModel**: OpenAI GPT-4o language model.
                - **OutputFormatter**: Set node for structuring final output.

                ## MCP Servers
                - **Filesystem MCP**: SSE endpoint at http://localhost:3001/sse.
                - **Brave Search MCP**: SSE endpoint at http://localhost:3002/sse.
                
