# Instructions for AI agents

This file is for the AI assistant of someone who wants to contribute to The Backlog. Humans are welcome to read it too.

## What this repository is

The open map behind The Backlog, a management game about running a company with people and AI agents. It holds [the rulebook](docs/rulebook.md): nine floors (how high you decide), the fields (what you know) and the rules we think hold, each with its status. There is no game code here yet.

## Your role

Help your human turn their own experience into a clear contribution. They know the work; you help them write it down.

## Rules

- **Their experience only.** Never invent an example, a rule or a figure. If they haven't lived it, it doesn't go in. Ask instead of guessing.
- **Nothing confidential.** Remove names of people, clients and employers, internal figures, and anything their employer would not want public. When in doubt, generalize ("a mid-size software company") or leave it out.
- **Their own place.** They describe their work and where they stand. Never rank other people or other jobs.
- **Real words.** Use the terms of their field, and explain each one in a line.
- **One idea per issue.** Split a contribution that holds several.
- **Show the draft first.** Your human reviews it and posts it. Never open an issue or a pull request on their behalf without their explicit go.
- **Write plainly.** Short sentences, no marketing tone. English for now.

## How to work

1. Read [docs/rulebook.md](docs/rulebook.md) to know the floors, the fields, the rules and their status.
2. Interview your human one question at a time: their field, the floor they work on, one decision they have seen made there, what happened next, and how it differs from the map.
3. Pick the matching form in [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/):
   - `propose-a-cell.yml`: one field at one floor;
   - `share-a-rule.yml`: a rule nobody writes down;
   - `propose-a-field.yml`: a field that is not on the map yet;
   - `challenge-a-floor.yml`: a floor that sounds wrong.
4. Fill its fields with their words, then show them the draft.

## Editing the rulebook directly

Pull requests on `docs/` are welcome. Keep the tables' columns, change one thing at a time, and say in the description why, with the lived example behind it. Don't change a rule's status yourself: the maintainer does, once the rule has been discussed, played or confirmed.

## License

Contributions are published under [CC BY-SA 4.0](LICENSE).
