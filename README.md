# 🦢 Prompt-library-for-AI-for-supply-chain-ops
This repository represents the detailed prompt engineering examples using elements of prompt formatted clearly for AI especially for Amazon Large Titan by considering four critical manufacturing problems. It is important to provide clear and concise prompts while interacting with AI systems

---

## 🦑 Elements of prompt
A prompt's form depends on a task you are giving to a model. As you explore prompt engineering example, you will review prompts containing some or all the following elements:
- *Introduction* provides a task description or instruction for how the model should perform
- *Context* is external information to guide the model
- *Input data* is the input for which you want a response
- *Output indicator* is the output type or format

**Best practices for designing effective prompts**
1. Be clear and concise
2. Include context if needed
3. Use directives for the appropriate response type
4. Consider the output in the prompt
5. Start prompts with an integration
6. Provide an example response
7. Break up complex tasks
8. Experiment and be creative

It is important to review the model's responses to ensure that the prompts are eliciting the appropriate quality, type, and range of responses. Make changes to the prompts if needed. You can even ask one copy of the model to improve or check output from another copy of the model. With experimentation, you will gain intuition for crafting and optimizing prompts to best suit your needs and models. Prompt engineering is an iterative skill and improves with practice

---

## 🦋 Prompt 1: Unplanned Customer orders

### Introduction
Evaluate the impact of unplanned customer orders and recommend ways to adjust production schedules, minimizing disruption and delays

### Context
A steel manufacturing plant receives unexpected customer orders that must be fulfilled quickly. This disrupts existing production and order sequences

### Input
"Here is the production schedule, available resource constraints, and new unplanned customer details:
- Current orders: [List of jobs and deadlines]
- New order quantity and desired delivery date: [Input quantity and deadline]
- Resource availability: [List of available mills, shift timings, constraints]"

### Output indicator
Return an optimized schedule that includes the new order, highlighting:
- Suggested sequence of jobs
- Resource allocations
- Impact on existing order delivery times
- Proposed mitigation measures

---

## 🫎 Prompt 2: Unbalanced Resource utilization

**Introduction**
Balance workloads across equipment and shifts, ensuring maximum utilization and minimal downtime

**Context**
The manufacturing process has certain bottleneck resources (e.g. specific rolling mills) leading to delays, while other equipment operates below capacity

**Input**
"Here is the current load across equipment lines and shift patterns:
- Resource status: [List of equipment, shift load, available slots]
- Order backlog: [List of pending jobs with processing times, due dates]
- Maintenance constraints: [List of downtime windows]"

**Output indicator**
Recommend:
- Adjusted shift allocations
- Dynamic load-balancing strategy
- Resource reassignments
- Projected improvements in lead times and equipment utilization

---
