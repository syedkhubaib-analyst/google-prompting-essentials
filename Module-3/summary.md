# Module 3: Speed Up Data Analysis And Presentation Building

Generative AI can help uncover insights in datasets by identifying patterns, connections, and trends. This module focuses on strategies to prompt gen AI tools effectively for data analysis while keeping in mind their strengths, limitations, and best-use scenarios.

---

## Prompting Strategies for Data Analysis

### 1. **Align with Gen AI Capabilities**
Design your prompts to suit what gen AI is good at:
- **Text analysis**: Classify sentiment and themes in open-ended responses.
- **Data augmentation**: Expand small datasets to simulate trends.
- **Q&A with data**: Ask direct questions in plain language (e.g., "Were Q2 sales up?").
- **Scenario analysis**: Predict outcomes based on past data.
- **Visual/image analysis**: Extract insights from charts or images.
- **Market/customer research**: Summarize trends from surveys and social media.

>  "Avoid expecting rigorous statistical or highly structured data analysis directly from gen AI. Instead, prompt it to suggest appropriate tools or methods."

---

## Preparing Your Dataset

>  "Your output is only as good as your input."

Before using gen AI:
- **Validate and clean your data**  
- Use gen AI to spot inconsistencies or formatting issues  
- Example prompt:  
  `"Here's a sample of my data. Identify any issues or inconsistencies and suggest fixes."`

---

## Encourage Exploration

Gen AI works best when given **open-ended prompts** that allow it to surface unexpected patterns.

Example:  
> “You're a journalist researching housing trends. What insights can you find in this vacant property dataset?”

Keep your prompts broad and curiosity-driven.

---

## Use Embedded Gen AI Tools

Many tools embed AI for direct data interaction:

| Tool | Features |
|------|----------|
| **Gemini in Google Sheets** | Summarize, create tables, write formulas |
| **Tableau Pulse** | Automated data insights via Slack/email |
| **Looker Studio** | Pre-built templates, shareable dashboards |
| **BigQuery** | Query generation based on metadata |

Example prompt in Google Sheets:  
> “Create a table that includes the median vacancy rate per city.”

---

## Decipher Complex Content with Gen AI

Gen AI can help you understand confusing material by translating, simplifying, or explaining it:

- **Translate**: "Translate this sentence to Spanish."
- **Break down jargon**: "Explain compound interest in simple terms."
- **Explain spreadsheets**: "Explain formula in cell B12."
- **Understand errors**: "What does 'Error 404' mean?"
- **Assist with coding**: "Debug this JavaScript function."

---

## Fine-Tune AI Outputs with Settings

Some platforms let you adjust generation settings:

### Temperature (Creativity)
- **Low (0.1–0.4)**: Factual and consistent (e.g., reports, code)
- **High (0.8–1.0)**: Creative and diverse (e.g., brainstorming)

### Top-k and Top-p (Focus controls)
- **Top-k**: AI chooses from top K most likely words.
- **Top-p**: AI chooses from a dynamic probability-based pool.

 >  "Use **top-p = 0.9–0.95** for creativity, leave **top-k** at default."

---

## Key Takeaways

- Always validate data before analysis.
- Use gen AI tools based on their strengths, and design prompts accordingly.
- Keep prompts open-ended for better insights.
- Use embedded AI tools like Gemini when available.
- Fine-tune AI output using temperature, top-p, and top-k.
- Evaluate all AI outputs, especially when dealing with unfamiliar content or critical data.

---

## Final Thought

As an analyst, the quality of your prompts determines the quality of your insights. Prompt thoughtfully, understand your tools, and gen AI becomes a powerful partner in uncovering what your data has to say.

