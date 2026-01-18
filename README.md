# NoteSense – AI Agent for Notes to Facts, Decisions, and Actions

## Overview
NoteSense is a prompt-based AI agent that converts raw, unstructured notes
(from student lectures or meetings) into clear and actionable information.

Instead of summarizing, the agent separates notes into:
- Verifiable Facts
- Explicit Decisions
- Action Items
- Uncertainties

## Problem
Notes are often written quickly and revisited later with confusion.
It becomes unclear what was important, what was decided, and what needs to be done.

## Solution
NoteSense uses a structured 4-layer agent architecture to first understand,
then reason, and finally produce a clean output without assumptions.

## Agent Architecture

1. Input Understanding  
   Identifies context, topics, and signals in raw notes.

2. State Tracker  
   Maintains internal context such as lecture vs meeting, topics, and uncertainties.

3. Task Planner  
   Plans how to extract facts, decisions, and actions without guessing.

4. Output Generator  
   Produces a structured and readable final result.

## What This Agent Does NOT Do
- Does not summarize or paraphrase
- Does not invent missing information
- Does not provide advice or prioritization

## Example

**Input:**
exam mid march, sir said normalization esp 2nf, assignment next friday, shubham slides

**Output:**
- Facts: exam timing, topic emphasis
- Decisions: none explicitly stated
- Actions: assignment due next Friday
- Uncertainties: meaning of "Shubham slides", exact exam date

## Build Notes
This agent was designed and iterated entirely inside ChatGPT.
The focus of this repository is agent reasoning, prompt design, and exploration logs,
not production deployment.
