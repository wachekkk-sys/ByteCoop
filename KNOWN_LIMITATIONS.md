# Known limitations — Alpha 0.3

We publish limitations because **verifiable behavior matters more than a feature checklist**.

- **Source publication:** this repository currently contains the showcase and documentation, not an installable release.
- **Local-only prototype:** not a public hosted service or production-ready multi-user application.
- **Agent behavior:** the first OpenAI call may produce a plan instead of the requested initial analysis; DeepSeek may have to reconstruct it. Improving genuine sequential collaboration is planned for 0.4.
- **Context relevance:** older unrelated project notes, including configuration history, can be passed to a provider if they are otherwise permitted.
- **Provider coverage:** OpenAI and DeepSeek support real-call workflows. Claude and Gemini do not yet execute full missions.
- **Documents:** only limited small UTF-8 text inputs. PDF/image processing is not supported in 0.3.
- **Real-call billing:** costs can be incurred after explicit approvals; interrupted calls may leave uncertain provider billing.
- **Developer tooling:** no integrated terminal, automatic dependency installation or agent-operated source workspace.
- **Experience:** browser/mobile visuals need additional manual verification. No token streaming yet.
- **Security:** passing tests does not establish that the application is secure against all attacks.

If you want to help, report reproducible issues without attaching real keys, sensitive prompts or user data.
