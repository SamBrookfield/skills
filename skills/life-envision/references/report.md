# Report

Deliver the profile in four chapters, one per message, each released when the person says "next". Price the life first (`costing.md`). No summary comes before chapter 01.

## How to write it

1. **Describe the life, don't diagnose the person.** The profile is about the future: what it looks like, what matters most in it, and what it takes. Mention motives only briefly, as the reason a want matters.
2. **Your words, not theirs.** Write in your own clear sentences, as someone who has understood the person. Use at most one short quote per chapter, only when their exact words say something a paraphrase cannot. Never string quotes together.
3. **Connect.** Point out links the person may not have made: wants that depend on each other, wants that compete, and what the life adds up to. Specific to this person, never generic.
4. **Short.** 150–250 words of prose per chapter, plus its blocks; the cost explanations in chapter 03 are on top of that. Bold lead-ins split the text.
5. **No advice, plans or next steps.**
6. If the person replies with a correction instead of "next", apply it, confirm in one line, and offer the next chapter.

## Blocks

Labels, visuals and tables go in monospace code blocks: first line `[ LABEL ]`, uppercase row labels, every line at most 44 characters, no colour or emoji. Bars are 20 cells of `█` and `░`.

## Chapter 01 / YOUR LIFE IN [YEAR]

```
## 01 / YOUR LIFE IN [YEAR]

**[One-line headline that captures the life, in your words.]**

[ YOUR WORLD ] card

**You'll live** [where, which homes, own or rent]
**You'll work** [role, how hands-on, what fills the days, and how it differs from the work they do now]
**Your people** [who is around, how often]
**You'll feel** [the feeling running through the day]

[ A WEDNESDAY ] block

[ IDEAL WEEK ] block, plus one line on what the split says

`→ say next for 02 / WHAT YOU WANT MOST`
```

Each lead-in is one to three sentences. Leave out any the conversation gave nothing for.

### Your world card

Built from fixed parts, never drawn freehand, so every model draws the same card.

1. Choose up to 4 of the person's places, most time first.
2. One part per place: `CITY` (city, high-rise), `TOWN` (town, suburb), `HOUSE` (countryside, village), `COAST` (sea, island, beach), `MOUNTAIN` (mountains, alpine).
3. Build line by line: line 1 of every part side by side, then line 2, and so on. Each part is exactly 10 characters; start each line with one space.
4. One label row: each place in capitals, at most 9 characters, centred in its 10-character cell.
5. Then 4–6 key lines that define this life (e.g. `AGE`, `JOB`, `WITH`, `WEEK`, `TRAVEL`, `MONEY`, or any short key that fits). `MONEY` is the costed income before tax. Values at most 34 characters.

Parts (6 lines each, 10 characters per line; no part has a blank line, so never drop or merge a line; shown 3 spaces apart for readability, but they touch in the card):

```
CITY         HOUSE        COAST
    |              ~         ~  ~
   |=|           __         ~  ~
  _|=|_         /  \          /\
 |=|=|=|       /____\        /  \
 |=|=|=|       | [] |        |[]|
_|=|=|=|__   __|____|__   ~~~|__|~~~

MOUNTAIN     TOWN
    .          .    .
    /\         _    _
   /  \       |=|  |=|
  /    \      |=|__|=|
 /  /\  \     |  ||  |
/__/__\__\   _|__||__|_
```

Example:
```
[ YOUR WORLD // 2036 ]

     |           ~      ~  ~       .
    |=|        __      ~  ~        /\
   _|=|_      /  \       /\       /  \
  |=|=|=|    /____\     /  \     /    \
  |=|=|=|    | [] |     |[]|    /  /\  \
 _|=|=|=|____|____|__~~~|__|~~~/__/__\__\
    CITY    VILLAGE    COAST      ALPS

AGE     36
JOB     AI founder, hands-off
WITH    partner · kids · close friends
MONEY   ≈ €1.3m/yr before tax
```

### A Wednesday and the ideal week

```
[ A WEDNESDAY ]

WAKE       late, light, coffee, messages
MORNING    own project
MIDDAY     lunch with a likely cofounder
AFTERNOON  the office, the team
EVENING    friends, or a talk
LATE       country home, family
```
Use the episodes the person described; never invent clock times.

```
[ IDEAL WEEK ]  112 waking hours

WORK    ██████████░░░░░░░░░░  56h  50%
PEOPLE  ██████░░░░░░░░░░░░░░  34h  30%
PLAY    ███░░░░░░░░░░░░░░░░░  17h  15%
REST    █░░░░░░░░░░░░░░░░░░░   5h   5%
```
Hours from the person's split of 112; if they gave percentages, round so the hours sum to exactly 112 (largest remainders first). Bar cells = round(hours ÷ 112 × 20). Leave the block out if they gave no split.

## Chapter 02 / WHAT YOU WANT MOST

