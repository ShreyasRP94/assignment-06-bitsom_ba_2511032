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

Scenrario A : Technical Explanation

| Version | Prompt                                                                             | What Changed                                       | Why This Improved the Output                           |
| ------- | ---------------------------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------ |
| V1      | Explain neural networks.                                                           | N/A                                                | N/A                                                    |
| V2      | Explain neural networks to a 10-year-old child using simple language and examples. | Added audience and simplicity requirements.        | Produced a more understandable explanation.            |
| V3      | Added expert teacher role, analogy requirement, word limit, and fun example.       | Added role assignment and structured instructions. | Improved clarity, engagement, and age appropriateness. |

Scenario B: Professional Email

| Version | Prompt                                                                            | What Changed                            | Why This Improved the Output                   |
| ------- | --------------------------------------------------------------------------------- | --------------------------------------- | ---------------------------------------------- |
| V1      | Write an email declining a job offer.                                             | N/A                                     | N/A                                            |
| V2      | Write a professional email declining a job offer while thanking the company.      | Added professionalism and gratitude.    | Improved tone and courtesy.                    |
| V3      | Added HR role, candidate context, future interest, tone, and length requirements. | Added context and detailed constraints. | Produced a realistic, polished business email. |


Scenario C: Creative Content

| Version | Prompt                                                                               | What Changed                                | Why This Improved the Output                              |
| ------- | ------------------------------------------------------------------------------------ | ------------------------------------------- | --------------------------------------------------------- |
| V1      | Create a tagline for an eco-friendly water bottle.                                   | N/A                                         | N/A                                                       |
| V2      | Create a catchy and memorable tagline for a premium eco-friendly water bottle brand. | Added brand positioning.                    | Generated stronger marketing language.                    |
| V3      | Added copywriter role, target audience, brand values, tone, and output constraints.  | Added role assignment and business context. | Produced creative, targeted, and differentiated taglines. |


### 1.3 Role and Context Analysis

Role assignment significantly improved the quality of responses by guiding the model to adopt the expertise and communication style appropriate for the task. In Scenario A, assigning the role of an elementary school teacher resulted in a more engaging and age-appropriate explanation. In Scenario C, assigning the role of an advertising copywriter produced more creative and marketable taglines.

Context setting further enhanced output quality by providing background information about the audience, objectives, and constraints. For the job-offer email, contextual details helped generate a realistic professional response that balanced gratitude, rejection, and future interest. Overall, combining role assignment with contextual information reduced ambiguity and produced outputs that were more accurate, relevant, and aligned with the intended purpose.