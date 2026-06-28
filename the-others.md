# 🧟 The Others – Complete Game Design Document

## (Non-Technical Full Version)

---

## Core Concept

A **survival / crafting / psychological drama** game in an open world (Top-Down 2D), where zombies aren't just stupid enemies. **They learn.**

You are not a superhero. You are an ordinary person trying to survive in a collapsing world. Zombies evolve. Human factions compete with you for resources. And the characters you meet aren't just "helpers" – each one carries a deep wound.

**The Essence:** The world learns. Zombies learn. Factions evolve. And you – if you don't learn, you'll die.

---

## The Story

### The Demo

You start on an abandoned street. One zombie behind you. You hear distant gunfire. You see car lights flickering on the horizon.

You run. You reach an obstacle (a parked car). The first zombie bypasses it slowly. The second bypasses it faster. The third avoids it entirely. **They're learning.**

You try to hit them. You succeed the first time. The second is harder. The third fails. **Direct combat is not a solution.**

You reach a parking lot. You run toward a car. Suddenly, a young man (Tim) jumps out from behind a nearby car. Panting. Scared. He looks back.

> **Tim:** "Go! It's not just zombies – a gang is following me!"

You get in the car. You start escaping. On the way, you see a little girl (Layla) running behind a container. She disappears. You can't save her.

The demo ends.

---

### The Full Game

The world is open. Randomly generated with a `seed`. Every game is different.

**The Ultimate Goal (optional):** Eliminate the zombies.  
- 1. Understand the zombies (analyze samples).
- 2. Hack their communication system.
- 3. Produce an antidote and lure zombies to it.
- 4. Rebuild society.

**But the player is not forced to do this.** They can live in the world forever – build a base, trade with factions, fight, flee.

**The world continues even after the player dies.** If you die, you create a new character (an heir) in the same world. You lose your equipment, but your base and some characters remain.

---

## Friendly Characters

### The Fighter – "Asad"

- **Past:** Former soldier, lonely, regrets pushing people away.
- **Motivation:** Sees the disaster as a new chance to become a different person.
- **Skills:** Advanced combat, tactical planning, training.
- **Weakness:** Avoids relationships, rushes sometimes, drinks sometimes.
- **Joining:** Prove your strength + show that emotions aren't weakness.
- **Breakdown:** Drinks alone. Pushes you away. Then apologizes.

---

### The Engineer – "Ammar"

- **Past:** His family was kidnapped by a slave gang. He feels guilty for not being there.
- **Motivation:** Save his family at any cost.
- **Skills:** Advanced crafting, repair, technical hacking, teaching.
- **Weakness:** Physically weak, hesitant sometimes, obsessive.
- **Joining:** Help him get rare resources + show interest in his family.
- **Breakdown:** Receives news about his family. Breaks down. Repeats: "If only I had been there..."

---

### The Doctor – "Sara"

- **Past:** Her family turned into zombies. She has natural immunity.
- **Motivation:** Find a cure, find her family.
- **Skills:** Advanced medicine, chemistry, zombie science, calming.
- **Weakness:** Hesitates to kill zombies (some of them), overly emotional.
- **Joining:** Help her get rare samples + respect her refusal to kill.
- **Breakdown:** Finds a zombie that looks like her daughter. Hesitates. Almost dies.

---

### The Hunter – "Shadow"

- **Past:** Lost everything, chose to live in the forest.
- **Motivation:** Live with dignity without needing anyone.
- **Skills:** Hunting, stealth, tracking, traps.
- **Weakness:** Never asks for help, unsociable.
- **Joining:** Help him without being asked + respect his privacy.
- **Breakdown:** Gets injured. Refuses your help. Whispers: "Leave me... I'm used to being alone."

---

### The Teacher – "Noor"

- **Past:** Was a teacher, saw the collapse of morality.
- **Motivation:** Build a new society on ethical foundations.
- **Skills:** Ethical leadership, negotiation, teaching, lie detection.
- **Weakness:** Too idealistic, interferes, clashes with reality.
- **Joining:** Prove you follow principles + respect ethics even in difficult circumstances.
- **Breakdown:** Discovers someone she trusted betrayed her. Cries: "Where is the good in this world?"

---

### The Teenager – "Tim" (ADHD)

- **Past:** Separated from his family, struggled in school due to his chaos.
- **Motivation:** Become strong enough to save his family.
- **Skills:** Chaotic intelligence, quick wit, connecting ideas, technological skills.
- **Weakness:** Reckless, difficulty concentrating, emotional.
- **Joining:** Listen to him + give him a chance to prove himself.
- **Breakdown:** Fails a mission. Shouts: "I'm a failure!"

---

### The Mysterious One – "Sakhr"

