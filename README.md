<a name="start-building"></a>

<p align="center">
<img src="img/banner-ignite-26.png" alt="Microsoft Ignite 2026" width="100%"/>
</p>

# [Microsoft Ignite 2026](https://ignite.microsoft.com)

## 🔥THR996: Your Agent Has Access. Now Prove What It Did.

### Session description

An emergency override code ends up in an external mailbox. We investigate how it got there, working backwards through Microsoft Purview eDiscovery, Exchange Online, SharePoint, and Agent 365 audit records to uncover two agents, a copied document, and a manipulated safety report. Along the way, we connect the evidence, reconstruct the incident, and discover what the logs can prove and what they cannot.

### 🚀 Getting started

#### In a guided session

If you're following along during a live session:

1. Review the session overview above.
2. Follow the guided steps in the session materials.
3. Open [`instructions/`](instructions/README.md) when this session includes attendee step-by-step guidance.

#### On your own

If you're learning at your own pace:

1. Clone this repository.
2. Review the supporting materials in [`docs/`](docs/README.md).
3. Follow the session guidance in [`instructions/`](instructions/README.md), or use the linked docs-site entry point when this repository uses that pattern.

### 🎯 Learning outcomes

By the end of this session, you will be able to:

1. Follow a data leak across Microsoft 365. Use Purview eDiscovery and Exchange Message Trace to find where sensitive information appeared, trace its movement between SharePoint and Exchange, and verify external email transport.
2. Connect agent actions to the audit trail. Correlate `InvokeAgent`, `ExecuteToolBySDK`, `FileAccessed`, `FileCopied`, and `SendAs` events to reconstruct an incident timeline and distinguish the agent, shared mailbox, and recorded user identities.
3. Trace an incident back to its source. Compare conflicting documents, investigate SharePoint upload activity, and uncover how a manipulated safety report influenced subsequent agent actions without mistaking recorded activity for proof of intent.

### 💻 Technologies used

- Microsoft Copilot Studio
- Microsoft Agent 365 audit records
- Microsoft Purview Audit
- Microsoft Purview eDiscovery
- Microsoft Exchange Online
- Exchange Message Trace
- Microsoft SharePoint Online
- Outlook and SharePoint connectors

### 📚 Continue your learning

Pick your next step based on your learning style:

| Resource | What you'll get |
|----------|-----------------|
| **[Ignite 2026 Next Steps](https://aka.ms/ignite26-next-steps)** | Additional session repos and materials from Microsoft Ignite 2026 |
| **[Microsoft AI Skills Navigator](https://aka.ms/ignite26-asn)** | Discover AI skills, learning paths, and resources for your next step |
| **[Microsoft Learn](https://aka.ms/ignite26-learn)** | Official documentation and guided learning paths on these topics |
| **[Microsoft Foundry Community](https://aka.ms/MicrosoftFoundryDiscord-Ignite26)** | Connect with other learners and experts in our Discord community |

### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the topics in this session.

**GitHub Copilot CLI** — Install with:

```shell
copilot plugin install microsoftdocs/mcp
```

**VS Code** — One-click install:
[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoftdocs%2Fmcp&full=true)

For more information, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

### 👥 Content owners

<table>
<tr>
    <td align="center"><a href="https://github.com/Leprechaun91">
        <img src="https://github.com/Leprechaun91.png" width="100px;" alt="Julian Kusenberg"/><br />
        <sub><b>Julian Kusenberg</b></sub></a><br />
            <a href="https://github.com/Leprechaun91" title="GitHub">🐙</a>
            <a href="https://www.linkedin.com/in/juliankusenberg" title="LinkedIn">💼</a>
            <a href="https://sessionize.com/julian-kusenberg" title="Speaker Profile">🎤</a>
            <a href="https://kusenberg.net" title="Website">🌐</a>
    </td>
</tr></table>

Dual Microsoft MVP | Microsoft Copilot & Microsoft Purview  
Senior Consultant | SoftwareOne

### 🚀 Delivery links

- **Session:** THR996, Microsoft Ignite 2026  
  https://ignite.microsoft.com/en-US/sessions
- **Slide deck:** To be published
- **Supporting materials:** To be published
- **Recording:** To be added when available

### ⚖️ Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/default.aspx).

Any use of third-party trademarks or logos are subject to those third-party's policies.
