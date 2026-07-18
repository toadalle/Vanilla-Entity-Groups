# Vanilla Entity Groups

Vanilla Entity Groups is a lightweight datapack that categorizes vanilla entity types into reusable groups such as **Hostile**, **Neutral**, **Passive**, and **Livestock**.

Instead of manually listing every entity type in your commands or datapacks, you can target an entire category with a single selector.

## Features

- Categorizes vanilla entity types into reusable groups.
- Simplifies entity selectors.
- No functions or scoreboards.
- Zero performance impact.
- Works anywhere entity type tags are accepted.
- Multiplayer compatible.

### Example

Instead of writing:

```mcfunction
/kill @e[type=zombie,type=skeleton,type=creeper,...]
```

you can simply write:

```mcfunction
/kill @e[type=#group:hostile]
```

The included groups work anywhere Minecraft accepts entity type tags, making commands shorter, easier to read, and easier to maintain. Whether you're building a datapack, creating an adventure map, using command blocks, or simply running commands in-game, Vanilla Entity Groups lets you target categories of vanilla entities without repeatedly maintaining long lists of entity types.

## Included Groups

- **Hostile** – Aggressive entities that attack on sight.
- **Neutral** – Entities that become hostile only under certain conditions.
- **Passive** – Peaceful entities that never attack the player.
- **Livestock** – Common farm animals and domesticated creatures.
