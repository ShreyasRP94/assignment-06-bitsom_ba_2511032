# Prompt Engineering Portfolio

Name: Shreyas Pimple

Date: 06-JUN-2026

LLM Used:ChatGPT- 5.5

This portfolio demonstrates prompt engineering techniques using ChatGPT (GPT-5.5). Multiple prompts were designed, tested, refined, and evaluated across different use cases to understand how prompt structure, context, examples, and instructions influence model outputs.

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation
**Initial Prompt**: Explain neural networks.

**Refined Prompt 1**: Explain neural networks to a 10-year-old child using simple language and examples.

**Refined Prompt 2**: You are an expert elementary school teacher.

Explain neural networks to a 10-year-old child.

Requirements:
- Use very simple language.
- Avoid technical jargon.
- Use an everyday analogy.
- Keep the explanation under 200 words.
- End with a fun real-world example showing how neural networks help people.

**Final Output from LLM:** Imagine your brain is like a team of tiny helpers. Each helper looks at a small piece of information and passes it to the next helper. Together, they make a decision.

A neural network works in a similar way inside a computer. It has many tiny digital helpers that work together to recognize patterns and solve problems.

Think about learning to recognize cats. At first, the computer may not know what a cat looks like. But after seeing thousands of cat pictures, it starts noticing things like ears, eyes, whiskers, and tails. Over time, it gets better at identifying cats.

Just like you learn from practice, neural networks learn from lots of examples.

Neural networks help people every day. They can recognize faces in photos, suggest videos you might like, and even help doctors find diseases earlier.

### 1.1 Scenario B: Professional Email

**Initial Prompt**: Write an email declining a job offer.

**Refined Prompt 1**: Write a professional email declining a job offer while thanking the company.

**Refined Prompt 2**: You are an experienced HR professional.

Write a professional email declining a job offer.

Context:
- The candidate appreciates the offer.
- The candidate has accepted another opportunity.
- The candidate wants to maintain a positive relationship.
- The candidate remains interested in future opportunities with the company.

Requirements:
- Professional and respectful tone.
- 150-200 words.
- Express gratitude.
- Clearly decline the offer.
- Mention interest in staying connected.

**Final Output from LLM:** 

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your organization. I sincerely appreciate the time and effort invested by you and the interview team throughout the recruitment process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. Therefore, I must respectfully decline your offer.

This was not an easy decision, as I was genuinely impressed by the company's culture, vision, and the professionalism demonstrated throughout the hiring process.

I would like to express my gratitude for your confidence in my abilities and for the opportunity to learn more about your organization. I hope to stay connected and would welcome the possibility of exploring future opportunities together should our paths cross again.

Thank you once again for your consideration. I wish you and your team continued success.

Kind regards,

Shreyas Pimple

### 1.1 Scenario C: Creative Content

**Initial Prompt**: Create a tagline for an eco-friendly water bottle.

**Refined Prompt 1**: Create a catchy and memorable tagline for a premium eco-friendly water bottle brand.

**Refined Prompt 2**: You are an award-winning advertising copywriter.

Create 10 marketing taglines for a premium eco-friendly water bottle brand.

Context:
- Target audience: environmentally conscious young professionals.
- Brand values: sustainability, style, and innovation.
- Tone: modern, inspiring, and memorable.

Requirements:
- Maximum 8 words per tagline.
- Avoid clichés.
- Make each tagline unique.

**Final Output from LLM:** 

1. Drink Smart. Leave Less Behind.

2. Hydration with a Smaller Footprint.

3. Refill Today. Protect Tomorrow.

4. Style Meets Sustainability.

5. Carry Water. Carry Change.

6. Every Sip Shapes the Future.

7. Sustainable by Design.

8. Drink Clean. Live Green.

9. Better Bottles for a Better Planet.

10. Hydrate Responsibly.

### 1.2 Iteration Documentation

**Scenrario A : Technical Explanation**

