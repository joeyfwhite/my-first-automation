# My First AI Automation Project

## Project Overview
This is my first Claude Code project. I'm learning the WAT framework and building simple automations.

## Project Structure
- **workflows/**: Markdown files that define automation procedures
  - Each file = one complete automation
  - Format: Objective, Inputs, Steps, Expected Output
  
- **tools/**: Python scripts that do the actual work
  - Each script = one specific task
  - Examples: scrape_web.py, send_email.py, format_data.py

- **.claude/skills/**: Reusable instruction sets
  - Load automatically when relevant
  - Can be invoked with /skill-name

## Agent Guidelines
1. **Ask Before Acting**: If a task is ambiguous, ask clarifying questions
2. **Plan Then Execute**: Create the workflow file first, then execute
3. **Document Everything**: Every tool should have comments explaining what it does
4. **Test Incrementally**: Test each tool independently before combining them
5. **Use the Feedback Loop**: After running, ask me for feedback and improve

## Error Handling
- If any tool fails, log the error
- Try alternative approaches if the first one fails
- Never silently skip steps

## Coding Conventions
- Use snake_case for all file and variable names
- Include docstrings in all Python functions
- Store API keys in .env file (never hardcode)
- Add comments for complex logic

## Tools I'll Build
(Update this as you add tools)
- [ ] Tool 1: (description)
- [ ] Tool 2: (description)
- [ ] Tool 3: (description)

## Workflows I'll Create
(Update this as you add workflows)
- [ ] Workflow 1: (description)
- [ ] Workflow 2: (description)
