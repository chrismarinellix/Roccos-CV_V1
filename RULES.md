# Development Rules & Guidelines

## 🚫 STRICT NO-CHANGE POLICY

### Core Rule
**NO CODE CHANGES ARE PERMITTED WITHOUT EXPLICIT USER REQUEST**

All modifications to `index.html` must be:
1. Explicitly requested by the user
2. Clearly specified with exact requirements
3. Confirmed before implementation

## Code Modification Rules

### ✅ ALLOWED Changes (Only with explicit user request)
- Content updates requested by user
- Style modifications specified by user
- Structure changes explicitly asked for
- Bug fixes identified and approved by user

### ❌ PROHIBITED Changes (Never do these)
- "Improvements" not requested by user
- Code refactoring without permission
- Style "enhancements" not asked for
- Adding features user didn't request
- Removing features without instruction
- Changing formatting preferences
- Updating libraries or dependencies
- Optimizing code without request

## Content Update Protocol

### When User Requests Changes:
1. **Confirm Understanding**: Repeat back what changes are requested
2. **Ask for Clarification**: If anything is unclear
3. **Make ONLY Requested Changes**: Nothing more, nothing less
4. **Preserve Everything Else**: Don't touch unrelated code

### What to Preserve:
- Exact indentation style
- Comment placement (even if empty)
- Spacing preferences
- Naming conventions
- Code organization
- Existing formatting

## Development Principles

### 1. User Authority
- The user has absolute authority over all code
- User preferences override "best practices"
- User's existing code style must be maintained

### 2. Minimal Intervention
- Change only what is explicitly requested
- Preserve all existing code characteristics
- Don't fix what isn't broken
- Don't optimize unless asked

### 3. Transparency
- Explain what will be changed before changing
- Show exact modifications being made
- Confirm completion of requested changes only

## Version Control Rules

### Git Commits
- Only commit when user requests
- Use user's specified commit messages when provided
- Don't create automatic commits
- Don't push without user instruction

### Branches
- Stay on main unless instructed otherwise
- Don't create feature branches without request
- Don't merge without explicit permission

## File System Rules

### File Creation
- Only create files explicitly requested
- Don't create "helpful" additional files
- Don't generate documentation unless asked
- Don't add config files without permission

### File Modification
- Only modify files user specifies
- Don't update related files without asking
- Don't create backups without request
- Don't rename files without instruction

## Communication Rules

### Before Making Changes
```
User: "Update the email address"
Assistant: "I'll update only the email address in the header. The current email is X, changing to Y. Should I proceed?"
```

### After Making Changes
```
Assistant: "Updated the email address from X to Y as requested."
```

### When Tempted to Suggest Improvements
```
❌ DON'T: "I've also improved the CSS and fixed some formatting issues"
✅ DO: "Email updated as requested. I notice [issue] - would you like me to address this?"
```

## Common Scenarios

### Scenario 1: User asks for content update
- Change ONLY the specific content mentioned
- Don't update dates automatically
- Don't fix typos in other sections
- Don't update related content

### Scenario 2: User reports a bug
- Confirm the exact issue
- Ask how they'd like it fixed
- Fix only the confirmed bug
- Don't fix other "bugs" you notice

### Scenario 3: User asks for styling change
- Modify only the specific style requested
- Don't adjust related styles for "consistency"
- Don't update color schemes globally
- Keep changes isolated

## Emergency Overrides

The ONLY exceptions to these rules:
1. Security vulnerabilities actively being exploited
2. User explicitly asks for suggestions/improvements
3. User requests "fix all issues" or similar broad instruction

## Remember

> "The user's code is sacred. Touch only what you're asked to touch."

## Enforcement

These rules are MANDATORY and override:
- Best practices
- Code standards
- Personal preferences
- Industry conventions
- Optimization opportunities

## User Rights

The user has the right to:
- Messy code
- Inefficient solutions
- Unconventional approaches
- Personal preferences
- Ignore suggestions
- Keep "broken" code if they want

## Final Word

**When in doubt, DON'T CHANGE IT**

If you're unsure whether a change was requested:
1. Don't make the change
2. Ask for clarification
3. Wait for explicit confirmation
4. Then proceed only with confirmed changes