| Version | Prompt                                                                             | What Changed                                       | Why This Improved the Output                           |
| ------- | ---------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------ |
| V1      | Explain neural networks.                                                           | N/A                                                | N/A                                                    |
| V2      | Explain neural networks to a 10-year-old child using simple language and examples. | Added audience and simplicity requirements.        | Produced a more understandable explanation.            |
| V3      | Added expert teacher role, analogy requirement, word limit, and fun example.       | Added role assignment and structured instructions. | Improved clarity, engagement, and age appropriateness. |

**Scenario B: Professional Email**

| Version | Prompt                                                                            | What Changed                            | Why This Improved the Output                   |
| ------- | --------------------------------------------------------------------------------- | --------------------------------------- | ---------------------------------------------- |
| V1      | Write an email declining a job offer.                                             | N/A                                     | N/A                                            |
| V2      | Write a professional email declining a job offer while thanking the company.      | Added professionalism and gratitude.    | Improved tone and courtesy.                    |
| V3      | Added HR role, candidate context, future interest, tone, and length requirements. | Added context and detailed constraints. | Produced a realistic, polished business email. |


**Scenario C: Creative Content**

| Version | Prompt                                                                               | What Changed                                | Why This Improved the Output                              |
| ------- | ------------------------------------------------------------------------------------ | ------------------------------------------- | --------------------------------------------------------- |
| V1      | Create a tagline for an eco-friendly water bottle.                                   | N/A                                         | N/A                                                       |
| V2      | Create a catchy and memorable tagline for a premium eco-friendly water bottle brand. | Added brand positioning.                    | Generated stronger marketing language.                    |
| V3      | Added copywriter role, target audience, brand values, tone, and output constraints.  | Added role assignment and business context. | Produced creative, targeted, and differentiated taglines. |


### 1.3 Role and Context Analysis

Role assignment significantly improved the quality of responses by guiding the model to adopt the expertise and communication style appropriate for the task. In Scenario A, assigning the role of an elementary school teacher resulted in a more engaging and age-appropriate explanation. In Scenario C, assigning the role of an advertising copywriter produced more creative and marketable taglines.

Context setting further enhanced output quality by providing background information about the audience, objectives, and constraints. For the job-offer email, contextual details helped generate a realistic professional response that balanced gratitude, rejection, and future interest. Overall, combining role assignment with contextual information reduced ambiguity and produced outputs that were more accurate, relevant, and aligned with the intended purpose.


## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

**Selected Task**

Create a short story opening (2–3 sentences).

**Base Prompt** : Write the opening of a short story in 2-3 sentences about a mysterious door that appears overnight in a small town.

**Low Temperature (0.2)**

Prompt Used : Write the opening of a short story in 2-3 sentences about a mysterious door that appears overnight in a small town. Be precise and consistent.

Temperature: 0.2

Output : When the residents of Maple Creek woke up on Monday morning, they found a wooden door standing alone in the center of the town square. No one knew where it had come from, and no buildings nearby were missing a door. By noon, the entire town was gathered around it, searching for answers.

**Medium Temperature (0.7)**

Prompt Used : Write the opening of a short story in 2-3 sentences about a mysterious door that appears overnight in a small town.

Temperature: 0.7

Output : The door appeared sometime between midnight and dawn, standing silently beside the old fountain in the middle of town. Its dark blue paint shimmered strangely in the morning sunlight, and no one could remember seeing it before. By evening, rumors about what lay behind it had spread faster than the town newspaper.

**High Temperature (1.3)**

Prompt Used : Write the opening of a short story in 2-3 sentences about a mysterious door that appears overnight in a small town. Be creative and explore diverse ideas.

Temperature: 1.3

Output : On the morning the lavender-colored door arrived, every clock in Willow Bend had stopped at exactly 3:17 a.m. Tiny golden moths circled its brass handle, whispering sounds that resembled forgotten songs, while strange footprints appeared in spirals around it. Nobody dared open it, yet everyone dreamed about what waited on the other side.

**Comparison Table**

| Aspect         | Low Temperature   | Medium Temperature | High Temperature        |
| -------------- | ----------------- | ------------------ | ----------------------- |
| Language Style | Simple and direct | Descriptive        | Highly imaginative      |
| Creativity     | Limited           | Moderate           | Extensive               |
| Story Elements | Realistic         | Some mystery       | Strong fantasy elements |
| Consistency    | Very high         | High               | Moderate                |
| Originality    | Moderate          | Good               | Excellent               |


