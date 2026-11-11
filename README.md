# The Backlog

**From the desk to the board.**

A management game about running a company with people and AI agents, built on an open map of how work runs, floor by floor, field by field.

> **Where this stands, honestly.** There is no playable game in this repository yet. The prototypes are private while the core loop is being found and tested. What is here today is the map behind the game: the floors, the fields and the rules we think hold. If you want to see it grow, star the repository. If you think a rule is wrong, open an issue.

## Why this exists

Every company already runs on a board: tasks, projects, people placed where someone decided. Most people are cards on it. A few people play.

How work runs on the floors above you is rarely written down. You learn it by being there, or by starting on the right floor. With AI agents, execution becomes abundant and human attention becomes rare. The rules change.

**Execution is cheap now. Judgment isn't.**

Agents are the elevator. The map is what is missing.

## The idea

We think the rules of work can be written down together: an open map of how work and organizations run in the age of agents, explicit enough to be played, and open to correction by the people who do the work.

- **Play it** to explore it: try a way of working, see what it does, try again.
- **Correct it** with what you've lived: your field, your floor, the rules nobody writes down.
- **Use it** at work: to change how you work, or to start something of your own.

There is no single right way to work. The map doesn't look for the optimal one. It looks for the best ways we can find, and shows what each one costs.

The Backlog is the first game built on that map. The map is open, so it doesn't have to be the last thing built on it.

## Why a game

Like a lot of people working with agents, I kept adding tools and habits to how I work, and lost sight of the whole. I needed to see the system from above. That's a simulation. Make it fun, and it's a game.

- **You can't learn a system by reading about it.** You learn it by touching it, breaking it and trying again.
- **A simulation can't be vague.** To run, every rule has to be written down. Building the game is how the map gets explicit.
- **Failure is free.** Skip the review, ship the bug, and see what it costs in minutes instead of a quarter.
- **It used to be too expensive to build.** Agents changed that. Product teams already prototype instead of writing specs; this is the same move, at the scale of a company.

Management schools have taught with games for decades: MIT's Beer Game has made supply chains felt since the 1960s. The bar for fun is set by games like Factorio and RimWorld: systems you keep tinkering with, and people who matter.

## Two axes

The whole game fits on two axes.

**Your field is what you know. Your floor is what you decide.**

### The floors: how high you decide

Each floor takes back one question about the work, and is named after the tool that answers it.

| Floor | The question you take back | In hand |
|---|---|---|
| 8 · The Board | Who owns the company? | the company |
| 7 · The P&L | Does it pay? | a spreadsheet |
| 6 · The Org Chart | Who decides? | an org chart |
| 5 · The Playbook | By which rule? | a playbook |
| 4 · The Portfolio | Why this one? | a set of bets |
| 3 · The Roadmap | What for? | a roadmap |
| 2 · The Planner | Who, and when? | a calendar |
| 1 · The Backlog | What, and in what order? | a board |
| 0 · The Desk | How? | a ticket |

Every floor starts with a problem you have already felt. Climbing has a price, too: the higher you go, the more people turn into numbers. The game does not preach about it. It lets you feel it.

### The fields: what you know

Tech, Product and Marketing come first; Support, Design and Sales come later. Every field runs on a backlog. Job titles change; fields stay. You learn a field, not a job: the job gets delegated, the field stays yours.

**Agents extend your reach. Only you grow your capital.** With agents you can go far into a field you don't master, as long as you know what to ask. Climbing a floor once people are involved takes what can't be delegated: trust, growing people, choosing between them.

The full map, with what each floor and each field changes, is in [the rulebook](docs/rulebook.md).

## The game

You start at a desk, with a task someone else chose. Then the board is yours, and you decide what goes on it. When one person can't do it all, you plan the day. Your team works from 9 to 6; agents keep working through the night; in the morning you decide what ships.

- **Earn your methods.** Scoping, review and a day planner are bought once you have felt the problem they solve.
- **Every shortcut is free, until it isn't.** Skip the review and the bug comes back into your backlog.
- **Every number has a recipe.** You can always see why something goes up or down.
- **Keep your team in the green.** Bored people slow down. Overloaded people burn out. And you're on the team too.

Single player, in the browser. Agents in the game are simulated: no real AI runs in it. It is built in vertical slices, each one a complete little game.

**Status:** private prototypes. The first board and its methods are being played and tuned; the first three floors are being built. Nothing is playable publicly yet, and there is no release date.

## The game already exists. This is its rulebook.

Work is already a game, with floors, fields and rules nobody wrote down. The Backlog makes it visible; this repository writes its rules down. For each floor and each field, it records the question you take back, the tools, the time horizon, what good work looks like, how fast you find out, what an agent is worth there, and what you stop seeing as you climb.

Those rules should be written by the people who do the work, not guessed by one developer. Every rule we keep gets tested in play, and carries a status that says how far it has been tested.

## Whose map is this?

Most maps of a company are drawn from the top: org charts, frameworks, slides. This one is drawn from the desk, looking up. It's one developer's hypothesis about how work runs, floor by floor. The lower floors are drawn from the inside, the higher ones from models and from people who've been there. The fog marks what's still being drawn. As the game gets played and people correct it, the map changes, and every change says why.

## How this is built

This game exists because agents opened fields I couldn't work in alone: game design, sound, motion, marketing. One developer, a team of agents, and a backlog: the project runs the way the game plays. Agents do much of the execution. The choices stay human: what to build, what to cut, what is fun, what is true.

No one has worked on every floor of every field, and neither have I. That is why the map is open.

## Draw the map with us

You don't need to code. You need to know your work.

- **Star this repository.** It is the clearest signal that this is worth building. Watch its releases to hear first when something is playable.
- **Propose a cell.** One field at one floor: what gets decided there, in your work.
- **Share a rule from your work.** A real one, the kind nobody writes down.
- **Propose a field.** Your job runs on a backlog too: tell us what it holds and what good work means there.
- **Challenge a floor.** If a question, a tool or a time horizon is wrong, say so.

**Bring your agent.** If you use an AI assistant, it can help you turn what you've lived into a proposal. [AGENTS.md](AGENTS.md) tells it how this repository works, and [CONTRIBUTING.md](CONTRIBUTING.md) has a prompt you can paste. The example has to be yours; the agent only helps you write it down.

**What happens next.** What holds up goes into the rulebook, and each change links the issue it came from, so who brought it stays visible. The plan is for the game's own content (fields, floors, rules) to live in readable files too, so that a contribution can become part of the game.

## What this is not

- Not a productivity tool, even though it borrows real methods.
- Not a certification: the game trains a way of thinking, and promises nothing more.
- Not a ranking of people. You place yourself on the map, never someone else.
- Not proof. A rule that wins in the game, or that people agree with, is not yet proven at work. The rulebook says how far each rule has been tested.

## License

The map and the documentation are under [CC BY-SA 4.0](LICENSE): use them, adapt them, build on them, and share alike. Game code is not published yet.

---

Made by one developer, a team of agents, and a backlog. Everything starts with the backlog.
