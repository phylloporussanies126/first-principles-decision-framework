# First-Principles Thinking Guide Skill

A Claude Code skill that guides users through first-principles thinking to analyze problems, make decisions, and uncover fundamental truths.

## Overview

The First-Principles Thinking Guide is a specialized skill for Claude Code that helps users break through thinking limitations and see the essence of problems. It combines Socratic questioning techniques with deep thinking guidance methods to systematically challenge assumptions and find fundamental truths.

## Core Goal

Help users completely deconstruct the first principles of any problem or issue to reduce decision errors.

## Skill Features

### Core Interaction Rules
1. **Concise questioning**: Ask only 1-2 key questions at a time, focusing on the core
2. **Adaptive questioning**: Ask one question at a time, then modify and improve subsequent questions based on user answers, like a psychological mentor helping to unpack thoughts
3. **Challenge assumptions**: Focus on challenging "human assumptions", "industry conventions", and unverified premises
4. **Timely summary**: Provide structured summary only at the end of conversation

### Three-Stage Questioning Framework

#### Stage 1: Clarification and Challenge
**Goal**: Clarify problem essence, challenge existing assumptions
- Opening: Please briefly describe the problem you want to explore
- Key questions to ask:
  - What common practices or assumptions are involved in this problem?
  - Which practices exist only because "everyone does it this way"?
  - How do you distinguish facts from assumptions?

#### Stage 2: Uncover Truth
**Goal**: Find basic facts, constraints, and underlying principles
- Key questions to ask:
  - What hard constraints does this problem face? (physical, mathematical, logical, resource limitations, etc.)
  - What are the unchangeable basic facts?
  - If you strip away all human-made regulations and assumptions, what remains?

#### Stage 3: Reconstruct Insights
**Goal**: Rethink based on truth, compare new and old solutions
- Key questions to ask:
  - If starting from scratch, based on the basic facts we found, what is the optimal solution?
  - What are the main advantages of this new solution compared to existing solutions?
  - What obstacles need to be overcome to implement the new solution?

### Adaptive Mechanism
- **Interactive questioning**: Ask one question at a time, then modify and improve subsequent questions based on user answers
- **Psychological mentorship**: Act like a thinking partner who helps unpack thoughts gradually, not just a questionnaire
- **Dynamic adjustment**: Adjust questioning depth and direction based on problem complexity and user responses
- **Clarification support**: If user feels confused, provide explanation of questioning purpose
- **User control**: Allow user to request skipping a question or adjusting pace

## Installation

### Method 1: Direct Import (Recommended)
1. Download the `.skill` file from the `skill/` directory
2. In Claude Code, use the skill import feature to load `first-principles-guide.skill`
3. The skill will automatically appear in your available skills list

### Method 2: Manual Setup
1. Clone this repository
2. Copy the `skill/first-principles-guide.skill` file to your Claude skills directory
3. Restart Claude Code if necessary

## Usage Examples

The skill automatically triggers when users need to:
- Think deeply about a problem
- Make important decisions
- Analyze complex situations
- Break down assumptions
- Understand the core essence of any issue

### Example Interaction

**Interactive Dialogue Example**:

**User**: "I'm trying to decide whether to start a consulting business."

**Skill Response (first question)**: "Hello! I'm your first-principles thinking guide. I'll help you uncover fundamental truths about your decision to reduce errors in your thinking.

Let's start with the core: What is the exact decision you're facing regarding starting a business?"

**User Response**: "I'm deciding whether to leave my corporate job to start a consulting business."

**Skill Follow-up (adapting to answer)**: "Thanks for sharing that. What do people typically assume about starting a consulting business in your field?"

**User Response**: "People assume you need lots of startup capital, a fancy office, and full-time commitment from day one. Many consultants also copy big firms' practices like expensive marketing and rigid pricing."

**Skill Follow-up (digging deeper)**: "Interesting. Which of these assumptions exist mainly because 'that's how successful businesses do it' versus what's actually necessary?"

*(The conversation continues with adaptive questioning, exploring constraints, fundamental truths, and fresh perspectives based on each previous answer.)*

## Structured Output Format

After confirming that fundamental truths have been uncovered, the skill provides:

1. **Problem Restatement** - Brief restatement of the core problem
2. **Key Findings** - Challenged assumptions, fundamental truths, core essence
3. **Comparison Table** - Markdown table comparing "First-Principles Solution" vs "Conventional Solution"
4. **Efficiency Analysis** - Differences across time, resources, cognitive load, etc.
5. **Implementation Recommendations** - Actionable steps, risks, success indicators

## Project Structure

```
first-principles-decision-framework/
├── README.md              # This file
├── skill/
│   ├── first-principles-guide.skill  # Claude Code skill file
│   └── SKILL.md           # Skill documentation (English)
└── LICENSE                # MIT License
```

## Use Cases

- **Personal Decisions**: Career choices, major purchases, life planning
- **Business Analysis**: Strategy development, market entry, product design
- **Technical Problems**: System architecture, algorithm design, optimization
- **Creative Work**: Writing, design, artistic direction
- **Problem Solving**: Any situation requiring clear, fundamental thinking

## Benefits

- **Reduces decision errors** by systematically challenging assumptions
- **Uncovers hidden opportunities** by stripping away conventional thinking
- **Saves time and resources** by focusing on what truly matters
- **Improves clarity** by distinguishing facts from assumptions
- **Enhances creativity** by enabling fresh perspectives

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see LICENSE file for details.

## Acknowledgments

Inspired by first-principles thinking methodologies and Socratic questioning techniques.