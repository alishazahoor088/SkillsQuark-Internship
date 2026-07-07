# # 🚀 SkillsQuark Internship – Prompt Design Mastery

> **Task 1 – Prompt Engineering Internship**
## 📖 Overview
This repository contains my submission for **Task 1: Prompt Design Mastery** as part of the **SkillsQuark Generative AI & Prompt Engineering Internship**.
The objective of this task is to design a library of advanced prompts for different business use cases using **Zero-shot** and **Few-shot Prompting** techniques. Each case demonstrates how prompt engineering can be applied to solve real-world business problems through clear, structured, and context-aware AI instructions.
## 🎯 Objective
Create a library of advanced prompts for five different business use cases using **Zero-shot Prompting** and **Few-shot Prompting** techniques. The business domains covered in this repository include:
- 🛎️ Customer Support
- 📢 Marketing & Content Creation
- 👨‍💼 Human Resources (HR)
- 💻 Software Development
- 🛒 E-commerce
## 🤖 What is Prompt Engineering?
Prompt Engineering is the process of designing clear, specific, and effective instructions that guide an Artificial Intelligence (AI) model to generate accurate, relevant, and high-quality responses. Well-crafted prompts improve the consistency, reliability, and usefulness of AI-generated outputs across various industries and business applications.
## 🧠 Prompting Techniques Used
### 🎯 Zero-shot Prompting
Zero-shot prompting involves giving an AI model only the task instructions without providing any examples. The AI relies entirely on its existing knowledge to generate the required response.
**Characteristics**
- No examples are provided.
- Simple and direct instructions.
- Useful for straightforward tasks.
- Fast and efficient.
### 🎯 Few-shot Prompting
Few-shot prompting provides the AI with one or more examples before presenting the actual task. These examples help the model understand the expected tone, structure, and style, resulting in more consistent and accurate outputs.
**Characteristics**
- Includes multiple examples.
- Produces more consistent responses.
- Helps maintain a specific writing style.
- Suitable for complex business scenarios.

# 📚 Business Use Cases

# 🛎️ Case 1 – Customer Support
## 📌 Business Problem
An online clothing company needs to respond professionally to customers who receive incorrect products while maintaining customer satisfaction and trust.

## 🎯 Zero-shot Prompt
### 📝 Prompt
Act as the CEO of an online clothing company. Write a sincere apology to a customer who received the wrong clothing size. Use a warm, empathetic, and professional tone. Reassure the customer that the issue will be resolved promptly. Limit the response to **30 words** and end by signing with the **company's name only**.

### 💡 Why this Prompt Works
This Zero-shot prompt instructs the AI to generate a professional customer response using only the provided instructions, without any examples. It tests the AI's ability to understand the task and produce an appropriate response independently.

## 🎯 Few-shot Prompt
a### 📝 Prompt
**Act as the CEO of an online clothing company.**
### Example 1
**Customer Issue:**
I received a damaged hoodie.
**Response:**
Hello! We sincerely apologize for the inconvenience caused by the damaged product. We'll investigate the issue immediately. You may exchange the item at your convenience.
**Urban Thread**
### Example 2
**Customer Issue:**
I received the wrong color.
**Response:**
Hello! We're truly sorry for sending the wrong color. You may choose a replacement in your preferred color or request a full refund. We're here to help.
**Urban Thread**
### Now respond to this customer
**Customer Issue:**
I received the wrong clothing size.
**Instructions:**
- Use a warm, empathetic, and professional tone.
- Reassure the customer.
- Limit the response to **30 words**.
- End with the **company's name only**.

### 💡 Why this Prompt Works
This Few-shot prompt provides two examples before presenting the actual task. These examples help the AI understand the expected tone, structure, and writing style, resulting in a more accurate and consistent response.

# 📢 Case 2 – Marketing & Content Creation
## 📌 Business Problem
A skincare company is launching its new **Vitamin C Face Serum** and wants to create an engaging Instagram post that increases brand awareness and encourages customers to purchase the product.

## 🎯 Zero-shot Prompt
### 📝 Prompt
Act as a Social Media Marketing Manager for a skincare company. Create an engaging Instagram caption to launch our new **Vitamin C Face Serum**. Highlight its key benefits, including brighter skin, reduced dark spots, and a natural glow. Target teenagers, skincare enthusiasts, and adults interested in skincare. Use a fun, trendy, persuasive, and Gen Z-friendly tone with relevant emojis. End the caption with a strong call-to-action, one branded company hashtag, and **5–7 popular skincare hashtags**. Keep the caption between **80–100 words**.

### 💡 Why this Prompt Works
This Zero-shot prompt provides detailed instructions without any examples. It evaluates the AI's ability to generate a creative, audience-specific, and engaging Instagram caption based solely on the given requirements.

