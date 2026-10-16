# GitHub Copilot on GitHub.com

GitHub Copilot on GitHub.com brings repository assistance into the browser. Depending on your plan and organization settings, you can use it to investigate code, discuss possible changes, delegate implementation, review pull requests, and automate recurring work.

For a comparison of Copilot surfaces, see [Where to use GitHub Copilot](https://docs.github.com/en/copilot/get-started/where-to-use-github-copilot).

## Ways to work with Copilot

- **Chat** can answer questions about a repository, explain code, propose fixes, and help plan tests. You can refine a request in follow-up messages.
- **Copilot cloud agent** can explore a repository and carry out multi-step coding work in an ephemeral cloud environment. It can edit files and run the project's checks.
- **Code review** can analyze pull request changes and offer feedback or fixes. You can request a review manually or configure automatic reviews.
- **Automations** can run cloud-agent tasks on a schedule or in response to repository events. They are managed from the repository's Agents tab and are available for eligible private and internal repositories.
- **GitHub Agentic Workflows** describe repository tasks in Markdown and run them as GitHub Actions workflows, using Copilot or another supported coding agent.

You can begin a task from chat, the agents panel, or an issue or pull request. Cloud agent can prepare commits and push its branch; you can inspect and refine the result before opening a pull request. For security alerts, eligible alerts can also be assigned to Copilot through a security campaign.

## Context and sessions

Chat and cloud-agent work can share context when you start an agent task from a chat. You can continue discussing an active task while the agent works. Copilot Chat can also use relevant agent session logs to answer questions about Copilot-created pull requests.

Session logs show the work performed, but they are not a substitute for reviewing and testing the result. Teammates with repository access can follow shared sessions and pull requests.

With remote control enabled, a Copilot CLI session can be monitored from GitHub.com while it continues running on its original machine. GitHub.com can also answer questions about synced sessions you started across supported Copilot surfaces, provided syncing is enabled and allowed by organizational policy.

This active-session context is separate from [Copilot Memory](https://docs.github.com/en/copilot/concepts/agents/copilot-memory), which retains information across sessions.

## Customization and models

Copilot can be customized with personal, repository, or organization instructions. Other options include Copilot Spaces for shared reference material, custom agents and skills for specialized delegated tasks, MCP servers for additional tools and data, and hooks for actions during agent work. See [Customize Copilot](https://docs.github.com/en/copilot/how-tos/copilot-on-github/customize-copilot).

Available AI models depend on your plan, account policies, and how you start a cloud-agent task. See [supported AI models](https://docs.github.com/en/copilot/reference/ai-models/supported-models) and [changing the cloud-agent model](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/cloud-agent/changing-the-ai-model).

## Public-code references

Copilot may produce code resembling code in public GitHub repositories. When a match is identified, chat responses or agent session logs can provide a reference to the repository and available licensing information. The reference can help you evaluate the suggestion; the public-code index is refreshed periodically and may not reflect recent moves or deletions.

## Access and limitations

Feature availability is controlled by plan and organization policy. Repository administrators can disable cloud agent, and incompatible repository rules may prevent it from working. Cloud agent works only with GitHub-hosted repositories and is limited to the repository and branch associated with a task. A task can open one pull request, and each session has a maximum duration of 59 minutes.

Copilot output can be incorrect or insecure. Review and test generated changes before using them. Learn more about [responsible use of Copilot agents](https://docs.github.com/en/copilot/responsible-use/agents), [cloud-agent risks and mitigations](https://docs.github.com/en/copilot/concepts/agents/cloud-agent/risks-and-mitigations), and [cloud-agent access management](https://docs.github.com/en/copilot/concepts/enterprise/cloud-agent-access).

## Further reading

- [GitHub Copilot on GitHub](https://docs.github.com/en/copilot/how-tos/copilot-on-github)
- [Copilot cloud agent](https://docs.github.com/en/copilot/how-tos/use-copilot-agents/cloud-agent)
- [Copilot Cookbook](https://docs.github.com/en/copilot/tutorials/copilot-cookbook)
- [Copilot integrations](https://docs.github.com/en/copilot/concepts/tools/about-copilot-integrations)
- [Copilot usage metrics](https://docs.github.com/en/copilot/concepts/billing-and-usage/copilot-usage-metrics/copilot-metrics)
