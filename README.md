<p align="center">
  <img src="ascii-portrait.png" width="720" alt="ASCII portrait">
</p>

#### [ruijie_skills](https://github.com/ruijiezh67/ruijie_skills)

Skills for Claude Code that make an AI coding agent's work checkable. Install them with `/plugin marketplace add ruijiezh67/ruijie_skills`.

| skill | what it does |
|---|---|
| **notary** | Every number the agent reports (accuracy, cost, test counts) needs a receipt: the file and line, the command output, or the calculation it came from. A checker verifies each one, and anything not measured is written N/A, never 0. |
| **decoy** | Fake test data that can't be mistaken for real: every email, phone, card number, SSN and IP comes from a range reserved by a published standard, the data comes from a seeded script, and a linter checks it. |
| **shift-change** | Hands a long session over to a fresh one: a handover with next steps, rejected paths and your corrections, then a quiz for a new agent to prove nothing was lost. |
| **runcard** | Before a training run or any costly command, shows every setting it will actually use and where each one came from, and asks once. |
| **runway** | Plans your work around Claude's usage limits, so heavy tasks don't stop halfway. |

notary and decoy are also contributed to [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) ([#1270](https://github.com/Shubhamsaboo/awesome-llm-apps/pull/1270), [#1271](https://github.com/Shubhamsaboo/awesome-llm-apps/pull/1271)).

#### [modfence](https://github.com/ruijiezh67/modfence)

See a project as modules and prompt your coding agent about one of them; edits outside that module are blocked.

#### [can-an-agent](https://github.com/ruijiezh67/can-an-agent)

Small, sourced experiments on what AI agents can and can't do: can an agent close the books, and can it post on 26 platforms.
