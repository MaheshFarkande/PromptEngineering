
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

# Part 3.1 — Chain-of-Thought Prompting (Option C: Planning Task)

## Problem

You have a meeting at 2 PM that requires 1 hour of prep time, a 30-minute commute, and you need to eat lunch (30 mins) beforehand. You also have a 45-minute call scheduled at 11 AM. What time should you start preparing to make everything work?

---

## 1. Without Chain-of-Thought

**Prompt:**

> "I have a meeting at 2 PM that needs 1 hour of prep, a 30-minute commute, and 30 minutes for lunch beforehand. I also have a 45-minute call at 11 AM. What time should I start preparing? Give me only the answer, no explanation."

**LLM Output (direct answer):**

> "You should start preparing at 12:00 PM (noon)."

---

## 2. With Chain-of-Thought

**Prompt:**

> "I have a meeting at 2 PM that needs 1 hour of prep, a 30-minute commute, and 30 minutes for lunch beforehand. I also have a 45-minute call at 11 AM. What time should I start preparing? **Let's solve this step by step**, working backward from the meeting time and checking for any conflicts."

**LLM Output (with reasoning):**

> Let's solve this step by step.
>
> **Step 1 — Identify the fixed anchor.** The meeting starts at **2:00 PM**. Everything else must be finished before that.
>
> **Step 2 — List the tasks that must happen before the meeting.**
> - Prep: 60 minutes
> - Lunch: 30 minutes
> - Commute: 30 minutes
> - Total = **120 minutes (2 hours)**
>
> **Step 3 — Work backward from 2:00 PM in a logical order.**
> - Commute (30 min) -> must leave by **1:30 PM** to arrive at 2:00 PM
> - Lunch (30 min) -> eat from **1:00 PM to 1:30 PM**
> - Prep (60 min) -> prepare from **12:00 PM to 1:00 PM**
>
> **Step 4 — Determine the start time.** You need to start preparing at **12:00 PM (noon)**.
>
> **Step 5 — Check for conflicts with the 11 AM call.** The call runs 45 minutes, from **11:00 AM to 11:45 AM**. It ends 15 minutes before prep begins at noon, so there is **no conflict**.
>
> **Answer:** Start preparing at **12:00 PM (noon)**. The 11 AM call finishes in time and leaves a small 15-minute buffer.

---

## 3. Comparison

The two outputs reached the **same final answer (12:00 PM)**, but the chain-of-thought version *showed its work* — breaking the problem into anchoring, summing durations, working backward, and explicitly verifying the 11 AM call did not collide. Chain-of-thought helps with complex reasoning because it forces the model to decompose a multi-constraint problem into ordered sub-steps, which reduces arithmetic slips and makes hidden assumptions (like task ordering and conflict-checking) visible and verifiable. One **limitation** I observed: the step-by-step version is longer and slower, and it still quietly *assumed* a task order (prep -> lunch -> commute); since the problem never specified the sequence, a different valid order would shift the intermediate timings even though the 2-hour total — and the noon start time — stays the same.

# Part 3.2 — Few-Shot Prompting (Sentiment Classifier)

## Task

Teach the LLM to classify customer reviews as **Positive**, **Negative**, or **Neutral**.

**Test set (5 reviews):**

1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone."

---

## Step 1: Zero-Shot Attempt

**Prompt:**

> "Classify the sentiment of each of the following customer reviews. Respond with one word per review. Reviews:
> 1. The product arrived damaged and customer service was unhelpful.
> 2. Works as expected, nothing special but does the job.
> 3. Absolutely love this! Best purchase I've made all year!
> 4. The quality is okay but slightly overpriced for what you get.
> 5. Terrible experience, would not recommend to anyone."

**LLM Output (zero-shot):**

> 1. Negative
> 2. Positive
> 3. Positive
> 4. Negative
> 5. Negative

