# GuaraCloud Agent Skills

Agent skills that teach AI agents how to deploy and manage applications on [GuaraCloud](https://guaracloud.com) using the `guara` CLI.

## Installation

### Any compatible agent (Cursor, Copilot, Gemini CLI, etc.)

```bash
npx skills add guaracloud/agent-skills
```

### Claude Code

```
/plugin install guaracloud/agent-skills
```

## Skills

| Skill | Description |
|---|---|
| `guara-cloud` | Platform concepts, CLI setup, and command reference |
| `guara-deploy` | Deploy services, manage domains, scale, and rollback |
| `guara-troubleshoot` | Diagnose failed deployments, crashes, and CLI errors |
| `guara-develop` | Local dev workflows: linking, exec, proxy, logs, env |

## Documentation

- [GuaraCloud Docs](https://guaracloud.com/docs)
- [GuaraCloud Dashboard](https://app.guaracloud.com)
- [Agent Skills Specification](https://agentskills.io/specification)

## License

Apache-2.0
