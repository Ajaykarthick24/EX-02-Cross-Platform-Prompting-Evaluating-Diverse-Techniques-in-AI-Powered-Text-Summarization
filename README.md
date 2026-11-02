# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

### Name: Ajay Karthick M
### Reg No: 212225040014


# EXPERIMENT: DESIGNING PROMPTS USING DIFFERENT PROMPT STRUCTURES

## 1. OBJECTIVE

To design and experiment with different prompt structures by gradually improving a basic prompt into an effective and well-structured prompt using Role Prompting, Context Prompting, Constraint Prompting, and Output Format Prompting.

## 2. APPLICATION SELECTED

**Application: Text Summarization**

Text summarization is the process of converting lengthy information into shorter, meaningful, and easy-to-understand content while preserving the important points.

**AI Tool Used:**
- ChatGPT

## 3. INTRODUCTION

Prompt Engineering is the process of designing and improving instructions given to Generative AI models to obtain accurate, relevant, and useful responses.

Different prompt structures help improve the quality of AI-generated outputs.

In this experiment, five prompt structures are used to generate a summary of a given text.

The prompt structures are:

1. Basic Prompt
2. Role Prompt
3. Context Prompt
4. Constraint Prompt
5. Output Format Prompt

## 4. SAMPLE INPUT TEXT

The following text is used as the input for all five prompt structures.

**Topic: Cloud Computing**

Cloud computing is a technology that allows users to access computing resources such as servers, storage, databases, networking, and software through the internet. Instead of purchasing and maintaining physical hardware, organizations can use cloud services provided by companies such as Amazon Web Services (AWS), Microsoft Azure, and Google Cloud.

Cloud computing offers several advantages, including cost savings, scalability, flexibility, data backup, and accessibility. It allows businesses to increase or decrease their computing resources according to their requirements.

There are three major cloud service models: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). Cloud computing also supports different deployment models, including public cloud, private cloud, and hybrid cloud.

Today, cloud computing is widely used in education, healthcare, banking, business, and software development. It plays an important role in modern digital transformation.

---

## 5. DIFFERENT PROMPT STRUCTURES

### EXPERIMENT 1: BASIC PROMPT

**Definition:**

A Basic Prompt is a simple instruction given to an AI model to perform a particular task without additional role, context, or constraints.

**Prompt:**

Summarize the following text about cloud computing.

**Expected Output:**

Cloud computing provides computing resources such as servers, storage, and software through the internet. It reduces hardware costs and offers scalability, flexibility, and accessibility. Its major service models are IaaS, PaaS, and SaaS. Cloud computing is widely used in education, healthcare, banking, and business.

**Observation:**

The AI generated a basic summary containing the main points. However, the response may lack detailed explanations and a specific structure.

---

### EXPERIMENT 2: ROLE PROMPT

**Definition:**

A Role Prompt assigns a specific identity or professional role to the AI model to guide how it responds.

**Prompt:**

Act as a professional Computer Science professor. Summarize the following text about cloud computing in a way that is easy for engineering students to understand.

**Expected Output:**

Cloud computing is a technology that provides computing services such as servers, storage, databases, and software through the internet.

It helps organizations reduce hardware costs and access computing resources whenever required.

The three major service models are:
- IaaS – Infrastructure as a Service.
- PaaS – Platform as a Service.
- SaaS – Software as a Service.

Cloud computing is commonly used in education, healthcare, banking, and software development.

**Observation:**

The AI adopted the role of a Computer Science professor and generated an educational explanation suitable for engineering students.

---

### EXPERIMENT 3: CONTEXT PROMPT

**Definition:**

A Context Prompt provides background information about the user, situation, or purpose of the task so that the AI can generate more relevant responses.

**Prompt:**

I am a second-year Computer Science Engineering student preparing for my university examination. I need to understand cloud computing quickly for revision.

Summarize the following text about cloud computing. Focus on important definitions, service models, advantages, and applications. Make the explanation easy to understand for an engineering student.

**Expected Output:**

Cloud computing is the delivery of computing services such as servers, storage, databases, and software over the internet.

**Advantages:**
1. Cost reduction.
2. Scalability.
3. Flexibility.
4. Accessibility.
5. Data backup.

**Service Models:**
- IaaS: Provides virtualized computing infrastructure.
- PaaS: Provides a platform for application development.
- SaaS: Provides software applications over the internet.

**Applications:**
- Education.
- Healthcare.
- Banking.
- Business.
- Software development.

**Observation:**

Providing background information helped the AI generate a more relevant summary based on the student's learning requirements.

---

### EXPERIMENT 4: CONSTRAINT PROMPT

**Definition:**

A Constraint Prompt specifies limitations or conditions that the AI must follow while generating the response.

**Prompt:**

Summarize the following text about cloud computing by following these conditions:

1. Use simple English.
2. Keep the summary within 100 words.
3. Include only the most important points.
4. Explain all three cloud service models.
5. Avoid unnecessary technical details.
6. Do not introduce information that is not present in the given text.

**Expected Output:**

