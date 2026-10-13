# AI Search Experiment Workbench

## Problem

AI-generated answers can mention different brands and cite different websites even when users ask similar questions. Tracking every possible buyer question can be expensive.

## Research question

Can a prompt-selection algorithm identify a smaller set of questions that captures most of the brands and citation domains found in a larger sample?

## Initial industry

Project-management software.

## Initial scope

* 20 buyer-intent prompts
* 2 repeated runs per prompt
* 1 AI-search interface
* Manually recorded responses and citations
* A comparison between random prompt selection and greedy coverage-based selection

## Metrics

1. Brand mention rate.
2. Unique citation domains observed.
3. Citation coverage achieved at a fixed prompt budget.
4. Variation in results across repeated runs.

## Limitations

This is a small exploratory sample. It does not represent every user, AI engine, or possible question. Repeated prompts may not be independent, and results can change over time.

## Success criteria

The experiment runs reproducibly, its calculations can be checked manually, and the report clearly explains the evidence and limitations.
