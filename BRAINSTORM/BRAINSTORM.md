I am trying to create "cursor for design".  The goal is to enable users who are heavily utilizing AI coding agents to have consistent design throughout their application.  Meaning all pages, components, colors, themes, etc. are all aligned to the same design patterns.

The idea is to expose and MCP server or tools to users so that their cursor agent can simply call our "design-agent" tool who will scaffold a project based on the user's design input (or image).

We are targeting react applications that use tailwindV4 and react with shadcn.  I have a basic implementation boilerplate in this directory.  This directory is simply an app that is preconfigured to use tailwind, react, and shadcn; it installs all shadcn components.

From here users could iterate on the design as they see fit, and then begin building components (e.g., login form, dashboard page, landing page, etc.).  Here is the basic template.

@/bun-design


Your goal is to evaluate this agentic system and provide feedback. 