## 🎯 Few-shot Prompt
### 📝 Prompt
**Act as a Social Media Marketing Manager for GlowVerse Skincare.**
### Example 1
**Product:**
Hydrating Face Wash
**Instagram Caption:**
Just launched! Meet our **Hydrating Face Wash**—your new skincare essential! It deeply cleanses, keeps your skin hydrated, and helps minimize the appearance of pores for a fresh, healthy glow. Ready to upgrade your skincare routine? Shop now! ✨
**#GlowVerse #HydratingSkin #SkincareRoutine #FreshFace #HealthyGlow #CleanSkin**
### Example 2
**Product:**
SPF 50 Sunscreen
**Instagram Caption:**
 IT'S HERE! Our most requested product has finally arrived! Meet the **GlowVerse SPF 50 Sunscreen**—lightweight, no white cast, and designed to protect your skin from harmful UV rays while keeping your skin fresh every day. Grab yours online or in-store today! 🕶️✨
**#GlowVerse #SPF50 #SunProtection #NoWhiteCast #SkincareEssentials #GlowEveryDay**
### Now create an Instagram caption for the following product
**Product:**
Vitamin C Face Serum
**Instructions:**
- Highlight brighter skin, reduced dark spots, and a natural glow.
- Target teenagers, skincare enthusiasts, and adults.
- Use a fun, trendy, persuasive, and Gen Z-friendly tone.
- Include relevant emojis.
- End with a strong call-to-action.
- Add one branded company hashtag and **5–7 popular skincare hashtags**.
- Keep the caption between **80–100 words**.

### 💡 Why this Prompt Works
This Few-shot prompt includes two examples that demonstrate the desired writing style, structure, and branding. By learning from these examples, the AI can generate a more engaging, consistent, and audience-focused Instagram caption for the new product.

# 👨‍💼 Case 3 – Human Resources (HR)
## 📌 Business Problem
A technology company is hiring a Software Engineer and wants AI to help create a clear, professional job description and generate relevant interview questions to evaluate candidates.

## 🎯 Zero-shot Prompt
### 📝 Prompt
Act as the Human Resources Manager at **NovaTech Solutions**. Create a professional job description for a **Software Engineer** position. Include the job summary, key responsibilities, required educational qualifications, technical skills, work experience, salary range, workplace rules, and company policies. At the end, include a **Terms and Conditions** section followed by checkboxes for **"I Agree"** and **"I Disagree."** Use a formal and professional tone. Keep the document between **200–250 words** and end with the company's name only.

### 💡 Why this Prompt Works
This Zero-shot prompt provides detailed instructions without giving any examples. It evaluates the AI's ability to generate a structured, professional, and comprehensive job description while following specific formatting and content requirements.

## 🎯 Few-shot Prompt
### 📝 Prompt
**Act as the Human Resources Manager at NovaTech Solutions.**
### Example 1
**Position:**
Sales Representative
**Interview Questions:**
1. Tell us about your previous experience in sales or customer service.
2. How would you communicate with customers who have different needs and personalities?
3. How do you ensure you have complete knowledge of the products you are selling?
4. Describe a situation where you had to handle multiple customers at once. How did you manage it?
5. How would you encourage a customer to explore additional products without making them feel pressured?
### Example 2
**Position:**
UI/UX Designer
**Interview Questions:**
1. How do you ensure an application is user-friendly and easy to navigate?
2. Describe your process for understanding users' needs before starting a design.
3. How do you collect and use user feedback to improve a product?
4. Which UI/UX design tools are you most comfortable using, and why?
5. How do you collaborate with developers to ensure your designs are implemented successfully?
### Now generate 5 interview questions for the following position.
**Position:**
Marketing Intern
**Instructions:**
- Ask professional and role-specific questions.
- Assess communication skills, creativity, problem-solving, and teamwork.
- Use a formal and professional tone.
- Present the questions as a numbered list.

### 💡 Why this Prompt Works
This Few-shot prompt provides two interview question examples for different job roles before introducing the final task. These examples help the AI understand the expected structure, professionalism, and level of detail, enabling it to generate relevant interview questions tailored to the Marketing Intern position.

# 💻 Case 4 – Software Development
## 📌 Business Problem
A software development company wants to use AI to help developers identify and fix errors in Python code. This saves time and improves code quality.

## 🎯 Zero-shot Prompt
### 📝 Prompt
Act as a Senior Software Engineer. Identify and fix the errors in the given Python program. Provide the corrected version of the code and explain each correction in simple, beginner-friendly English. Format the output in the following order:
1. Error Identified
2. Corrected Code
3. Explanation

### 💡 Why this Prompt Works
This Zero-shot prompt clearly instructs the AI to analyze Python code, identify errors, provide the corrected version, and explain each correction in a beginner-friendly manner. It demonstrates the AI's ability to perform code debugging without relying on prior examples.