Cloud computing provides computing resources such as servers, storage, databases, and software through the internet. It reduces hardware costs and offers scalability, flexibility, and accessibility. Its three service models are IaaS (infrastructure), PaaS (application development platform), and SaaS (software applications). Cloud computing supports public, private, and hybrid deployment models. It is widely used in education, healthcare, banking, business, and software development.

**Observation:**

The AI followed the specified conditions and generated a concise summary within the required word limit.

---

### EXPERIMENT 5: OUTPUT FORMAT PROMPT

**Definition:**

An Output Format Prompt specifies how the AI should organize and present its response, such as using tables, bullet points, headings, or numbered lists.

**Prompt:**

Summarize the following text about cloud computing using the following output format:

1. Definition: Explain cloud computing in two sentences.
2. Advantages: Present five advantages using bullet points.
3. Service Models: Present IaaS, PaaS, and SaaS in a table.
4. Applications: List five major application areas.
5. Conclusion: Provide a short concluding statement.

Use simple English and make the content suitable for engineering students.

**Expected Output:**

### Definition
Cloud computing is the delivery of computing resources through the internet. It allows users to access servers, storage, databases, and software without maintaining physical hardware.

### Advantages
- Cost savings.
- Scalability.
- Flexibility.
- Accessibility.
- Data backup.

### Service Models

| Model | Description |
|---|---|
| IaaS | Provides computing infrastructure. |
| PaaS | Provides an application development platform. |
| SaaS | Provides software applications over the internet. |

### Applications
1. Education.
2. Healthcare.
3. Banking.
4. Business.
5. Software development.

### Conclusion
Cloud computing is an important technology that provides flexible, scalable, and cost-effective computing services.

**Observation:**

The AI generated a well-organized response using headings, bullet points, and a table as requested.

---

## 6. FINAL PROMPT (COMBINED PROMPT STRUCTURE)

After experimenting with all five prompt structures, combine them into a single advanced prompt.

**Final Prompt:**

Act as a professional Computer Science professor.

I am a second-year Computer Science Engineering student preparing for my university examination. I need to understand cloud computing quickly and effectively.

Summarize the given text about cloud computing by following these instructions:

**Task:**
Create a clear and informative summary of the given text.

**Context:**
The summary is intended for an engineering student who needs to understand and revise the important concepts.

**Constraints:**
1. Use simple English.
2. Keep the summary within 150 words.
3. Include all important concepts.
4. Avoid unnecessary technical details.
5. Do not introduce unsupported information.

**Output Format:**
1. Definition of cloud computing.
2. Five important advantages.
3. A table explaining IaaS, PaaS, and SaaS.
4. Five real-world applications.
5. A short conclusion.

Make the response accurate, easy to understand, and suitable for examination preparation.

**Input Text:**

[Paste the cloud computing text here.]

**Observation:**

The final combined prompt generated a more relevant, structured, and useful response by combining all five prompt engineering techniques.

---

<img width="732" height="772" alt="image" src="https://github.com/user-attachments/assets/7fe36f67-e339-4859-8875-215e091d8226" />


## 7. COMPARISON OF DIFFERENT PROMPT STRUCTURES

| Prompt Structure | Main Purpose | Output Quality |
|---|---|---|
| Basic Prompt | Gives a simple instruction. | Basic |
| Role Prompt | Assigns a specific role to AI. | More relevant |
| Context Prompt | Provides background information. | Personalized |
| Constraint Prompt | Defines limitations and conditions. | More focused |
| Output Format Prompt | Defines the response structure. | Well-organized |
| Final Combined Prompt | Combines all five techniques. | More structured and task-specific |

---

## 8. PROCEDURE

1. Select a specific application (Text Summarization).
2. Prepare a sample input text about cloud computing.
3. Enter the Basic Prompt into ChatGPT and observe the output.
4. Upgrade the prompt by adding a specific role.
5. Add user context to make the response more relevant.
6. Introduce constraints such as word limits and language requirements.
7. Specify the required output format.
8. Combine all five prompt structures into one final prompt.
9. Compare the outputs generated by each prompt.
10. Record the observations and prepare the final conclusion.

---

## 9. RESULTS AND OBSERVATIONS

The experiment demonstrates how different prompt structures influence AI-generated responses.

- Basic prompts generate simple responses.
- Role prompts improve the perspective and style of the response.
- Context prompts make responses more relevant to the user's needs.
- Constraint prompts help control the length and content.
- Output format prompts improve readability and organization.
- Combined prompts produce more specific and structured responses.

---

## 10. FINAL CONCLUSION

In this experiment, different prompt engineering techniques were studied using Text Summarization as the selected application.

The experiment demonstrated that prompt quality plays an important role in the quality of AI-generated responses.

A basic prompt provides a general answer, whereas role, context, constraint, and output format prompts provide better control over the generated content.

Finally, combining all five prompt structures produced a more relevant, organized, and useful response.

Therefore, effective prompt engineering helps users communicate clearly with Generative AI models and obtain better results for academic and professional applications.

---

**END OF EXPERIMENT**
