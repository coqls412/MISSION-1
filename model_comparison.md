# Model Comparison

## 1. Task Definition
- **Task:** Read incoming emails received by university administrative staff, understand the context and requests, and draft polite and natural English replies.
- **Target Users:** University administrative staff.
- **Input Data:** Original email, sender's name, and any additional information required to prepare a reply.
- **Output Format:** A professional English email reply with an appropriate greeting, body, and closing. The AI must not invent facts, deadlines, policies, or commitments that are not provided.

## 2. Models Tested
Three AI models were tested using the same task instructions and the same sample email.

| Model | Version | Plan |
| :--- | :--- | :--- |
| **ChatGPT** | GPT-6 | Free |
| **Gemini** | Gemini 1.5 Flash 002 | Free |
| **Claude** | Claude Sonnet 5.5 | Free |

- **Test Date:** November 24, 2026
- **Testing Method:** The same prompt and sample email were provided to all three models.

## 3. Common Test Input
The following email was used for all three models.

> Dear International Office,
> 
> I am an exchange student who has been nominated by my home university for the Spring 2027 semester.
> 
> I would like to ask whether I need to submit my official transcript again, as I have already uploaded a copy during the nomination process.
> 
> Also, could you let me know the deadline for submitting the remaining application documents?
> 
> Thank you for your assistance.
> 
> Best regards,  
> Alex Kim

## 4. Evaluation Criteria
Each model was evaluated using four criteria on a scale of 1 to 5.

- **Content Accuracy:** Whether the response accurately reflects the original email without inventing information.
- **English Naturalness:** Whether the English is grammatically correct, natural, and professional.
- **Task Suitability:** Whether the response is appropriate for university administrative work.
- **Instruction Compliance:** Whether the model follows the task instructions and respects the limitations of the provided information.

## 5. Evaluation Results

| Evaluation Criteria | ChatGPT | Gemini | Claude |
| :--- | :---: | :---: | :---: |
| **Content Accuracy** | 5 | 4 | 4 |
| **English Naturalness** | 5 | 5 | 5 |
| **Task Suitability** | 4 | 5 | 4 |
| **Instruction Compliance** | 5 | 4 | 4 |
| **Total** | **19** | **18** | **17** |

### ChatGPT — 19/20
ChatGPT accurately identified both questions in the student's email and separated confirmed information from details requiring verification. It avoided inventing submission requirements or application deadlines. Its response was concise and professional.

### Gemini — 18/20
Gemini provided a professional response and suggested practical administrative follow-up steps. However, it requested additional information, such as the student's ID and home university, even though these details were not necessary to address the original questions.

### Claude — 17/20
Claude provided a detailed response and clearly identified information requiring confirmation. However, it requested additional personal information and used placeholders for details that had not been verified, making the response somewhat less suitable for immediate administrative use.

## 6. Final Model Selection
- **Selected Model:** ChatGPT (GPT-6)

I selected ChatGPT because it did not invent necessary information and clearly distinguished between confirmed details and information requiring verification. 

Although Gemini and Claude also produced natural and professional English, ChatGPT was the most suitable model for this task based on its content accuracy and compliance with the instructions.