- **Past:** Deep trust issues (previous betrayal).
- **Motivation:** Trust someone again.
- **Skills:** Advanced stealth, intelligence gathering, silent combat, disguise.
- **Weakness:** Trusts no one, avoids relationships, keeps secrets.
- **Joining:** Save him from mortal danger + prove your worth through tests.
- **Breakdown:** After many tests, confesses: "I haven't trusted anyone in years..."

---

### The Girl – "Rana" (not from The Lone Engineer)

- **Past:** Saved herself when a gang attacked her family. Her father died in the attack.
- **Motivation:** Doesn't want to need anyone. But wants to trust again.
- **Skills:** Combat, stealth, but lacks trust in others.
- **Weakness:** Cold, independent, never asks for help.
- **Joining:** Need to prove you don't want to "protect" her – you want to cooperate.
- **Relationship with Tim:** He feels her emotions (hyper-empathy) before she admits them. Their relationship becomes deep without words.

### The Child – "Layla"

- **Past:** Lost her family. Saved by Noor.
- **Motivation:** Symbol of innocence. No combat skills.
- **Role:** Boosts group morale (reduces psychological breakdowns).
- **Danger:** If the base falls, she disappears (kidnapped or killed). This ends Noor.

---

## Game Mechanics

### Zombies – Collective Intelligence

Zombies are not stupid individuals. They are a **collective entity** that learns together.

| Stage | Days | Behavior |
| :--- | :--- | :--- |
| 1 | 1-5 | Individuals, attack only when approached |
| 2 | 6-10 | Gather, attack sources of noise |
| 3 | 11-20 | Avoid simple traps, attack from two directions |
| 4 | 21-30 | Avoid light, test fortifications |
| 5 | 31-40 | Remember your old locations, coordinate ambushes |

#### The Zombie Leader (Rare)

- **Not physically stronger.** But smarter.
- **Stands in the back.** Doesn't attack directly. Coordinates the group.
- **If killed:** The group temporarily collapses. A rare sample can be extracted from its brain.
- **How to recognize it:** A group acting with high coordination. One zombie in the back flees if you approach.

#### The Disruptor Zombie (Hard Mode Only)

- **Very rare.**
- **Function:** Changes the group's communication frequency to protect the communication system from hacking.
- **If killed:** Frequencies return to normal.

---

### Human Factions

7 types of factions, each with its own style:

| Type | Behavior | How to Deal With It |
| :--- | :--- | :--- |
| **Raiders** | Attack quickly, steal, flee | Fortify, ambush |
| **Extortionists** | Send threats, demand tribute, kidnap | Negotiate, fight, alliances |
| **Slavers** | Kidnap survivors | Free prisoners, destroy hideout |
| **Zealots** | Kill those who disagree | Fight, no negotiation |
| **Traders** | Trade, don't usually attack | Trade, protection |
| **Old Soldiers** | Organized, want control | Join, difficult fight |
| **Chaotics** | Chaotic, attack everything | Avoid, quick kill |

#### Joining a Faction

The player can join any faction. But each faction has its price:
- Resources, protection, information.
- New enemies, loss of some friendly characters, mandatory missions.

---

### Crafting

**Logic-based, not pre-made recipes.**

- **Materials:** Wood, stone, metal, plastic, glass, cloth, rubber, electronics, chemicals.
- **Tools:** 12 categories (sharp tools, long tools, solid tools, digging, cutting, primitive/modern firearms, explosives, electrical tools, medical, building, miscellaneous).
- **Templates:** 12 templates (primitive sharp tool, long sharp tool, etc.).

**Discovery:** The player discovers recipes through experimentation. If they fail, they can undo the combination at a cost (time + simple randomness).

**Chemicals:** Add sensory weapons (irritating smoke bombs, sound bombs, fluorescent paint).

---

### Hacking (Zombie Communication System)

Three layers:

| Layer | Effect |
| :--- | :--- |
| **Jamming** | Disables communication between them (each zombie becomes an individual) |
| **Confusion** | They attack each other or scatter (temporary chaos) |
| **Direction** | Attract to a specific area or repel from it |

**Advanced Devices (from Leader samples):**
- Advanced portable jammer (confuses the leader itself).
- Advanced confusion grenade (pure chaos for 30 seconds).
- Direction (attract/repel) – attracts or repels zombies in a wide range.
- Sensing – see and hear like them.

**The Disruptor (Hard Mode):** Changes frequencies to protect the communication system from hacking.

---

### Heat (Day Danger, Night Safe)

- **Zombies are active during the day** (heat increases infection).
- **Night is relatively safe** (cold slows them down).
- **Effect:** Player sleeps during the day, works at night. Or fortifies during the day.

---

### Base and Fortification

