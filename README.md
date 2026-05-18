# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:
To achieve the comparative results outlined in the report, a standardized evaluation algorithm and a multi-tiered prompting strategy were employed across all platforms.

The Evaluation Algorithm The following algorithm was used to ensure parity across ChatGPT, Claude, Gemini, Cohere, and Meta:
Initialization: Set the "System Temperature" to a neutral value (approx. 0.7) where applicable to balance creativity and factual precision.

Input Standardization: Feed the exact same "Base Prompt" into each model’s primary chat interface simultaneously to prevent temporal data bias.

Execution Phase:

Task A (Summarization): Input a 1,000-word technical research paper.

Task B (Technical Q&A): Ask a complex architectural question regarding Transformer models.

Metric Collection:

Record Latency (time to first token).

Record Token Count (verbosity).

Assess Constraint Adherence (did it follow formatting rules?).

Scoring: Use a double-blind human review to assign a Reasoning Score out of 10.

The Benchmark Prompts The experiment utilized high-density prompts designed to test the limits of instruction following.
A. The Summarization Prompt "You are an expert technical editor. Summarize the provided research paper into exactly three bullet points for an executive audience. Focus exclusively on methodology, results, and limitations. Use professional language and do not exceed 150 words total. Do not include an intro or outro."

B. The Technical Q&A Prompt "Explain the 'Attention Mechanism' in Transformer architectures. Your explanation must be suitable for a Senior Software Engineer who is new to AI. Include a brief comparison to Recurrent Neural Networks (RNNs) and use one analogy. Ensure the response is factually rigorous and avoids fluff."

Strategy Analysis Claude 3.5 Sonnet: Excelled at the Summarization Prompt due to its superior adherence to "negative constraints" (e.g., "Do not include an intro").
GPT-4o: Was the most efficient for Technical Q&A, providing the highest information density in the shortest response time.

Gemini 1.5 Pro: Outperformed others when the "Base Prompt" included extremely large source files, thanks to its massive context window.

## Prompt

The experiment utilized two specific types of prompts to evaluate the performance of ChatGPT, Claude, Gemini, Cohere, and Meta. These were designed to test both high-density summarization and technical reasoning capabilities. 1. The Summarization PromptThis prompt was used to evaluate the models' ability to distill complex information while adhering to strict formatting constraints: "You are an expert technical editor. Summarize the provided research paper into exactly three bullet points for an executive audience. Focus exclusively on methodology, results, and limitations. Use professional language and do not exceed 150 words total. Do not include an intro or outro.

## Output
[exp 3.pdf](https://github.com/user-attachments/files/27941228/exp.3.pdf)
