Here's the revised README with no tables, concise sentences, and straight to the point:

---

# PromoGenie – AI-Powered Marketing Copy Generator

**Live Demo:**  https://attached-assets--atshonota357.replit.app/ 

**Date:** 08 May 2026  
**Author:** Nota Atsho  
**Tech Career Accelerator – 2026**

---

## Overview

PromoGenie is a full-stack AI-powered marketing copy generator that produces product descriptions, social media captions, ad text, promotional messages, and hashtags based on user input.

---

## Key Features

Users can customize tone, audience, platform, and key selling points. The system offers five prompt templates: Standard, Storytelling, Feature-Focused, Urgency & Sale, and Minimalist. A history feature lets users save and revisit past generated content.

---

## Tech Stack

Frontend uses React. Backend uses Express.js. AI model is OpenAI GPT (gpt-4.1-mini). Database is PostgreSQL.


---

## API Selection Rationale

OpenAI GPT was chosen for its strong instruction-following ability, structured output generation, token usage tracking, and built-in content safety.

---

## Prompt Engineering Methodology

Each prompt includes a role definition (AI as marketing expert), instructions based on tone/audience/platform, a structured output format with five content types, and safety rules.

The five prompt templates serve different use cases. Standard is balanced for general marketing. Storytelling is emotional for lifestyle brands. Feature-Focused is technical for tech products. Urgency & Sale is persuasive for promotions. Minimalist is short and clean for luxury brands.

---

## Input Validation & Output Filtering

All fields are required. Product descriptions must contain at least 10 words. Dropdown menus ensure consistent inputs. Outputs are filtered for professionalism and tone matching.

---

## Performance Metrics

Average generation time is 2–5 seconds. Token usage is tracked for cost monitoring.

---

## Limitation Management

API rate limits are handled with error messages. Output quality variation is managed with minimum input requirements. Response delays use loading indicators.

---

## Sample Output (Standard Template)

**Product Description:** Upgrade your wardrobe with the Nike T-shirt, designed with high-quality fabric for comfort and durability.

**Social Media Caption:** Stay stylish every day. Grab your Nike T-shirt now!

**Advertisement Text:** Experience comfort and style with the Nike T-shirt.

**Short Promo Message:** Style meets comfort.

**Hashtags:** #Nike #TShirt #Streetwear #Fashion #EverydayStyle

---

## Conclusion

PromoGenie demonstrates effective prompt engineering, structured full-stack design, and practical application of generative AI for professional marketing content.

---
