# mcp-demo

  A tiny demo repository for testing Model Context Protocol (MCP) tool access from an AI assistant.

  ## About

  This is a test repo used to verify that an AI assistant can call MCP tools — specifically, reading repository file contents through an MCP server. It contains a few small, predictable files so
  tool responses are easy to inspect and validate.

  ## Structure

  mcp-demo/
  ├── README.md      # this file
  ├── hello.txt      # sample text file to read
  └── data/
      └── sample.json

  ## Example

  Ask the assistant to read a file via the MCP server:

  ```text
  > Read hello.txt from the mcp-demo repo
  hello from mcp-demo!

  Purpose

  Used to verify that an MCP server/proxy can read repository contents and return them to the assistant through standard tool calls.