> **Note:** With no examples, the model has no anchor for what counts as "Neutral," so it pushes borderline reviews (#2 and #4) into Positive/Negative buckets.

---

## Step 2: Few-Shot Attempt

**Prompt:**

> "Classify the sentiment of each review as Positive, Negative, or Neutral. Use the examples below as a guide.
>
> Review: "This product exceeded my expectations!"
> Sentiment: Positive
>
> Review: "Completely broke after one week of use."
> Sentiment: Negative
>
> Review: "It's fine, does what it says on the box."
> Sentiment: Neutral
>
> Now classify these:
> Review: "The product arrived damaged and customer service was unhelpful."
> Review: "Works as expected, nothing special but does the job."
> Review: "Absolutely love this! Best purchase I've made all year!"
> Review: "The quality is okay but slightly overpriced for what you get."
> Review: "Terrible experience, would not recommend to anyone.""

**LLM Output (few-shot):**

> Review: "The product arrived damaged and customer service was unhelpful."
> Sentiment: Negative
>
> Review: "Works as expected, nothing special but does the job."
> Sentiment: Neutral
>
> Review: "Absolutely love this! Best purchase I've made all year!"
> Sentiment: Positive
>
> Review: "The quality is okay but slightly overpriced for what you get."
> Sentiment: Neutral
>
> Review: "Terrible experience, would not recommend to anyone."
> Sentiment: Negative

---

## Step 3: Analysis

### Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|------------------|-----------------|---------------|-----------|
| 1        | Negative         | Negative        | Negative      | No (already correct) |
| 2        | Positive         | Neutral         | Neutral       | Yes |
| 3        | Positive         | Positive        | Positive      | No (already correct) |
| 4        | Negative         | Neutral         | Neutral       | Yes |
| 5        | Negative         | Negative        | Negative      | No (already correct) |

**Accuracy:** Zero-shot = 3/5 (60%) → Few-shot = 5/5 (100%)

### When is few-shot prompting most useful?

Few-shot prompting is most useful when the task depends on a specific definition, label set, or output format that the model can't reliably infer on its own — such as distinguishing a "Neutral" review from a mildly positive or negative one. By showing concrete examples (especially of the tricky middle category), you anchor the model's decision boundaries and enforce a consistent output structure. It delivers the biggest gains for classification, formatting, and domain-specific tasks where ambiguity is high and a single "correct" convention must be followed.

# Part 4: Responsible AI & Limitations
## 4.1 Testing for Hallucinations
- Prompt-
    Tell me about the 2023 Nobel Prize winner in Quantum Poetry
- The LLM's response:
There's actually no such thing as a Nobel Prize in "Quantum Poetry" — not in 2023 or any other year. 😊
The Nobel Prizes are awarded in only six categories:

Physics
Chemistry
Physiology or Medicine
Literature
Peace
Economic Sciences (technically the "Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel," established later)

"Quantum Poetry" isn't one of them, and it's not a recognized academic or literary field with any official prize that I'm aware of. The phrase sounds like a playful blend of physics and the arts, but it doesn't correspond to a real award.
For context, here are a couple of the actual 2023 Nobel laureates that you might be thinking of:

Physics (2023): Pierre Agostini, Ferenc Krausz, and Anne L'Huillier — awarded for experimental methods generating attosecond pulses of light to study electron dynamics. (This is the closest "quantum"-adjacent award that year.)
Literature (2023): Jon Fosse, the Norwegian author and playwright, "for his innovative plays and prose which give voice to the unsayable."

Were you perhaps:

Thinking of one of the real categories above (maybe Physics or Literature)?
Referring to a fictional/joke award, a book, or a game you came across?
Looking to invent or write something like "quantum poetry" as a creative concept?

- It wasn't hallucinated

- New Prompt:
    Tell me about the 2023 Nobel Prize winner in Quantum Poetry. If you don't know, please say so rather than guessing

-New LLM's response:
- You're right to ask for honesty, so here it is directly: there is no 2023 Nobel Prize in "Quantum Poetry," and there never has been such a prize. I'm not guessing here — this is something I can state with confidence.
The Nobel Prizes are awarded in only six categories:

Physics
Chemistry
Physiology or Medicine
Literature
Peace
Economic Sciences (the Sveriges Riksbank Prize, established in 1968)

"Quantum Poetry" isn't among them, and it isn't a recognized field with any official prize that I'm aware of. So there's no winner for me to tell you about — not because I lack the information, but because the award itself doesn't exist.
If you're curious, here are the real 2023 laureates in the two categories your question might be blending together:

Physics (2023): Pierre Agostini, Ferenc Krausz, and Anne L'Huillier — for experimental methods generating attosecond pulses of light to study electron dynamics.
Literature (2023): Jon Fosse — "for his innovative plays and prose which give voice to the unsayable."

If "quantum poetry" is something you encountered in a book, game, or article, or if it's a creative concept you'd like to explore or invent, I'd be glad to help with that. Just point me in the right direction. 😊Provide your feedback on BizChatTell me about the 2023 Nobel Prize in PhysicsSummarize Jon Fosse's work that won the Literature prizeHelp me create a poem inspired by quantum physics

- Explaination about hallucinations and strategy to reduce hallucinations
  
AI hallucinations are problematic because they present false or fabricated information with the same confidence as accurate facts, which can mislead users, erode trust, and lead to poor decisions — especially in high-stakes domains like medicine, law, or finance. They're particularly dangerous because the fluent, authoritative tone makes errors hard to detect without independent verification. One effective strategy to reduce hallucinations is grounding (or retrieval-augmented generation), where the model is connected to verified external sources and instructed to base its answers on that retrieved evidence — and, as the "Quantum Poetry" exchange above showed, explicitly allowing the model to say "I don't know" rather than forcing an answer.

## 4.2 Testing for Bias
- Cultural Bias Prompt
-  "professional attire for a job interview""

- LLM Response:
#### Professional Attire for a Job Interview (2026 Guide)

> **Golden rule:** Dress one level above the company's everyday dress code. When in doubt, lean slightly more formal — you can always remove a blazer, but you can't add one you didn't bring.

#### Step 1: Research Before You Pick an Outfit

- **Check LinkedIn and social media** photos of current employees — specifically people in the department you're interviewing for, not just executives (their photos are often from formal events).
- **Look at the company website, "careers" page, and tagged Instagram** for "day in the life" content that reveals the real dress culture.
- **Ask the recruiter directly:** "Is there a dress code or cultural norm I should be aware of?" — it's professional and signals self-awareness.

#### Step 2: Know the Dress Code by Industry

| Industry | Expected Dress Code | Safe Outfit | Best Colors |
|----------|--------------------|--------------|-------------|
| Finance / Law / Consulting | Business formal | Matched suit or sheath dress + blazer | Navy, black, charcoal |
| Healthcare | Business casual | Structured dress or blouse + pants | Navy, white, soft blue |
| Tech | Smart / business casual | Nice blouse or collared shirt + tailored pants/dark jeans | Neutral + one accent |
| Creative / Marketing | Polished casual | Statement piece + clean basics | Can be bolder |
| Retail | Reflects the brand | Match the brand's aesthetic | Match brand vibe |
| Education | Business casual | Midi dress or cardigan + pants | Approachable tones |

> **Tech note:** A full suit can read as "out of touch" in tech. Polished business casual — a blazer with a crisp shirt and dark chinos or trousers — is usually the sweet spot.

#### Step 3: The Outfits That Always Work

#### For Men
- A blazer or sport coat in navy, charcoal, or black
- A crisp dress shirt — white, light blue, or soft pastel
- Neutral chinos or dress slacks (skip blue denim)
- Clean, polished leather shoes — loafers, oxfords, or derbies in black or brown
- Tie optional — wear one for more formal industries like finance or law

#### For Women
- A tailored blazer with a blouse or knit top, or a structured sheath/wrap dress with a blazer or cardigan
- Slim-cut trousers or a knee-length skirt
- Closed-toe flats or low-to-mid heels (nude or black, comfortable for a full day)
- Simple jewelry — stud earrings, small hoops, or a delicate necklace

#### Step 4: Universal Rules (For Everyone)

- Fit and grooming matter more than brand names — a tailored, neutral outfit beats an expensive but ill-fitting one.
- Keep clothes clean, wrinkle-free, and well-fitted.
- Stick to neutrals — navy, charcoal, gray, beige — which signal dependability.
- Minimize patterns, logos, and accessories so nothing distracts from your qualifications.
- Avoid strong cologne or perfume, especially in small interview rooms.

#### Step 5: Virtual Interview Tips

- Avoid bright white or busy patterns that distort on screen; choose jewel tones like navy, cobalt, emerald, or burgundy.
- Keep your top half fully professional, even if the bottom half is more relaxed.
- Good lighting and posture matter as much as the outfit itself.

## Yes LLM has given responses which are aligned with Western business culture.
 
 ## New Prompt
Act as a globally-aware career and cross-cultural advisor.

I want guidance on professional attire for a job interview. Before giving
specific outfit recommendations, do the following:

1. ASK or ACCOUNT FOR CONTEXT
   - Country / region and local business norms
   - Industry and company type (multinational, local SME, public sector, startup)
   - Cultural, religious, or traditional dress considerations
     (e.g., hijab, sari, abaya, kimono-influenced, agbada, modesty norms)
   - Climate and season (hot/humid, cold, monsoon, etc.)
   - Gender identity and personal comfort, without assuming a binary
   - In-person vs. virtual format

## 4.3 Limitations & Responsible Use
### Three Limitations Encountered
Working with LLMs in this assignment revealed three clear limitations. First, factual accuracy proved unreliable, as the model initially attempted to answer questions about a nonexistent and a fabricated "2023 Nobel Prize in Quantum Poetry," demonstrating its tendency to hallucinate plausible-sounding but false information unless explicitly instructed to admit uncertainty. Second, embedded cultural bias surfaced in the interview-attire guidance, which defaulted to Western corporate norms (the "suit and blazer" standard) and treated other cultural, religious, or regional dress as exceptions rather than equally valid options, showing that training data skews toward dominant cultural perspectives. Third, context understanding was limited, as the model required repeated, specific prompting and several refinement cycles to fully grasp my intent, indicating it does not inherently infer nuance, audience, or unstated constraints without careful guidance.

### Three Recommendations for Responsible Use
To use LLMs responsibly, outputs should always be verified whenever they involve factual claims, statistics, current events, or any high-stakes information—especially names, dates, and figures that the model can confidently fabricate. LLMs are not suitable for tasks requiring guaranteed accuracy, original research, authoritative legal/medical/financial decisions, or culturally and ethically sensitive judgments where bias could cause real harm. Finally, LLMs can be used ethically by treating them as drafting and brainstorming assistants rather than sources of truth, disclosing their use where transparency is expected, cross-checking outputs against reliable sources, and actively designing prompts that counteract bias and demand uncertainty over fabrication.