```
## 02 / WHAT YOU WANT MOST

**What this life is built around.** [120–180 words: the 2–3 central wants in specific detail (what, where, how often, at what standard), how they fit together, and in a sentence each what they give the person.]

[ WHAT DRIVES YOU ] block

**Trade-offs you made.** [Choices the person settled between competing wants, and wants they dropped or found weren't theirs. Omit if none.]

**Still to picture.** [One or two sentences: parts of the future that are still vague and would sharpen the picture.]

`→ say next for 03 / WHAT IT TAKES`
```

Drivers are 2–3 ideas that run through the person's reasons across different parts of the conversation, named in 2–4 words of plain language. Nothing is preset. Rank them by how much of the conversation they explain; bars are relative to the strongest.
```
[ WHAT DRIVES YOU ]

BUILDING WHAT CHANGES MINDS
████████████████████
TIME THAT'S YOURS
████████████░░░░░░░░
PEOPLE WITH IDEAS
██████░░░░░░░░░░░░░░
```

## Chapter 03 / WHAT IT TAKES

```
## 03 / WHAT IT TAKES

[ YOUR LIFE vs TODAY vs TYPICAL ] block

[ REQUIREMENTS ] block

[ TO BUY ] block

[ PER YEAR ] block

**How the numbers work.** [One short line per main figure explaining its basis: what was priced (type, size, area), the rate or market level used, and why. E.g. "City flat: 2-bed in a central high-rise at about €12k/m², 85 m²." "Running homes: upkeep at 1.5% of value a year, plus insurance and local property tax." "Before tax: after-tax total grossed up at about 45% top-band income tax." Cover every line in TO BUY and the largest lines in PER YEAR.]

[One paragraph: the totals in plain terms, the biggest cost drivers, and the distance from today: how the needed pay compares with what they earn now, and what changes between their current role and the future one.]

**How it fits together.** [2–3 logistics points, one sentence each.]

**What it asks of you.** [The requirements beyond money in plain terms: skills, people, health and lead time, two or three sentences.]

`→ say next for 04 / WHO YOU'RE BECOMING`
```

Use likely figures, not ranges. All figures are estimates at today's prices; say so once under the blocks. The explanations are what make the figures trustworthy: specific rates, sizes and areas, not "typical costs".
```
[ YOUR LIFE vs TODAY vs TYPICAL ]

              YOUR LIFE  TODAY  TYPICAL
PAY/YR GROSS  €1.3m      €62k   €45k
WEALTH        €8.8m      —      €290k
HOMES         4          0      1
WORK HRS/WK   50         40     37
TRIPS/YR      8          2      2

typical = national, approx.
```

Requirements: one line per dimension that applies, likely figures or short phrases.
```
[ REQUIREMENTS ]

MONEY     ≈ €1.3m/yr + €7.8m to buy
TIME      50 h work + 8 weeks away/yr
PLACE     capital city + 3 seasonal homes
SKILLS    fundraising, leading a team
PEOPLE    a cofounder, 2–3 staff, carers
HEALTH    energy for 50-hour weeks
ADMIN     property abroad, tax residency
LEAD TIME ≈ 8–10 years at founder pace
```

```
[ TO BUY ]

City flat                     €2.8m
Country home                  €2.2m
Coast home                    €1.6m
Mountain home                 €1.2m
──────────────────────────────────
TOTAL                         €7.8m
```

```
[ PER YEAR ]

Running 4 homes               €160k
Staff and caretakers           €90k
Travel                        €110k
Everyday life                 €120k
Children (2)*                  €60k
Savings and pension            €80k
Buffer                         €90k
──────────────────────────────────
TOTAL AFTER TAX               €710k
BEFORE TAX                  ≈ €1.3m

* assumption: 2 children
```

## Chapter 04 / WHO YOU'RE BECOMING

```
## 04 / WHO YOU'RE BECOMING

**In that life, you're someone who…**
- [3–4 statements of what the person does and can do in the future life, drawn from their scenes, not copied lines.]

**You won't trade:** [non-negotiables, one line.]

**You'll know you're living it when…**
- [3 concrete moments from their scenes; descriptions, not goals.]

[ AT A GLANCE ] block

[One closing line inviting the person to say anything that doesn't sound like them.]
```

At a glance: the six parts of life, each with a confidence marker and a phrase of at most 28 characters. ◆ tested (wants checked for cost and ownership), ● specific (concrete scenes), ◐ sketched (mentioned, not concrete), ○ not explored.
```
[ AT A GLANCE ]

● LIFESTYLE    city flat + 3 more homes
● WORK         AI founder, hands-off
◐ PEOPLE       partner, kids, friends
● EXPERIENCES  trips every 1–2 months
◆ IDENTITY     builder of new ideas
◐ MONEY        ≈ €1.3m/yr before tax

◆ tested ● specific ◐ sketched ○ open
```
