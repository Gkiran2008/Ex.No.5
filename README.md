

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

# 🧪 AI Tools Required: 
- **ChatGPT (OpenAI)** – Test zero-shot, few-shot, and structured prompts.  
- **Claude (Anthropic)** – Known for long-context and detailed reasoning.  
- **Google Gemini (formerly Bard)** – Good for fact-based and summarization tasks.  

---

## 📖 Explanation: 

### Define the Two Prompt Types:

- **Naïve Prompt:** Broad or unstructured prompts that provide little instruction or context.  
- **Basic Prompt:** Clear, detailed, and structured prompts that give specific instructions or context to guide the model.  

Based on that pattern type refine the prompt and submit that with AI tool.  
Get the output and write the report.  

---

## 🧭 Prepare Multiple Test Scenarios:

Select various scenarios such as:  
- Generating a creative story.  
- Answering a factual question.  
- Summarizing an article or concept.  
- Providing advice or recommendations.  
- Or any other test scenario.  

For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.  

---

## ⚡ Run Experiments with ChatGPT:

- Input the naïve prompt for each scenario and record the generated response.  
- Then input the corresponding basic prompt and capture that response.  
- Repeat this process for all selected scenarios to gather a full set of results.  

---

## 📊 Evaluate Responses:

Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on:  
- **Quality**  
- **Accuracy**  
- **Depth**  

Also analyze:  
- Does ChatGPT consistently provide better results with basic prompts?  
- Are there scenarios where naïve prompts work equally well?  

---

## ✅ Deliverables:

1. A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.  
2. Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.  
3. Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.  


# 🔬 Prompting Strategy Experiment: Zero-Shot vs Few-Shot vs Chain-of-Thought

This project compares how different prompting strategies perform across reasoning, creative, and fact-based tasks.  
Evaluation was done using a **rubric method (Accuracy, Depth, Clarity; Likert scale 1–5).**

---

## 1. Scenarios for Testing
We tested three types of tasks:
1. **Reasoning Task** → Math/logic puzzle  
2. **Creative Task** → Short story writing  
3. **Fact-Based Task** → Climate change causes  

---

## 2. Prompting Techniques
- **Zero-Shot Prompting** → No examples, just the task.  
- **Few-Shot Prompting** → Provide 2–3 examples of expected answers.  
- **Chain-of-Thought Prompting (CoT)** → Ask the model to reason step by step.  

---

## 3. Experiment Results

### **Scenario A – Reasoning Task**
**Prompt:** *"A farmer has 17 sheep, all but 9 run away. How many are left?"*

- **Zero-Shot Response:**  
`9 sheep are left.`

- **Few-Shot Response:**  
`In a similar riddle: If there are 25 birds and all but 7 fly away, then 7 remain.  
Now for the sheep: All but 9 ran away, so 9 remain.`

- **Chain-of-Thought Response:**  


**Evaluation:**  
- Zero-Shot → Accuracy=5, Depth=2, Clarity=3 → **3.3**  
- Few-Shot → Accuracy=5, Depth=3, Clarity=4 → **4.0**  
- CoT → Accuracy=5, Depth=5, Clarity=5 → **5.0**  

---

### **Scenario B – Creative Task**
**Prompt:** *"Write a short story about a robot who learns emotions."*

- **Zero-Shot Response:**  
`A robot named Zeta worked in a lab. One day it saw a child crying and felt something new—compassion. From then, Zeta began to understand emotions.`

- **Few-Shot Response:**  
`Zeta was built for efficiency, but after befriending a little girl, it experienced confusion, joy, and finally love. The girl’s laughter became the first melody in Zeta’s metallic heart.`

- **Chain-of-Thought Response:**  

**Evaluation:**  
- Zero-Shot → Accuracy=4, Depth=3, Clarity=3 → **3.3**  
- Few-Shot → Accuracy=4, Depth=4, Clarity=4 → **4.0**  
- CoT → Accuracy=4, Depth=5, Clarity=5 → **4.7**  

---

### **Scenario C – Fact-Based Task**
**Prompt:** *"What are the causes of climate change?"*

- **Zero-Shot Response:**  
`Burning fossil fuels, deforestation, agriculture, and industrial emissions.`

- **Few-Shot Response:**  

**Evaluation:**  
- Zero-Shot → Accuracy=5, Depth=3, Clarity=3 → **3.7**  
- Few-Shot → Accuracy=5, Depth=4, Clarity=4 → **4.3**  
- CoT → Accuracy=5, Depth=5, Clarity=5 → **5.0**  

---

## 4. Final Comparison Table

| Scenario   | Prompt Style | Accuracy | Depth | Clarity | Avg Score |
|------------|--------------|----------|-------|---------|-----------|
| Reasoning  | Zero-Shot    | 5        | 2     | 3       | **3.3**   |
| Reasoning  | Few-Shot     | 5        | 3     | 4       | **4.0**   |
| Reasoning  | CoT          | 5        | 5     | 5       | **5.0**   |
| Creative   | Zero-Shot    | 4        | 3     | 3       | **3.3**   |
| Creative   | Few-Shot     | 4        | 4     | 4       | **4.0**   |
| Creative   | CoT          | 4        | 5     | 5       | **4.7**   |
| Fact-Based | Zero-Shot    | 5        | 3     | 3       | **3.7**   |
| Fact-Based | Few-Shot     | 5        | 4     | 4       | **4.3**   |
| Fact-Based | CoT          | 5        | 5     | 5       | **5.0**   |

---

## 5. Key Findings
- **Zero-Shot** → Quick, decent accuracy, but shallow.  
- **Few-Shot** → Adds structure and creativity, useful for storytelling and structured answers.  
- **Chain-of-Thought (CoT)** → Best for reasoning and explanation, most consistent clarity.  

📌 **Conclusion:**  
- For **fact recall** → Zero-Shot works fine.  
- For **creative writing** → Few-Shot improves richness.  
- For **problem-solving/reasoning** → Chain-of-Thought is superior.  



# RESULT: 

The prompt for the above said problem executed successfully
