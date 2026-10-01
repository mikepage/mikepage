## Mike Pagé 🦉

Software Engineer — Infrastructure, based in Middelburg, Netherlands. Resident night owl: most of what you'll find here was built after dark.

🌐 [mikepage.nl](https://mikepage.nl) · 🧪 [tools.mikepage.nl](https://tools.mikepage.nl) · 💼 [LinkedIn](https://www.linkedin.com/in/mikepagenl/)

---

### Writing

**[mikepage.nl](https://mikepage.nl)** is my blog: software, agentic development, Cloudflare, and the occasional stray thought.

#### Latest posts

- **[cf is a Cloudflare CLI written for the agent](https://mikepage.nl/posts/cloudflare-cf-cli)**
  Cloudflare's new cf CLI covers the whole API, speaks JSON by default and tells agents how to find commands. That makes the MCP server in Cloudflare's Claude Code plugin redundant.
- **[EmDash 1.0 and agentic development](https://mikepage.nl/posts/emdash-1-0-agentic-development)**
  What 1.0 changes, the three ways an agent can drive an EmDash site (skills, CLI, MCP), how to upgrade, and where it still falls short.
- **[A Symfony-style backend without the infrastructure](https://mikepage.nl/posts/backend-developer-moves-to-cloudflare)**
  We rebuilt a Symfony backend on Workers with Hono and Drizzle. The app design stayed. The infrastructure mostly disappeared.

→ [All posts](https://mikepage.nl/posts) · [RSS](https://mikepage.nl/rss.xml)

### Experiments

**[tools.mikepage.nl](https://tools.mikepage.nl)** is where the experiments live. Small DNS, email and network utilities, each one a live example of a Cloudflare Workers pattern. Every result has a shareable URL, and the ones with a JSON API are also tools on an MCP server.

### Working with agents

I build alongside Claude Code as a daily driver: agent-authored Workers, project skills that teach the agent a codebase's rules, and CLIs and MCP servers to deploy and debug from the same session. The blog runs on [EmDash](https://github.com/emdash-cms/emdash), an Astro CMS on Workers, D1 and R2, and it was agent-built too.
