# Designing Safe and Steerable Prompts for LLMs

**Access the lesson:** [Lesson notebook](https://github.com/bensethbell/safe-prompt-design/blob/main/safe_prompt_design_lesson.ipynb)  
**Access the solution:** [Solution notebook](https://github.com/bensethbell/safe-prompt-design/blob/main/safe_prompt_design_solution.ipynb)

This notebook demonstrates how structured prompt design can guide the behavior of large language models (LLMs), with a focus on safety, steerability, and responsible AI development. Inspired by Claude's alignment philosophy, the notebook introduces best practices for wrapping user queries with system prompts, applying role conditioning, and creating domain-aware scaffolds.

## Learning Objectives

- Understand how prompt design influences model behavior
- Identify and reframe potentially harmful or ambiguous user queries
- Use system-level instructions to scaffold safe assistant behavior
- Apply role-based prompting to influence tone and intent
- Build reusable prompt templates for sensitive domains like healthcare or education

## Notebook Structure

1. **Learning Objectives** – Clear goals for the learner
2. **Why Prompt Design Matters** – Motivations and safety concerns
3. **What Is a Prompt Scaffold?** – Definitions and structure
4. **Prompt Design: Wrapping Risky User Inputs Safely** – System prompt techniques
5. **Role-Based Prompt Framing** – Persona-driven prompting for alignment
6. **Developer Exercises** – Hands-on implementation tasks and reflection
7. **Key Takeaways** – Summary of safe prompting principles
8. **Further Exploration** – Suggested tools and learning paths

## How to Use

Open the notebook in Jupyter, Colab, or another environment that supports Python and Markdown. Simulated LLM responses (e.g., using GPT-4) are included to illustrate prompting techniques. This notebook does not use Claude or other proprietary APIs.

## Intended Audience

- LLM developers and safety researchers
- AI/ML curriculum designers and technical educators
- Engineers building user-facing generative AI applications

## License

This repository is released under the MIT License.