- **Choose an abandoned building** (warehouse, house, hospital).
- **Expansion:** Build additional rooms (workshop, storage, clinic, bedroom, watchtower).
- **Fortification:** Wooden fence, stone wall, electric fence, traps, watchtowers.
- **Storage:** Wooden boxes, metal boxes, shelves, refrigerators.

---

### Health and Injuries

- **100 health points.** Damage varies by difficulty.
- **Infection:** Only in hard mode (30-60% chance when bitten).
- **Permanent Disabilities:** Only in hard mode (fractures, lost finger, deep wounds).
- **Treatment:** Bandages, medicine, surgery (the doctor).

---

### Sleep and Time

- **8 hours of sleep every 24 hours.** Can't sleep more than 8 hours.
- **Can't sleep in an unsafe place.**
- **Lack of sleep = exhaustion** that reduces performance (speed, accuracy, damage).

---

### The Map

- **Minimap (circle in the corner):** Shows your immediate surroundings.
- **Large Map:** When you have a map (find or craft it), you can zoom it to fill the screen.
- **Personal Markers:** You can place markers (base, resource, danger, zombie leader).

---

### Skills

Evolve through use:
- **Combat (melee):** Every 100 hits → damage +5%, speed +5%.
- **Combat (firearms):** Every 50 hits → accuracy +5%.
- **Crafting:** Every 50 items → new recipes, faster crafting time.
- **Stealth:** Every hour in stealth → lower chance of detection.
- **Survival:** Every day you survive → your food and water needs decrease.

---

### Trading (Barter)

- **No currency.** Trade goods for goods.
- **Value:** Based on rarity (1 rifle bullet = 10 food cans).
- **Traders:** Mobile individuals or trading factions.

---

### Difficulty System

4 levels (chosen at game start):

| Level | Health | Zombie Damage | Resources | Infection | Disabilities | Saving |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Easy** | 150 | 3 | Abundant | No | No | Frequent |
| **Normal** | 100 | 8 | Medium | No | No | Medium |
| **Hard** | 80 | 15 | Rare | 30% | Rare | Sparse |
| **Very Hard** | 60 | 20 | Very Rare | 60% | Common | Very Sparse |

**Death in Hard/Very Hard mode:** New character (heir) in the same world. You lose equipment, but the base and some characters remain.

---

### World Generation (Seed)

Each world is randomly generated based on a `seed`:
- The map (building locations, roads, forests, rivers)
- Zombies (numbers, distribution, presence of leaders/disruptors)
- Factions (types, locations, leaders)
- Resources (rarity, distribution)
- Friendly characters (locations – their stories are fixed)

**Fixed:** Unique characters (Asad, Ammar, Sara, Shadow, Noor, Tim, Sakhr, Rana, Layla) – their stories don't change.

---

## Character Relationships

| Relationship | Dynamic |
| :--- | :--- |
| **Engineer + Teenager** | Collaboration (linear + networked). Two different minds making things neither could make alone. |
| **Fighter + Teacher** | Conflict (power vs principles) + potential attraction. |
| **Doctor + Hunter** | Conflict (saving vs surviving) + potential attraction. |
| **Engineer + Mysterious One** | Conflict (trust vs fear). |
| **Teenager + Mysterious One** | Admiration + potential learning. |
| **Teacher + Teenager** | Guidance + inspiration. |
| **Tim + Rana** | Hyper-empathy. He feels her emotions before she admits them. A deep relationship without words. |

---

## Endings (Optional)

| Ending | Condition |
| :--- | :--- |
| **Eliminate the Zombies** | Reach layer 4 (antidote + hacking + rebuilding). |
| **Control the Zombies** | Full hacking, use them as an army against factions. |
| **Escape** | Leave the area (to another city). |
| **Heroic Death** | Sacrifice yourself to save others. |
| **Eternal Chaos** | Destroy everything, return to zero. |

**After the ending:** Can continue playing in the new world.

---

## The Demo

**Duration:** 14 minutes.

**Scenes:**
1. Start on an abandoned street. Zombie behind you. Distant gunfire. Car lights.
2. Zombies bypass an obstacle (they're learning).
3. Combat system (hitting gradually fails).
4. Reaching the parking lot.
5. Entering the car + Tim throws materials (crafting).
6. Wiring puzzle (blue + black).
7. Gangs appear (SUV, gunfire).
8. **Layla's cameo scene** – a child runs, disappears.
9. Dialogue inside the car (3 choices affecting Tim's response).
10. Reaching the safe zone. End screen.

**What the player learns:**
- Zombies learn.
- Direct combat isn't the solution.
- The environment is a tool.
- Gangs are more dangerous than zombies.
- Characters join organically.

---

## Conclusion

**The Others** is not just another zombie game.

It's a game about **learning**.  
About how zombies learn.  
About how you learn.  
About how the characters learn to trust each other.

**The world learns. Zombies remember. Humans betray.**

And you – if you don't learn, you'll die.
