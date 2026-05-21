

# PromoGenie – AI-Powered Marketing Copy Generator

**Live Demo:**(https://attached-assets--atshonota357.replit.app/) 
 
 
**Author:** Nota Atsho  
**Tech Career Accelerator – 2026**



## Overview

PromoGenie is a full-stack AI-powered marketing copy generator that produces high-quality content including product descriptions, social media captions, ad text, promotional messages, and hashtags based on user input.



## Key Features

- Generate marketing content with customizable **tone**, **audience**, **platform**, and **key selling points**
- **5 prompt templates**: Standard, Storytelling, Feature-Focused, Urgency & Sale, Minimalist
- **History feature** – save and revisit previously generated content
- Structured AI outputs (5 content types per request)



## Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React |
| Backend | Express.js |
| AI Model | OpenAI GPT (gpt-4.1-mini) |
| Database | PostgreSQL |

---

## Architecture

```
User Input → AI Processing → Output Display → Save to Database
```

---

## API Selection Rationale

**OpenAI GPT (gpt-4.1-mini)** was chosen for:
- Strong instruction-following ability
- Structured output generation
- Token usage tracking
- Built-in content safety

---

## Prompt Engineering Methodology

Each prompt includes:
1. Role definition (AI as marketing expert)
2. Instructions based on tone, audience, platform
3. Structured output format (5 content types)
4. Safety rules

### Prompt Templates

| Template | Strength | Best Use Case |
|----------|----------|----------------|
| Standard | Balanced | General marketing |
| Storytelling | Emotional | Lifestyle brands |
| Feature-Focused | Technical | Tech products |
| Urgency & Sale | Persuasive | Promotions |
| Minimalist | Short & clean | Luxury brands |

---

## Input Validation & Output Filtering

- All fields required
- Product description: minimum 10 words
- Dropdown menus for consistent inputs
- Output filtered for professionalism and tone matching

---

## Performance Metrics

- Generation time: **2–5 seconds**
- Token usage tracking for cost monitoring

---

## Limitation Management

| Limitation | Mitigation |
|------------|------------|
| API rate limits | Error handling messages |
| Output quality variation | Minimum input requirements |
| Response delays | Loading indicators |

---

## Sample Output (Standard Template)

**Product Description:**  
Upgrade your wardrobe with the Nike T-shirt, designed with high-quality fabric for comfort and durability.

**Social Media Caption:**  
Stay stylish every day. Grab your Nike T-shirt now!

**Advertisement Text:**  
Experience comfort and style with the Nike T-shirt.

**Short Promo Message:**  
Style meets comfort.

**Hashtags:**  
`#Nike #TShirt #Streetwear #Fashion #EverydayStyle`
