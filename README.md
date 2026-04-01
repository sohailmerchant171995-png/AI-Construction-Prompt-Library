AI-Powered Construction Project Management — Prompt Library
This repository contains a collection of 10 structured AI prompts designed to automate and support subcontractor management workflows in residential construction projects in Melbourne. Each prompt has been iteratively developed from a basic version (v1.0) to a final HD version (v1.2), with documented improvements, constraints, output formats, and risk considerations.
These prompts are designed to support construction project managers, schedulers, cost estimators, risk analysts, compliance officers, and operations managers in making faster, more accurate, and data-driven decisions.
---
Repository Structure
Each file follows the same structure:
Final Prompt Text (v1.2)
Workflow Task (where it fits in the process)
Problem Being Solved
Automation Potential
Risks and Limitations
Iteration Log (v1.0 to v1.2)
---
Prompt Files
1. Subcontractor Selection
Recommends the top 3 subcontractors for a construction task based on cost, experience, availability, and performance ratings.
File: prompt1_subcontractor_selection.md
---
2. Job Scheduling
Generates an optimised task schedule by assigning subcontractors to tasks based on dependencies, availability, and project timeline.
File: prompt2_job_scheduling.md
---
3. Cost Estimation
Produces a detailed cost breakdown for a construction project including labour, materials, contingency buffer, and cost optimisation recommendations.
File: prompt3_cost_estimation.md
---
4. Delay Prediction
Predicts potential project delays by analysing task progress, subcontractor performance, dependencies, and external factors.
File: prompt4_delay_prediction.md
---
5. Site Report Analysis
Analyses daily site reports to extract key insights, classify issues by category and severity, and recommend immediate actions.
File: prompt5_site_report_analysis.md
---
6. Project Risk Assessment
Identifies and evaluates project risks across operational, financial, safety, and compliance categories with mitigation strategies.
File: prompt6_project_risk_assessment.md
---
7. Compliance Checking
Reviews project activities against Australian building codes and WHS requirements to flag violations and recommend corrective actions.
File: prompt7_compliance_checking.md
---
8. Client Update Generation
Generates professional, client-friendly project progress updates in a structured format suitable for weekly or bi-weekly communication.
File: prompt8_client_update_generation.md
---
9. Resource Allocation
Optimises the allocation of subcontractors and resources across project tasks to minimise idle time and avoid over-allocation.
File: prompt9_resource_allocation.md
---
10. Project Performance Insights
Evaluates overall project performance against planned timelines and budgets, identifies root causes of gaps, and provides strategic recommendations.
File: prompt10_project_performance_insights.md
---
Workflow Overview
These prompts form a complete end-to-end subcontractor management workflow:
Step	Prompt	When Triggered
1	Subcontractor Selection	Project planning phase
2	Job Scheduling	After subcontractor selection
3	Cost Estimation	After scheduling, before execution
4	Delay Prediction	During project execution
5	Site Report Analysis	Daily or weekly
6	Project Risk Assessment	Periodically during execution
7	Compliance Checking	During execution
8	Client Update Generation	Weekly or bi-weekly
9	Resource Allocation	During planning and execution
10	Project Performance Insights	At milestones or project end
---
Key Design Principles
All prompts follow a role-based structure (assigning AI a specific professional role)
Each prompt includes clear input requirements, constraints, and structured output formats
Human-in-the-loop is maintained — AI supports decisions, final authority remains with the project manager
Prompts are designed to avoid hallucination by instructing AI not to assume missing data
All prompts were iteratively improved across three versions (v1.0, v1.1, v1.2)
---
Context
Industry: Residential Construction
Location: Melbourne, Australia
Regulatory Reference: Australian Building Codes, Workplace Health and Safety (WHS) Standards
AI Tool Used: ChatGPT (OpenAI)
Purpose: Academic and Professional Demonstration of AI Prompt Engineering in Business Workflows
---
Author
Master of Business Analytics Student
La Trobe University, Bundoora, Victoria, Australia
