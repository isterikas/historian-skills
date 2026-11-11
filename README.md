# Historian Skills

Historian Skills is a collection of reusable AI skills for historians, humanities researchers, students, and academics. It aims to make research workflows more efficient, transparent, reproducible, and reliable. The collection begins with literature discovery and can grow to support organizing sources, investigating historical topics, and other humanities research tasks.

## Available skills

| Skill | Description | Folder |
| --- | --- | --- |
| Literature Finder | Finds and verifies scholarly literature across publication languages and returns an annotated bibliography with a search methodology. | [`literature-finder`](skills/literature-finder/) |

## How to use

The package follows the [Agent Skills specification](https://agentskills.io/specification). To prepare an upload package, compress the `skills/literature-finder` folder so the ZIP contains a single top-level `literature-finder/` folder with `SKILL.md` and `references/`. On macOS, choose **Compress “literature-finder”** in Finder. From the repository root, the equivalent command is `(cd skills && zip -r ../literature-finder.zip literature-finder -x '*/.DS_Store')`.

- **ChatGPT Work** — On an eligible ChatGPT workspace with custom uploads enabled, open **Plugins → Skills → Create → Upload from your computer** and follow the upload prompt. In a Work chat, select Literature Finder using `@` where the skill picker is available, or ask “Use Literature Finder to help me research a historical topic.” Availability, upload controls and accepted files depend on the workspace and client. [OpenAI skill upload guidance](https://help.openai.com/en/articles/20001066-skills-in-chatgpt) · [OpenAI skill invocation guidance](https://learn.chatgpt.com/docs/build-skills)
- **Claude Cowork** — With code execution and skill creation enabled, open **Customize → Skills → + → Create skill → Upload a skill**. Upload the ZIP and enable the skill. In Cowork, ask “Use Literature Finder to help me research a historical topic.” Enable web search where needed. [Anthropic skill upload guidance](https://support.claude.com/en/articles/12512180-use-skills-in-claude) · [Web search guidance](https://support.claude.com/en/articles/10684626-enable-and-use-web-search)

Literature Finder asks for the topic, accepted publication languages and search depth, one at a time. It searches international sources first, then runs a regional pass. The bibliography defaults to up to ten verified works, with separate groups for direct and contextual results. The workflow uses the host's available search and retrieval tools. Native upload and end-to-end operation in the two products have yet to be tested.

The [source registry](skills/literature-finder/references/source-registry.md) describes public discovery, authorized database access and provider APIs. The package includes no API or MCP integrations. Subscription databases require the appropriate account or institutional access, and an authorized integration must be available to the host for any connector-mediated access. Indexed records or permitted alternative sources can help when direct access is limited.

### Search depth and model choice

| Depth | Research scope | Suggested capability and effort |
| --- | --- | --- |
| Quick | Core terms, focused international discovery, and a targeted regional pass | Fast model at low or medium effort, such as GPT-6 Luna in Work or Claude Haiku 5.5 where available |
| Balanced | More variants and sources, with selective citation exploration | General-purpose model at medium or high effort, such as GPT-6.1 Sol or Claude Sonnet 5.5 |
| Deep | Broader multilingual discovery, citation chaining, and coverage checks | Strong research model at high effort, such as Astra or Claude Opus 5.5 |

Choose among the models and effort controls your host exposes. The skill's search depth controls the scope of research and does not change model settings. Every depth uses the same verification rules. [Work model guidance](https://learn.chatgpt.com/docs/models) · [Claude model and effort guidance](https://support.claude.com/en/articles/8664678-change-the-model-effort-and-thinking-settings)

## Repository structure

```text
README.md
skills/
└── literature-finder/
    ├── SKILL.md
    └── references/
        ├── source-registry.md
        ├── search-methodology.md
        ├── output-format.md
        └── test-cases.md
```

Each skill folder contains its entry instructions and any supporting material. Literature Finder's [test cases](skills/literature-finder/references/test-cases.md) include manual scenarios, expected results, and validation status.

## Contributing

Bug reports, improvements, and proposals for new skills are welcome. Include a reproducible example where possible. Prioritize bibliographic reliability, clear documentation, and respect for source licenses and access restrictions.

## Academic integrity

Verify AI-assisted research against original publications and reliable bibliographic records before citing it. These skills support scholarly work. Interpretation, source criticism and citation decisions remain the researcher's responsibility.

## License

This repository does not currently specify a license.
