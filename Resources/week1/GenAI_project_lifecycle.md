# Generative AI Project Life Cycle

## Introduction
- The course will cover the techniques required to **develop and deploy an LLM-powered application**.
- Emphasis on the **Generative AI Project Life Cycle** that will guide the project from conception to launch.

![Project Lifecycle](./figures/project_liofecycle.png)


## 1. Define the Scope
- **Most crucial step** in any project.
- Narrow and accurate definition of scope is essential.
- Determine LLM's function in your application:
  - Broad capabilities (e.g., long-form text generation) or 
  - Specific tasks (e.g., named entity recognition).
- Specificity can save **time** and **compute cost**.

## 2. Model Choice
- Decide whether to:
  - Train your model from scratch or 
  - Use an existing base model.
- Generally, start with an existing model. But there are situations where training from scratch is beneficial.
- More insights on this decision will be provided later in the course.

## 3. Adapt and Align
- Assess model performance.
- Utilize **prompt engineering** to potentially enhance model performance.
- If prompt engineering isn't sufficient, consider **fine-tuning** the model.
  - Detailed coverage in Week 2.
- Week 3 introduces **reinforcement learning with human feedback** to ensure model alignment with human preferences.
- Importance of **evaluation**:
  - Use of metrics and benchmarks to measure performance.
  - This stage can be **highly iterative**; might go through prompt engineering, fine-tuning, and evaluation multiple times.

## 4. Deployment
- Once performance and alignment are satisfactory, deploy the model.
- Optimize the model for deployment to:
  - Make efficient use of compute resources.
  - Provide an optimal user experience.

## 5. Address Limitations
- Consider LLM's limitations, such as:
  - Tendency to invent information.
  - Limited complex reasoning and mathematical capability.
- The course will explore techniques to mitigate these limitations.

## Conclusion
- The Generative AI Project Life Cycle is complex but will be revisited multiple times throughout the course.
- Each stage will be detailed in the course, making the process clearer and more approachable.
