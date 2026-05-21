# PromoGenie – AI-Powered Marketing Copy Generator 
Tech Career Accelerator – 2026 
Live Application: PromoGenie
Date: 08 May 2026 
By  
Nota Atsho 
Introduction 
For this project, I developed PromoGenie, an AI-powered marketing copy generator that 
produces high-quality content for different marketing scenarios. The tool generates 
product descriptions, social media captions, advertisement text, short promotional 
messages, and hashtags based on user input. 
The purpose of this system is to help users quickly create professional marketing 
content by selecting different customization options such as tone, audience, platform, 
and key selling points. 
Implementation Architecture 
PromoGenie is a full-stack web application built using React for the frontend and 
Express for the backend. The system follows a structured workflow: 
User Input → AI Processing → Output Display → Save to Database 
Users enter product details through the interface, and the backend sends this data to 
the OpenAI GPT model. The AI generates structured marketing outputs, which are 
displayed to the user and stored in a PostgreSQL database. 
The system also includes a history feature that allows users to view previously 
generated content. 
Figure 1: Input Form Interface 
This screen shows the main user interface of PromoGenie. Users enter product details 
such as product name and description, and select customization options including target 
audience, key selling point, tone, platform, and prompt template. 
These inputs allow the system to generate tailored marketing content based on user 
preferences. 
Figure 2: Generated Output Screen 
This screen displays the AI-generated marketing content based on the user’s input. The 
system produces multiple outputs, including a product description, social media caption, 
advertisement text, short promotional message, and relevant hashtags. 
These outputs are tailored according to the selected tone, audience, platform, and 
prompt template 
Figure 3: History Page 
This screen shows the history of previously generated marketing content. Users can 
view past results, including product details and generated outputs, allowing them to 
revisit, compare, and reuse content. 
This feature supports result saving and improves usability by keeping a record of all 
generated campaigns 
API Selection Rationale 
The OpenAI GPT model (gpt-4.1-mini) was selected because it provides accurate and 
high-quality text generation. 
The main reasons for choosing this API include: 
• Strong instruction-following ability  
• Ability to generate structured outputs  
• Token usage tracking for performance monitoring  
• Built-in content safety features  
These features make it suitable for generating reliable and professional marketing 
content. 
Prompt Engineering Methodology 
The system uses a structured prompt engineering approach to ensure consistent and 
high-quality outputs. 
Each prompt includes: 
• A role definition where the AI acts as a marketing expert  
• Instructions based on tone, audience, and platform  
• A structured output format (5 content types)  
• Safety rules to prevent inappropriate content  
This ensures that all outputs are relevant, clear, and aligned with user inputs. 
Prompt Templates 
The system includes five optimized prompt templates: 
1. Standard Template 
Used for general-purpose marketing content with a balanced tone. 
2. Storytelling Template 
Focuses on emotional and narrative-driven content to engage the audience. 
3. Feature-Focused Template 
Highlights product specifications and benefits in a clear and direct way. 
4. Urgency & Sale Template 
Creates persuasive content using urgency and limited time offers. 
5. Minimalist Template 
Generates short and impactful content using minimal words. 
Sample Inputs 
The following example shows how users interact with the system: 
• Product Name: Nike T-shirt  
• Product Description: A high-quality t-shirt designed for comfort and everyday 
style for young adults  
• Target Audience: Young Adults (18–25)  
• Key Selling Point: High Quality  
• Tone: Friendly  
• Platform: Instagram  
• Prompt Template: Standard  
Sample Outputs 
Below are five examples generated using different templates: 
Sample 1 – Standard Template 
Product Description: 
Upgrade your wardrobe with the Nike T-shirt, designed with high-quality fabric for 
comfort and durability. Perfect for everyday wear, it combines style and reliability. 
Social Media Caption: 
Stay stylish every day, Grab your Nike T-shirt now! 
Advertisement Text: 
Experience comfort and style with the Nike T-shirt. Built for everyday confidence. 
Short Promo Message: 
Style meets comfort. 
Hashtags: 
#Nike #TShirt #Streetwear #Fashion #EverydayStyle 
Sample 2 – Storytelling Template 
Product Description: 
Every journey begins with a choice. The Nike T-shirt is designed for those who want 
comfort and confidence in every step of their day. 
Social Media Caption: 
Your story starts with style  
Advertisement Text: 
Feel confident every day with a t-shirt that matches your lifestyle. 
Short Promo Message: 
Wear your story. 
Hashtags: 
#Lifestyle #Fashion #Comfort #EverydayWear 
Sample 3 – Feature-Focused Template 
Product Description: 
The Nike T-shirt features high-quality fabric, durable stitching, and a comfortable fit 
designed for everyday use. 
Social Media Caption: 
Quality you can feel. Style you can trust. 
Advertisement Text: 
Designed with premium materials for long-lasting comfort and performance. 
Short Promo Message: 
Built for quality. 
Hashtags: 
#HighQuality #Nike #Clothing #Durable 
Sample 4 – Urgency & Sale Template 
Product Description: 
Get your Nike T-shirt now while stocks last. Limited availability for a high-quality 
everyday essential. 
Social Media Caption: 
Limited stock! Don’t miss out! 
Advertisement Text: 
Act fast and grab your Nike T-shirt before it’s gone. 
Short Promo Message: 
Hurry - limited time only! 
Hashtags: 
#LimitedOffer #Sale #ActNow #Nike 
Sample 5 – Minimalist Template 
Product Description: 
Nike T-shirt. Simple. Comfortable. Reliable. 
Social Media Caption: 
Clean style. Everyday comfort. 
Advertisement Text: 
Less words. More quality. 
Short Promo Message: 
Wear better. 
Hashtags: 
#MinimalStyle #Nike #CleanFashion 
Figure 4: Detailed Output Example 
This screen provides a detailed view of a single generated result. It shows all five 
content types clearly, including product description, caption, advertisement text, 
promotional message, and hashtags. 
This demonstrates the system’s ability to generate complete and structured marketing 
content in one request. 
Input Validation and Output Filtering 
The system includes input validation to ensure accurate results: 
• All fields are required  
• Product description must contain at least 10 words  
• Dropdown menus ensure consistent inputs  
Output filtering ensures: 
• Content is professional and appropriate  
• Tone matches user selection  
• No harmful or irrelevant content is generated  
Performance Optimization Techniques 
The system tracks performance using: 
• Generation time (2–5 seconds)  
• Token usage (for cost monitoring)  
Additional optimizations include: 
• Input validation to reduce unnecessary API calls  
• Efficient data handling and storage  
• Structured outputs for faster processing  
Limitation Management Strategies 
Some limitations include: 
• API rate limits  
• Variation in output quality based on input  
• Response time delays  
These are managed through: 
• Error handling messages  
• Minimum input requirements  
• Loading indicators  
Comparison of Prompt Templates 
Each template produces different results: 
• Storytelling → emotional and engaging  
• Feature-focused → detailed and technical  
• Urgency → persuasive and action-driven  
• Minimalist → short and impactful  
• Standard → balanced and versatile  
This shows how prompt design affects output quality. 
Comparison Matrix of Prompt Templates 
Template 
Strength 
Best Use Case 
Standard 
Balanced 
Output 
Style 
General 
marketing 
Storytelling 
Emotional 
Lifestyle brands 
Neutral 
Feature
Focused 
Narrative 
Technical 
Tech products 
Detailed 
Urgency & Sale High 
conversion 
Promotions 
Persuasive 
Minimalist 
Premium feel 
Luxury brands 
Short & 
clean 
Conclusion 
PromoGenie successfully meets all project requirements by providing a functional AI
powered marketing copy generator. The system demonstrates effective prompt 
engineering, structured design, and practical use of generative AI. 
