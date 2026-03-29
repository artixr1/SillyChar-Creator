# SillyChar-Creator
A directive for AI model to follow to create a full fledge Sillytavern compatible Card

---

I understand making a good character is hard especially if it is your first time. You probably read alot of entries of many people made on how to make a good character but still feels inadequate/lost. The solution? Ask AI to help you but that is also not as straight forward because AI need a proper instruction or *Directive* to make it able to work properly. This is where this directive goes to play and I will put this up front, This is not like a new thing, there are other people have made it too. I even borrow alot of component from [cha1latte](https://github.com/cha1latte/sillytavern-character-generator), do visit it. So, what is different of mine and the other one? 

| Feature | sillytavern-character-generator | SillyChar |
|---------|----------------|-----------------|
| **Modes** | Single mode | Quick / Guided / Brainstorm modes |
| **Description Format** | Freeform prose | Structured bracket format recommended (Appearance, Relationships, etc.) |
| **Personality Field** | Comma-separated, sentence, or psychological | Two approaches: empty (description-heavy) or deep romance-focused breakdown |
| **Speech Profile** | Embedded in personality/description | Dedicated section, same core advice |
| **first_mes Length** | 50-150 tokens, 2-3 paragraphs | 300-800+ tokens, 7-12 paragraphs (novel-quality opening) |
| **first_mes Structure** | Basic (set scene → action → hook) | Detailed 4-act structure with scene framing 「 」 |
| **Alternate Greetings** | Optional, 2-3 | Mandatory 4-8, each a full scene with arc planning |
| **NSFW Guidance** | Minimal | Dedicated section with greeting archetypes |
| **Rolecall Extension** | Not mentioned | Full specification with colors, pronouns, etc. |
| **Lorebook Generation** | Not included | Full system with position matrix, order tiers, recursion rules, entry templates |
| **Danbooru Tags** | Not included | Full positive/negative tag generation system |
| **Post-Delivery** | Token report + validation checklist | Auto-offers lorebook + Danbooru tags |
| **Extensions Field** | Explicitly forbidden | Required (Rolecall data inside) |
| **JSON Output** | With explanatory wrapper + token report | Raw JSON only, no markdown |
| **Validation Checklist** | Content + JSON checks | Same checks + post-delivery offers |

TLDR: I design my Directive towards a more full package to help with a more immersive and complete cards in one go while cha1latte's design is more simple and lighter. It is all depends on what you need for your card.

---

# Instruction
1. Download the SillyChar Creator.md
2. Paste it in your AI websites like ChatGPT, Gemini, Claude or NanoGPT
3. Choose what mode you want to use (Quick is for when you already have the char idea, Guided will help you step by step for the char and Brainstom is when you have no clue)
4. Just put a prompt of whatever you want for your character
5. Profit