### 2.2 Analysis & Recommendations

Low temperature settings are most useful when accuracy, consistency, and reliability are important. Two common use cases are generating SQL queries and creating technical documentation, where factual correctness is more important than creativity. Because the model produces more deterministic outputs, the results are easier to reproduce and verify.

High temperature settings are most useful when generating creative content and brainstorming new ideas. Two common use cases are writing stories and creating advertising or marketing slogans, where originality and diversity are desirable. Higher temperatures encourage the model to explore less common patterns and produce more varied responses.

For this experiment, the medium temperature (0.7) produced the best result. It generated an engaging story opening with descriptive details while maintaining logical coherence. The low temperature output was accurate but somewhat plain, whereas the high temperature output was highly imaginative but less predictable. Therefore, the medium setting provided the best balance between creativity and readability.


## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

**Selected Problem**

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

**Without Chain-of-Thought**

Prompt : A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Provide only the final answer.

LLM Output : 172 employees

**With Chain-of-Thought**

Prompt : A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations.

Let's solve this step by step.

Show all calculations clearly before giving the final answer.

LLM Output : 

Engineering employees:

60% of 150 = 90

Sales employees:

25% of 150 = 37.5

Operations employees:

150 − 90 − 37.5 = 22.5

New engineering hires:

20% of 90 = 18

New sales hires:

10% of 37.5 = 3.75

Total new hires:

18 + 3.75 = 21.75

Total employees after hiring:

150 + 21.75 = 171.75

Rounded to the nearest whole employee:

172 employees

**Comparison**

The non-chain-of-thought prompt produced only the final answer, making it impossible to verify how the model arrived at the result. The chain-of-thought prompt generated intermediate calculations and reasoning steps, improving transparency and making it easier to identify potential mistakes. Chain-of-thought prompting is especially useful for mathematical, logical, and multi-step business problems because it encourages structured reasoning. One limitation is that it increases response length and may occasionally include unnecessary intermediate details for simple problems.

### 3.2 Few-Shot Prompting

**Step 1: Zero-Shot Attempt**

Prompt : 

Classify each customer review as Positive, Negative, or Neutral.

Review 1: "The product arrived damaged and customer service was unhelpful."

Review 2: "Works as expected, nothing special but does the job."

Review 3: "Absolutely love this! Best purchase I've made all year!"

Review 4: "The quality is okay but slightly overpriced for what you get."

Review 5: "Terrible experience, would not recommend to anyone."

Zero-Shot Results

| Review | Classification |
| ------ | -------------- |
| 1      | Negative       |
| 2      | Neutral        |
| 3      | Positive       |
| 4      | Negative       |
| 5      | Negative       |

**Step 2: Few-Shot Attempt**

Prompt :

Classify customer reviews as Positive, Negative, or Neutral.

Examples:

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Review: "Excellent quality and fast delivery."
Sentiment: Positive

Review: "Customer support never responded to my complaint."
Sentiment: Negative

Now classify the following reviews:

Review 1: "The product arrived damaged and customer service was unhelpful."

Review 2: "Works as expected, nothing special but does the job."

Review 3: "Absolutely love this! Best purchase I've made all year!"

Review 4: "The quality is okay but slightly overpriced for what you get."

Review 5: "Terrible experience, would not recommend to anyone."

Few-Shot Results

| Review | Classification |
| ------ | -------------- |
| 1      | Negative       |
| 2      | Neutral        |
| 3      | Positive       |
| 4      | Neutral        |
| 5      | Negative       |


**Step 3: Analysis**

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Negative         | Neutral         | Neutral       | Yes       |
| 5        | Negative         | Negative        | Negative      | No        |


**Discussion**

Few-shot prompting is most useful when a task requires consistent interpretation, formatting, or classification rules that may not be obvious from the prompt alone. By providing examples, the model can infer the desired pattern and apply it to new inputs more accurately. Few-shot prompting is particularly valuable for sentiment analysis, information extraction, document classification, and domain-specific tasks where subtle distinctions need to be learned from examples.