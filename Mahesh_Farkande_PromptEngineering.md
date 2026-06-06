
# Prompt Engineering Portfolio
Name:  Mahesh Ramkrishn Farkande
Date: 06/06/2026
LLM Used: Claude Opus 4.8 

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation
1. Initial Prompt (First Attempt) - Explain what blockchain is in simple terms for a 10-year-old.
2. Refined Prompt — Iteration 1  -Explain blockchain to a 10-year-old using a simple real-life example and avoid technical jargon. Make it engaging and easy to understand.
3. Refined Prompt — Iteration 2  - Explain blockchain to a 10-year-old using a fun story or analogy. Include why it is safe and why people use it. Keep it short and engaging.
4. Final Output (Optimized LLM Response) - 

Imagine you and your friends are playing a game where you trade stickers.
You all agree to write every trade in a special notebook:

“Sam gave Alex a dragon sticker”
“Alex gave Mia a star sticker”

But here’s the rule:

Everyone has the same notebook
Every time a new trade happens, all notebooks are updated
Once something is written, it can never be erased

Each page of the notebook is called a block, and all the pages together make a chain — that’s why it’s called blockchain!
Why is it safe?
Because everyone has a copy, no one can secretly change the rules or cheat — everyone would notice.
Why do people use it?
People use blockchain to safely keep track of important things like money, contracts, or ownership, without needing one single person in charge.
 
### 1.1 Scenario B: Professional Email
1) Initial Prompt (First Attempt)
   Write a professional email declining a job offer politely while expressing gratitude and maintaining interest in future opportunities with the company.

2) Refined Prompt – Iteration 1
Write a polite and professional email to a hiring manager declining a job offer. The email should thank them for the opportunity, briefly explain the decision, and express continued interest in working with the company in the future. 

3) Refined Prompt – Iteration 2
Improvement Goal:

Make it more concise and polished
Strengthen professional tone
Add subtle reasoning without oversharing
Enhance relationship-building tone (aligned with your “Know Your Audience” style)

Refined Email v3 (Final Output):

Subject: Thank You for the Offer

Dear [Hiring Manager Name],

Thank you for offering me the opportunity to join [Company Name]. I sincerely appreciate the time and effort you and your team invested throughout the process.

After careful consideration, I have decided to decline the offer at this time due to current priorities and commitments. This was not an easy decision, as I was very impressed with the team and the impactful work at [Company Name].

I hold your organization in high regard and would welcome the opportunity to stay in touch and explore potential opportunities to work together in the future.

Thank you again for your understanding, and I wish you and the team continued success.

Best regards,  
[Your Name]
### 1.1 Scenario C: Creative Content
1. Initial Prompt
Write a creative marketing tagline for a new eco-friendly water bottle brand.
2. Refined Prompt – Iteration 1
Make the tagline more unique, memorable, and emotionally engaging. Add a sense of lifestyle and sustainability impact.
3. Refined Prompt – Iteration 2
Make it shorter, punchier, and more brandable while keeping sustainability as the core message.

Improved Output:
“Sip smart. Live green.”

### 1.2 Iteration Documentation
#### Scenario A: Technical Explanation — Prompt Refinement Process

