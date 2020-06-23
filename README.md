# proposal-holy-peace

Proposal that prevents holy wars about  code styles

# Motivation

1. Different programmers prefers different code styles because they have choice.
2. All programmers hate to read code in different style because it's hard.
3. Most programmers have to get used to a code style of the team. And they have to get used to a new style again when switching to another team.
4. Code style freedom allows to write well formatted code, but allows and worst formatted code too.
5. Most teams have to add an additional linter or formatter to the pipeline to enforce well formatting.
6. Many man hours in every team were spent and still spent to discuss about code styles and tooling.
7. Modern language supply with standard formatter (go) or prevents worst formatting at syntax level (view.tree).
8. We should add a standard way to format code that enforces one style for better reading and understanding.
9. Strict formatting can be parsed faster than lax formatting. That can improve web page initial time.

# Changes

## Enabling Holy Peace mode

In additional to "use strict" should be added a "holy peace" special literal that enables new parser that implements rules of this proposal. This literal should be at start of whole script.

```
"holy peace"
// other code
```

