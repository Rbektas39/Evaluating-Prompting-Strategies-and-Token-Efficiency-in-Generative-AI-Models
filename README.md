# 🔢 LLM Token Count Analysis

This project explores how large language models process text by analyzing token counts across different inputs. The goal is to better understand how tokenization works in practice and why it matters for cost, performance, and model behavior.

---

## 📊 Overview

Large language models do not read text as full words or sentences—they break text into smaller units called **tokens**.  

This project investigates:
- how text is split into tokens  
- how token counts vary across inputs  
- why token usage matters when working with APIs and prompts  

Understanding this is especially important when working with models that charge per token or have strict context limits.

---

## View Project 

TokenEfficiencyProject to TokenEfficiencyProject.pdf 

---

## 🔍 Key Questions

- How does token count change with sentence length and structure?  
- Do similar sentences produce very different token counts?  
- How do formatting choices (punctuation, spacing, phrasing) affect tokens?  
- What are the implications for prompt design and efficiency?  

---

## 🛠️ Tools Used

- Python  
- Tokenization libraries (e.g., OpenAI tokenizer / tiktoken)  
- pandas (for analysis)  
- matplotlib (for visualization)

---

## ⚙️ Methodology

1. Input text samples of varying complexity and structure  
2. Tokenize each input using a standard tokenizer  
3. Record and compare token counts  
4. Analyze how small changes in text affect tokenization  
5. Visualize patterns in token usage  

---

## 📈 Key Insights

- Token counts do not increase linearly with word count  
- Small formatting changes (like punctuation or spacing) can significantly affect token usage  
- More complex or less common words may break into multiple tokens  
- Efficient prompt design can reduce cost and improve model performance  

---