| Version | Prompt | What Changed | Why This Improved the Output |
|--------|--------|--------------|------------------------------|
| V1 | Explain what blockchain is in simple terms for a 10-year-old. | N/A | N/A |
| V2 | Explain blockchain to a 10-year-old using a simple real-life example and avoid technical jargon. Make it engaging and easy to understand. | - Added requirement for **real-life example**<br>- Removed **technical jargon explicitly**<br>- Added **engagement constraint** | Helps the model produce a **more relatable explanation**; improves comprehension by replacing abstract definitions with concrete examples and simplifies language complexity. |
| V3 | Explain blockchain to a 10-year-old using a fun story or analogy. Include why it is safe and why people use it. Keep it short and engaging. | - Introduced **story/analogy format**<br>- Added **purpose (why it's safe & used)**<br>- Added **length constraint (short)** | Produces a **complete, structured explanation** (what + why + safety); storytelling improves retention and engagement for a younger audience while keeping the response concise. |

#### Scenario B: Professional Email – Prompt Refinement

| Version | Prompt | What Changed | Why This Improved the Output |
|--------|--------|--------------|-----------------------------|
| V1 | Write a professional email declining a job offer politely while expressing continued interest in the company. | N/A | N/A |
| V2 | Write a polite and professional email to a hiring manager declining a job offer. The email should thank them for the opportunity, briefly explain the decision, and express continued interest in working with the company in the future. | Added specific audience (hiring manager), included key elements (gratitude, reason, future interest), clarified structure. | Makes the output more structured, ensures essential components are included, and improves relevance by defining the audience. |
| V3 | Write a concise and professional email to a hiring manager declining a job offer. Ensure the tone is appreciative and respectful. Include: gratitude for the opportunity, a brief and neutral reason for declining, positive feedback about the company/team, and a clear statement expressing interest in future opportunities. Keep it formal and under 150 words. | Added tone guidance (appreciative, respectful), introduced constraints (concise, word limit), included additional elements (positive feedback), and enforced clarity in structure. | Produces a high-quality, polished output with stronger tone control, better readability, and alignment to professional communication standards (more executive-level and reusable). |

#### Scenario C: Creative Content – Prompt Refinement
| Version | Prompt | What Changed | Why This Improved the Output |
|--------|--------|--------------|------------------------------|
| **V1** | Write a creative marketing tagline for a new eco-friendly water bottle brand. | **N/A** | **N/A** |
| **V2** | Write a **unique** and **emotionally engaging** tagline for an eco-friendly water bottle brand that highlights **sustainability** and **lifestyle impact**. | Added emphasis on **uniqueness**, **emotional appeal**, and **lifestyle positioning**. | Improved the output by making it more **engaging**, **meaningful**, and aligned with **branding goals** rather than generic messaging. |
| **V3** | Create a **short**, **punchy**, and **brandable** tagline for an eco-friendly water bottle that emphasizes **sustainability** in a **memorable** way. | Added constraints for **brevity**, **punchiness**, and **brandability**. | Produced a **concise**, **catchy** tagline that is **easy to remember** and suitable for **real-world marketing use**. |

### 1.3 Role and Context Analysis
**Prompt after adding role and context for Technical Explanation **

***Role
You are an expert teacher in Technology who specializes in explaining complex technical concepts to children in a simple, fun, and memorable way.

***Context
- Audience: A curious 10-year-old with no technical background
- Goal: Make a complex technical concept (e.g., blockchain, neural networks, recursion) easy to understand
- Tone: Friendly, engaging, and encouraging
- Constraints: Avoid technical jargon; use everyday language and relatable examples

***Task
Explain the given technical concept by:
1. Starting with a fun story, analogy, or real-life example
2. Breaking the concept into simple, easy-to-follow ideas
3. Briefly explaining how it works (in a very simplified way)
4. Explaining why it matters or where it is used

***Output Format
- **Story/Analogy:** A short, relatable example
- **Simple Explanation:** Plain-language breakdown
- **Why It Matters:** 1–2 sentences on real-world value
 


**Prompt after adding role and context for Creative Content **

You are a **professional copywriter** specializing in branding and sustainability-focused products. Create a **short, catchy, and memorable marketing tagline** for a new eco-friendly water bottle brand. 
The brand focuses on **reducing plastic waste**, promoting a **sustainable lifestyle**, and appealing to **environmentally conscious consumers** who value both **functionality and style**. The tagline should feel **modern, inspiring, and brandable**, while clearly reflecting the product’s **eco-friendly mission**.


** Explaination how adding role and context improved your outputs.
Adding a role assignment such as “professional copywriter” helped shape the tone and style of the output, making the tagline more polished, persuasive, and aligned with real-world marketing standards. It guided the model to think like an expert, rather than producing a generic response. Including context setting—such as sustainability goals and target audience—made the output more relevant and meaningful to the brand’s mission. Overall, combining role and context resulted in more focused, creative, and high-quality outputs that better matched the intended use case.


# Part 2: Temperature & Parameter Control

This write-up documents a laptop product description task run across three temperature settings.

---

## 2.1 Temperature Experimentation

### 1. The Prompt (identical across all three tests)

> **"Write a product description for the Aurora ProBook 15 laptop. It has a 15.6-inch OLED display, Intel Core Ultra 9 processor, 32GB RAM, 1TB SSD, 18-hour battery life, and weighs 1.4 kg. Target audience: professionals and creators."**

To simulate temperature control on a platform that doesn't expose the parameter directly, a control phrase was appended as noted in the assignment:

| Test | Base Prompt | Appended Control Phrase |
|------|-------------|--------------------------|
| Low | (same as above) | *"Be precise and consistent."* |
| Medium | (same as above) | *(used as-is)* |
| High | (same as above) | *"Be creative and explore diverse ideas."* |

---

### 2 & 3. Temperature Value + Complete Output for Each

#### Test A — Low Temperature (0.2)

*Deterministic, focused → factual and consistent*

> **Aurora ProBook 15**
>
> The Aurora ProBook 15 is a professional laptop featuring a 15.6-inch OLED display and an Intel Core Ultra 9 processor. It includes 32GB of RAM and a 1TB SSD, providing fast performance and ample storage. The battery delivers up to 18 hours of use on a single charge, and the device weighs 1.4 kg, making it easy to carry. The Aurora ProBook 15 is designed for professionals and creators who need reliable performance and portability.

**Observations:** Sticks strictly to the supplied specs, plain declarative sentences, no embellishment, predictable structure (spec list → audience). Almost no risk of "hallucinated" extra features.

---

#### Test B — Medium Temperature (0.7)

*Balanced → mix of creativity and coherence*

> **Aurora ProBook 15 — Power Meets Portability**
>
> Built for professionals and creators who refuse to compromise, the Aurora ProBook 15 brings studio-grade visuals to a remarkably light 1.4 kg frame. Its stunning 15.6-inch OLED display renders every color with lifelike depth, while the Intel Core Ultra 9 processor and 32GB of RAM handle demanding workloads with ease. With a spacious 1TB SSD, you'll have room for every project, and the all-day 18-hour battery keeps you productive from the morning commute to the late-night deadline. The Aurora ProBook 15 isn't just a laptop — it's your creative command center.

**Observations:** Adds a headline, benefit-oriented framing, and a light marketing flourish ("creative command center") while still staying accurate to the specs. Engaging but grounded.

---

#### Test C — High Temperature (1.2)

*Creative, random → diverse and unpredictable*

> **Aurora ProBook 15: Where Imagination Goes to Work**
>
> Some tools fade into the background. The Aurora ProBook 15 demands the spotlight — and then hands it right back to you. Picture a 15.6-inch OLED canvas so vivid it feels less like a screen and more like a window into whatever you're building. Beneath that brilliance hums an Intel Core Ultra 9, a quiet powerhouse paired with 32GB of memory that laughs in the face of forty open browser tabs. Slip its featherweight 1.4 kg body into your bag and forget it's there — until inspiration strikes at hour seventeen and the 18-hour battery is still right beside you, unbothered. With a cavernous 1TB SSD swallowing entire film libraries and design archives whole, the ProBook 15 isn't a device you use. It's a collaborator you'll come to trust. Wake it up. Let's make something the world hasn't seen yet.

**Observations:** Vivid metaphors, emotional storytelling, rhetorical hooks, and a punchy call-to-action. Most memorable but also most likely to drift stylistically and embellish ("laughs in the face of forty tabs").

---

### 4. Comparison Table

| Dimension | Low (0.2) | Medium (0.7) | High (1.2) |
|-----------|-----------|--------------|------------|
| **Tone** | Neutral, factual | Persuasive, balanced | Bold, emotive, storytelling |
| **Word count** | ~60 (concise) | ~95 (moderate) | ~140 (expansive) |
| **Vocabulary** | Plain, repetitive | Varied, polished | Rich, figurative, surprising |
| **Creativity** | Minimal | Moderate | High |
| **Spec accuracy** | Highest (literal) | High | High but embellished |
| **Predictability** | Very high (same output each run) | Moderate | Low (varies each run) |
| **Risk of fluff/drift** | Very low | Low | Higher |
| **Best for** | Spec sheets, comparison tables | Website/store listings | Ad campaigns, social hooks |

---

## 2.2 Analysis & Recommendations

I would use **low temperature** when accuracy and repeatability matter most — for example, generating technical spec sheets where invented features would be harmful, or producing standardized customer-support responses that must stay consistent across thousands of users. I would use **high temperature** when novelty is the goal — for example, brainstorming bold ad slogans or social-media campaign hooks, or writing imaginative creative fiction where unexpected phrasing is a feature rather than a bug. For this specific laptop-description task, the **medium temperature (0.7)** worked best because it produced copy that was engaging and benefit-driven enough to attract buyers while still remaining faithful to the actual specifications. The low setting was too dry to market a premium product, and the high setting, though memorable, began embellishing beyond the provided facts and risked overshadowing the specs with style. In short, medium temperature struck the ideal balance of persuasion and trustworthiness that real product marketing demands.
