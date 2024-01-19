# TiCoder
### Test-Driven Interactive Code Generation

TiCoder is a framework designed to enhance the accuracy of code generation in Large Language Models (LLMs) through interactive and guided intent clarification. TiCoder partially formalizes ambiguous intent in natural language prompts by generating a set of tests to distinguish common divergent behaviours in generated code suggestions. The test-driven interaction enables users to provide feedback on expected program behavior through concrete specifications. TiCoder has been evalauted through 1) a mixed-methods user study comparing practical impacts of using TiCoder compared to the existing interaction mechanisms and 2) an evaluation of the code accuracy improvements provided by the workflow at scale with four different state-of-the-art LLMs on two python datasets. Experimental results indicate that participants using TiCoder are significantly more likely to correctly evaluate AI generated code, and report significantly less task-induced cognitive load. In addition, experiments show an average absolute improvement of 38.43% in the pass@1 code generation accuracy across both datasets and all studied LLMs, within 5 user interactions. 

Arxiv paper: https://arxiv.org/pdf/2208.05950.pdf

Further details on the user study and experimental results can be found in: [TiCoder.pdf](TiCoder.pdf)
