# PEFT-of-LLMs-vs-RAG-Enhanced-LLMs-for-ASAG
This is the working repository for my CS6120 Natural Language Processing Project.

### Team
- Gugan S Kathiresan - 002756523
- Aditya Shanmugham - 002738073
- Prabhleenkaur Bindra - 002781738
- Maria Anson - 002931419

The goal of this project is to implement an ASAG (Automated Short Answer Grading) architecture that aims to be used for grading short computer science and coding assignments harnessing the knowledge within a finetuned LLM<S>, and be open for user interaction.

The proposed methods perform sInstruction fine-tuning with PEFT/ LoRA of an LLM.
We compare:

As mentioned previously, using a domain of course rubrics, questions and answers, the proposed model would posses interactive capabilities to perform Logical Reasoning and allow the user to receive feedback on their assignments. By specifying a rubric and opening up the LLM for interaction, we are both harnessing the knowledge of LLMs to provide constructive feedback, but are also avoiding any catastrophic forgetting, thereby making this scalable for applications like:
- Organization Knowledge Transfer (KT)
- Automated Test / Resume / Essay Evaluation
- Recommendations on how to improve prompts, content, etc.

Results:

Files:

