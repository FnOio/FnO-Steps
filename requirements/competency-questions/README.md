This file contains a list of competency questions, the vocabulary aims to answer.

The ID column should identify each question with a numerical ID prefixed by the letters CQ

The Question column should state the question
The Expected Answer column should state the expected answer
The Motivating Scenario column should state the name of the user story, located in the user-stories folder
The SPARQL query column should state the name of the SPARQL query file, located in the sparql-queries folder

# Competency Questions

| ID   | Question                           | Expected Answer                   | Motivating Scenario | SPARQL query          |
|------|------------------------------------|-----------------------------------|---------------------|-----------------------|
| CQ1  | question | answer | [Workflow planning](../use-cases/use-case-workflow-planning.md) | [cq-1.sparql](queries/cq-1.sparql) |

# Requirements

| ID | Requirement | User story | Related competency questions | Proposed by |
|----|-------------|------------|------------------------------|-------------|
| R1 | Costs consist of different **cost components** | [cost aggregation](../user-stories/user-story-cost-aggregation.md) |- | <Sven.Lieber@ugent.be> |
| R2 | The number of **cost components** must be fixed before the planning of a workflow | [cost aggregation](../user-stories/user-story-cost-aggregation.md) |- | <Sven.Lieber@ugent.be> |
| R3 | **Cost components** are aggregated to **costs** based on a **cost aggregation function** | [cost aggregation](../user-stories/user-story-cost-aggregation.md) |- | <Sven.Lieber@ugent.be> |








Unordered set of questions:

- Which steps produce evidence x?
- Which steps are involved in producing evidence x?
- Which evidences are needed in producing evidence x?
- Which evidence is produced by step x?
- Which steps depend on step x?
- Which steps precedes step x?
- Which evidence contains personal information?
- Which evidence contains personal information where no consent is available?
- Which evidence contains personal information where consent is available?
- What type of steps are necessary to produce evidence x?
- Which data does a step change?
- Which data does a step request?
- Which data does a step produce?
- Which step was executed to produce evidence x?


Structured according to patterns of related work:
