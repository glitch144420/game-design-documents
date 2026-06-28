# 🚀 The Lone Engineer – Complete Game Design Document

## (Non-Technical Full Version)

---

## Core Concept

A **psychological drama / survival game** set in space, where you play as an **Engineer** on a space station after Earth loses contact. You are not the leader. You are part of a crew of 5 people, each carrying their own guilt about the disaster.

**The Essence:** The game is not about the lost connection. It's about how humans deal with the knowledge that they are alone.

---

## The Story

### Background (The Demo)

You and Majed (a young trainee technician) go to fix a fault in the communication system. Two choices:
- **You send Majed alone** → He dies, and communications are lost.
- **You go yourself** → You fix the fault, but a secondary issue ends communications.

In both cases, communication is lost. Majed either dies or survives. The game begins here.

### The Full Game

60 days of isolation. Limited resources. A crew of 5 people (Rana, Dalia, Karim, Samer, Layan) + Majed (if alive) + Noor (Karim's assistant).

**The Central Conflict:**  
> Do we try to fix communication (risking our resources) or wait and hope (risking our hope)?

But the story isn't just about this conflict. The story is about **guilt**.

- **Rana** (the leader): Feels guilty for not leading better.
- **Layan** (resource officer): Feels guilty for failing to manage people as resources.
- **Karim** (psychologist): Feels guilty for not noticing their psychological decline.
- **Dalia** (scientist): Feels guilty for not warning more strongly.
- **Samer** (communications officer): Neglected a small fault before the disaster. Wants to make up for it at any cost.
- **Majed** (if alive): Feels guilty for not being good enough.
- **Noor**: Feels guilty for not noticing Karim's breakdown.

**There is no single villain. Everyone contributed in their own way.**

---

## Characters

### Rana – The Commander

- **Role:** Station Commander.
- **Personality:** Strict, fair, fears chaos more than death.
- **Weakness:** Fears appearing cowardly. May vote for action to prove courage.
- **Secret:** Knows the location of a hidden resource cache (farming equipment). Hides it because revealing it would mean failure as a leader.
- **Breakdown:** Becomes colder. Buries emotions instead of expressing them.

### Dalia – The Scientist

- **Role:** Physicist, analyzes signals.
- **Personality:** Curious, anxious, believes every problem has a solution.
- **Weakness:** Her confidence crumbles if she presents incomplete technical arguments.
- **Secret Project:** Was trying to prove or disprove a conspiracy theory (that Earth intentionally cut contact).
- **Breakdown:** Tries to find an argument or excuse (defending her self-confidence).

### Karim – The Psychologist

- **Role:** Psychological and medical doctor.
- **Personality:** Kind, exhausted, tries to be a rock for others.
- **Weakness:** Weakens in the face of crying or anger; votes emotionally.
- **Breakdown:** Disappears. Doesn't return to the clinic. Feels guilty for not being a support.
- **Secret:** Never talks about himself. Believes this goes against his mission.

### Samer – The Communications Officer

- **Role:** Responsible for communications.
- **Personality:** Desperate, guilty, wants to make amends.
- **Weakness:** Clings to false hope too quickly.
- **Guilt:** Neglected a small fault before the disaster. Wants to make up for it at any cost (whether Majed died or not).
- **Breakdown:** Hears voices. Talks to Majed (if dead). Exhausts himself with work.

### Layan – The Resource Officer

- **Role:** Manages food, water, energy.
- **Personality:** Cold, precise, sees people as consumption numbers.
- **Weakness:** Shuts down if emotionally threatened.
- **True Fear:** Not afraid of death. Afraid of dying with her coldness (without feeling anything real).
- **Hidden Side:** Hungry for emotion, but doesn't know how to show it.

### Majed – The Trainee Technician (if alive)

- **Role:** Maintenance technician, trainee.
- **Personality:** Ambitious, afraid, wants to prove himself.
- **Weakness:** Inexperience, fear of failure.
- **View of the Engineer:** Role model, but wants to surpass him one day.
- **Hidden Talent:** Draws what he sees from the station window.
- **Breakdown:** Afraid of being a burden. Wants to be useful at any cost.

### Noor – Karim's Assistant

- **Role:** Doctor's assistant.
- **Personality:** Quiet, observant, worries about Karim.
- **Feelings for Karim:** Love (unrequited or mutually implied). She is the only one who notices his burden.
- **Role:** "The rescuer of the rescuer" – tries to save Karim when he breaks down.

### The Engineer – You

- **Blank Slate:** No written past. Shaped through your choices.
- **Exempt** from psychological constraints (no specific exhaustion meter). But you see others breakdown.
- **Your Role:** You decide the path. You try to fix things – or let them crumble.

---

## Game Mechanics

### Main Metrics

Two visible metrics throughout the game:

| Metric | Starts At | What It Represents |
| :--- | :--- | :--- |
| **Hope** | 70 | The crew's belief in the possibility of repair or return |
| **Efficiency** | 85 | State of vital systems (power, oxygen, water, food) |

**When either metric reaches 0:**
- Hope = 0 → Rebellion and collective surrender (new path).
- Efficiency = 0 → Life support failure (rescue or stabilization path).

---

### Crew Discussions (Voting System)

The game is built on **crew discussions** (15-20 discussions). In each discussion:

1. A **situation** is presented (fault, discovery, crisis).
2. You choose an **argument** from 3 types:
   - **Technical** (numbers, calculations)
   - **Emotional** (fear, hope, solidarity)
   - **Neutral** (let's just vote)
3. Each character **votes** based on:
   - Their base tendency (wait/try)
   - Current hope
   - Relationship with you
   - Temporary psychological state
   - Emotional memory (how you treated them previously)
   - A simple dice roll (to break predictability)

**Voting Formula (for the programmer):**

> Character Vote = (Base Tendency × 2) + (Current Hope ÷ 20) + (Relationship) + (Trust ÷ 20) + (Emotional Memory) + Dice (1-3)

If the vote ≥ 10 → Votes "for trying."  
If the vote < 10 → Votes "against trying."

---

### Relationships and Trust

For each character:
- **Relationship:** From -3 to +3 (changes after each important interaction).
- **Trust:** From 0 to 100 (changes by ±5 to ±15).
- **Emotional Memory:** From -2 to +2 (last 3 important interactions).
- **Temporary Psychological State:** (grateful, exhausted, anxious, desperate, angry, confident).

**These mechanics force the player to "read" the characters.** You cannot predict their vote based on their base tendency alone. You need to know their psychological state and relationship with you.

---

### Reframing

A new psychological mechanic. In moments of crisis, you can choose dialogue that **reframes** the tragedy:

| Situation | Example of Reframing |
| :--- | :--- |
| Samer after turning Majed into fertilizer | "Majed had a purpose even when he died." |
| Dalia after a scientific error | "An error is discovering a way that doesn't work." (Edison) |
| Rana after leadership failure | "The true leader takes responsibility for the mistake." |
| Karim (through Noor) | "Coming back stronger after a breakdown is proof of strength." |
| Layan after a failed plan | "The difference between those who fail and those who are defeated." |
| Majed after a technical error | "Experience is learning from your mistakes." |

**No immediate effect.** But they plant seeds that may sprout days later (changing psychological state, preventing future breakdowns).

---

## Paths

### Open Path (Repair with Crew Help)

- **Unlocks when:** You win 3 discussions favoring action.
- **Help:** Majed (if alive) or Samer (if Majed is dead), Dalia for consultations, Layan for resources.
- **Puzzles:** 5 repair puzzles (decryption, repeater, firewall, antenna, final transmission).
- **Ending:** Ending 1 (Return with hope – the crew is with you).

### Secret Path (Repair Alone)

- **Available from the start:** You work secretly without convincing the crew.
- **Risks:** Engineer exhaustion, risk of discovery (if you fail 2 puzzles in a row).
- **Puzzles:** Same puzzles but without help (higher chance of failure).
- **Ending:** Ending 1b (Return with hope – but the crew discovers your secret work).

### Waiting Path (No Repair, Just Survival)

- **Occurs when:** You fail to unlock the open path, or choose to wait.
- **Tasks:** 6 maintenance puzzles (generator check, power rationing, revival, filter cleaning, hull inspection, air analysis).
- **Ending:** Ending 2 (Hold out until rescue – but you lose leadership).

---

## Endings

### Ending 1: Return with Hope (Successful Open Path)
- **Condition:** Open path + complete puzzles + final transmission.
- **Scene:** Earth responds. The crew is with you. But success came late.
- **Taste of Loss:** Majed didn't see this (if dead). Or "He didn't believe we'd give up yesterday" (if alive).

### Ending 1b: Return with Hope (Secret Path + Discovery)
- **Condition:** Secret path + complete puzzles + transmission before discovery.
- **Scene:** Earth responds. But the crew discovers your secret work.
- **Taste of Loss:** You succeeded. But they will never forgive you.

### Ending 2: Hold Out Until Rescue
- **Condition:** Reach 60 days with Efficiency ≥ 30.
- **Scene:** Rescue ship arrives. But Rana opens the door, not you.
- **Taste of Loss:** You survived. But leadership was taken from you.

### Ending 3: Complete Failure
- **Condition:** Any metric at 0 and the other ≤ 30.
- **Scene:** Rebellion, death, or complete collapse.
- **Taste of Loss:** Nothing. Just silence.

### Ending 4: Eternal Separation
- **Condition:** Hope = 0, Efficiency > 50.
- **Scene:** The crew votes to live in the station forever. Earth is far away.
- **Taste of Loss:** You survived. But you lost hope first.

### Ending 5: Sacrifice
- **Condition:** Both Hope and Efficiency < 20.
- **Scene:** A final choice: sacrifice yourself to save the rest.
- **Taste of Loss:** In both cases, you lose something.

### Rebellion Ending
- **Condition:** Losing 3 votes in a row.
- **Scene:** The crew rebels against you. You lose control.
- **Taste of Loss:** You are not the leader. You never were.

---

## Additional Scenes

### The Body Scene (If Majed Dies)

After Majed's death, the crew discusses what to do with his body:

| Choice | Effect |
| :--- | :--- |
| **Burial in space** | Karim +2 relationship. Layan -2. |
| **Utilize the body (fertilizer)** | Efficiency +5. Karim breaks down. Samer becomes more desperate. |
| **Cremate the body** | Everyone loses a little. No one is satisfied. |
| **Freeze (delay)** | Prolongs the pain. Karim withdraws psychologically. |

**If the player chooses "utilize the body":** Later, the "Tomato" scene – Dalia looks at the soil and whispers: "Sometimes I feel like Majed is still here. In every leaf. In every fruit."

---

### Reframing Scene (Samer After Turning Majed into Fertilizer)

> **Samer:** "Fertilizer... we turned him into fertilizer. He was human. And now he's... food for tomatoes."
>
> **Engineer's choices:**
> 1. "Yes. He was human. And now he's the reason we're alive."
> 2. "Majed had purpose even when he died. Because of him, our efficiency increased. Burying him would have made his death pointless."
> 3. "I don't know what's right. But he died. And we're alive."
> 4. "Stop thinking. Get back to work."

**Delayed effect (days later):** Samer says: "I thought about what you said... maybe you were right. Maybe he's still here. Not as a corpse. As something... useful."

---

## Game Tone

- **Primary:** Emotional (slow sadness, human moments, long silences).
- **Secondary:** Changes with the scene – tension, light despair, rare warmth, very dark humor in limited moments.

**The Goal:** Not to be just a "survival" game. To be an experience about humans, about guilt, about how to deal with knowing you're alone.

---

## Conclusion

**The Lone Engineer** is not a game about lost communication.  
It's not a game about fixing machines.  
It's not just a game about survival.

**It's a game about guilt. About leadership. About how we deal with knowing we're alone – and that we might be the cause.**

Every character carries their guilt. Every decision has a price. Every ending has a taste of loss.

**This is the game I designed.**
