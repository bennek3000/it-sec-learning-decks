# IT Security Learning Deck – Style Guide

This guide outlines the standards for writing, formatting, and organizing study decks in the it-sec-learning-decks repository.
It ensures every deck (e.g., Blue Team Basics, Search Engine Basics, Offensive Security Basics) has a unified structure and professional style.

## 1. Deck Structure

Each deck should start with:

- A title (clear and descriptive)
- A short summary paragraph describing the topic and learning goal
- The cards, formatted consistently in Markdown

### Example Header
```markdown
# Blue Team Basics

A study deck covering the fundamentals of defensive cybersecurity, including SOC operations, threat intelligence, incident response, and malware analysis.  
Designed to reinforce key Blue Team concepts for learners pursuing cybersecurity or SOC roles.
```

## 2. Card Format

Each card follows the same clean format:

```markdown
### Card [Number]
**Q:** [The question written clearly and directly]  
**A:** [A concise and accurate answer in plain English.]

---
```

### Example
```markdown
### Card 1
**Q:** Why is user cybersecurity awareness training essential?  
**A:** It helps employees recognize and avoid cyber threats, reducing the risk of attacks caused by human error or manipulation.

---
```

### Guidelines

- Keep questions short and specific (one concept per card)
- Use bold **Q:** and **A:** for clarity
- Separate each card with a horizontal line `---`
- Include examples only when they add clarity (e.g., **Example:** command)

## 3. Writing Style

### Tone

- Professional, educational, and neutral
- Avoid slang or overly technical jargon unless necessary
- Write in complete sentences; aim for clarity over complexity

### Voice

- Use active voice:
  - "Firewalls block malicious traffic," not "Malicious traffic is blocked by firewalls."
- Use present tense for general facts

### Length

- Keep each answer 1–2 sentences, max 3 if it adds clarity
- Shorter is better for flashcards and mental recall

### Examples

- Include examples sparingly for commands or tools
- Good: **Example:** `site:example.com`
- Avoid: Don't add long code snippets or logs