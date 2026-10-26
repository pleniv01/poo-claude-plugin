# Poo.ai for Claude

Review what you've shared with AI, separate visible evidence from model guesses,
and make a practical cleanup plan. When you want to inspect an export, this skill
guides you to [Poo.ai's local scanner](https://poo.ai/scan/) so your export can stay
on your device rather than being uploaded into Claude.

## Try it

- Help me review what I've shared in this conversation. Separate evidence from guesses.
- I want to audit my AI history without uploading my export anywhere. Where do I start?
- A privacy scan found old contact details. Help me make a cleanup checklist without seeing the details.
- Can you actually see my past chats? Be precise about the information available to you.
- How do I distinguish information I shared from an AI's speculation about me?

## Install and use

This is a skills-only plugin containing **review-ai-privacy**. It requires no Poo
account, API key, live connector, or payment to use in Claude. Claude feature and
plan availability apply; Poo's scanner entitlements are separate.

For local Claude Code testing, clone this repository and run from its parent:

```sh
claude --plugin-dir ./poo-claude-plugin
```

Use `/poo-ai:review-ai-privacy`, or ask for a personal AI privacy review.
For manual Claude skill installation, download
[poo-ai-skill.zip](https://github.com/pleniv01/poo-claude-plugin/releases/latest/download/poo-ai-skill.zip)
and upload it using Customize → Skills.
See [Anthropic's skill instructions](https://support.claude.com/en/articles/12512180-use-skills-in-claude).
The directory submission and review are separate; this repository does not claim
an approved or published listing.

## What this plugin can and cannot do

It provides instructions for evidence-based conversation review, questions to ask
your chatbot, local export scanning, and cleanup planning. It cannot run a Poo
scan, inspect another account, retrieve hidden AI profiles, change settings,
delete chats, or verify a provider's data holdings. It does not parse bulk exports
in Claude. Findings from Poo's deterministic scanner are matches to review, not
diagnoses, complete security audits, or verified psychological profiles.

## What runs, reads and connects

The plugin contains readable instructions, documentation and a logo. There is
no executable code, MCP server, hook, package dependency, authentication,
background network request, telemetry, or data storage. Claude can process
personal information already present in the conversation under your Claude
account's policies. The plugin does not request additional identifying details.

No conversations, exports or findings are sent to Poo.ai by this plugin. It offers
optional website links with fixed `utm_source=claude`, `utm_medium=skill` and
`utm_campaign=privacy-review` parameters, never personal content. Opening a link
uses Poo's normal website/hosting policies; the scanner's local processing is a
separate experience. At your request, Claude may use its own browsing tools to
check current public product information or official provider instructions.
The plugin supplies no additional connector or hidden data-transfer mechanism.

Do not upload your private AI export to Claude for this workflow. If you choose
to share material in Claude anyway, Poo's local-scanner protections do not apply
to that conversation. The skill makes this distinction explicit.

## Privacy, terms and support

- [Plugin privacy notice](PRIVACY.md)
- [Poo website privacy](https://poo.ai/privacy/)
- [Terms](https://poo.ai/terms/)
- [Support form](https://poo.ai/support/) — do not attach exports, raw chat text or access credentials.

Poo is operated by Magichaus. This skill is intended for adults and is independent
of Anthropic. It provides review guidance, not legal advice or a guarantee of
deletion or privacy. No private export or application source is bundled.

## Publisher identity and directory review

Poo.ai is the website and product operated by Magichaus at https://poo.ai.
The plugin identifier `poo-ai`, display name `Poo.ai`, and publisher name identify
that service. This plugin is not affiliated with, endorsed by, or connected to
Calil (カーリル for AI / `caliljp`), Pomo, or Poof.

The directory's automated name-similarity check flagged those three listings.
We have retained our product's name so reviewers can assess its identity and
presentation directly. This clarification does not claim directory approval.

## License

The [MIT License](LICENSE) covers these plugin instructions and documentation.
The Poo.ai name and logo identify this integration; trademark rights are reserved.
The license does not cover Poo's application, customer exports, or third-party
provider services.