## 🎯 Few-shot Prompt
### 📝 Prompt
**Act as a Senior Software Engineer.**
### Example 1
**Python Code:**
print("Hello World)
**Response:**
**Error Identified:**
The string is missing a closing quotation mark.
**Corrected Code:**
```python
print("Hello World")
```
**Explanation:**
Strings in Python must begin and end with quotation marks.

### Example 2
**Python Code:**
```python
age = 18
if age >= 18
    print("Adult")
```
**Response:**
**Error Identified:**
The `if` statement is missing a colon.
**Corrected Code:**
```python
age = 18
if age >= 18:
    print("Adult")
```
**Explanation:**
Python requires a colon after an `if` statement before the code block begins.
### Now identify and fix the errors in the
following Python program.
**Instructions:**
- Identify the error(s).
- Provide the corrected code.
- Explain each correction in beginner-friendly English.
- Format the output as:
  1. Error Identified
  2. Corrected Code
  3. Explanation

### 💡 Why this Prompt Works
This Few-shot prompt provides two debugging examples before presenting the final task. By learning from these examples, the AI understands the expected format, level of detail, and style of explanation, enabling it to produce clear and consistent debugging assistance for Python code.

 🛒 Case 5 – E-commerce
## 📌 Business Problem
An online shopping company wants AI to generate an attractive product description that highlights the product’s features and persuades customers to purchase it.

## 🎯 Zero-shot Prompt
### 📝 Prompt
Act as an E-commerce Content Writer. Create a compelling product description for the **Dyson Airwrap i.d. Multi-Styler**. Highlight its unique features and explain how it stands out from similar products in the market. Emphasize its benefits for people experiencing hair styling challenges while using a persuasive, professional, and engaging tone. Naturally include relevant SEO keywords. Keep the description within **150 words**. Present the output with a **Product Title**, **Product Description**, **Key Features**, and a strong **Call-to-Action**.

### 💡 Why this Prompt Works
This Zero-shot prompt provides detailed instructions without any examples, allowing the AI to independently generate a persuasive and SEO-friendly product description while following a structured format.

## 🎯 Few-shot Prompt
### 📝 Prompt
**Act as an E-commerce Content Writer.**
### Example 1
**Product:**
Titanium Buds – Wireless Bluetooth Headphones
**Product Description:**
Meet **Titanium Buds**, our premium noise-cancelling wireless Bluetooth headphones built with a durable titanium finish for maximum comfort and strength. Enjoy crystal-clear sound, intelligent auto-detection, and automatic playback pause when someone speaks to you. Designed to deliver a premium listening experience with long-lasting battery life, Titanium Buds stand out in today's wireless headphone market. Available online and in-store. **Shop now and experience the difference!**
### Example 2
**Product:**
HydraSmart Bottle – Stainless Steel Smart Water Bottle
**Product Description:**
Introducing the **HydraSmart Bottle**—our premium stainless steel smart water bottle designed to help you stay healthy and hydrated. It keeps your drinks at your preferred temperature for hours and features an AI-powered assistant that reminds you to drink water while playing your favorite music on the go. Combining innovation, convenience, and style, HydraSmart Bottle is the perfect companion for your daily routine. Available online and in-store. **Upgrade your lifestyle today! Grab yours now!**
### Now create a product description for the following product.
**Product:**
Dyson Airwrap i.d. Multi-Styler
**Instructions:**
- Highlight the product's unique features and explain how it stands out from similar products in the market.
- Emphasize its benefits for people experiencing hair styling challenges.
- Use a persuasive, professional, and engaging tone.
- Naturally include relevant SEO keywords.
- Keep the description within **150 words**.
- Present the output using the following format:
  - Product Title
  - Product Description
  - Key Features
  - Call-to-Action

### 💡 Why this Prompt Works
This Few-shot prompt provides two well-structured product description examples before introducing the final task. The examples help the AI understand the expected tone, organization, and writing style, enabling it to produce a compelling, professional, and conversion-focused product description for the Dyson Airwrap i.d. Multi-Styler.

# 🎓 Skills Demonstrated Throughout This Task
- Prompt Engineering
- Zero-shot Prompting
- Few-shot Prompting
- Business Problem Analysis
- Customer Support Prompt Design
- Marketing & Content Creation
- Human Resources Documentation
- Software Development Prompt Design
- E-commerce Content Writing
- AI Instruction Design
- Professional Business Communication

# 🛠️ Tools Used
- ChatGPT (OpenAI)
- GitHub
- Markdown
- Web Browser
  
 # 📌 Conclusion
This repository showcases my completion of **Task 1 – Prompt Design Mastery** for the **SkillsQuark Generative AI & Prompt Engineering Internship**. Through five real-world business use cases, I designed structured Zero-shot and Few-shot prompts to demonstrate how prompt engineering can improve AI performance across customer support, marketing, human resources, software development, and e-commerce.This task strengthened my understanding of writing precise, context-aware prompts that guide AI to generate accurate, professional, and business-focused outputs. It also enhanced my practical skills in prompt engineering, documentation, and organizing technical work using GitHub.








