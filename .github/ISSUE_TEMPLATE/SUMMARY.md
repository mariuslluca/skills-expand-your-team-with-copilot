# Issue Templates Summary

This directory contains 6 comprehensive issue templates designed to simplify change requests for teachers and staff who are not comfortable modifying the program directly.

## What Was Created

### Issue Templates (`.yml` files)

1. **bug_report.yml** - Report bugs or unexpected behavior
2. **feature_request.yml** - Suggest new features or enhancements  
3. **activity_management.yml** - Add, modify, or remove activities
4. **ui_enhancement.yml** - Request UI/styling changes
5. **api_endpoint.yml** - Request backend/API functionality
6. **documentation.yml** - Update or fix documentation

### Configuration

- **config.yml** - Configures issue template behavior and adds helpful links

### Documentation

- **README.md** - Overview of templates in this directory
- **../../docs/creating-issues.md** - Comprehensive guide for teachers

## Key Features

Each template includes:

✅ **Clear Problem Description**: Structured fields guide users to describe what they need

✅ **Acceptance Criteria**: Checkbox lists that define what "done" looks like

✅ **Hints and Tips**: Examples and placeholders show what information to provide

✅ **Context Fields**: Space for additional information, limitations, and related details

✅ **Validation**: Required fields ensure critical information isn't missed

✅ **Automatic Labeling**: Issues are tagged automatically for easy filtering

## Copilot-Friendly Design

These templates are specifically designed to work well with GitHub Copilot:

- **Structured Format**: Consistent YAML structure that Copilot can parse
- **Complete Information**: All necessary context in one place
- **Clear Requirements**: Acceptance criteria as actionable checklists
- **Implementation Hints**: Guidance on which files to modify
- **Technical Details**: Specific formatting (e.g., 24-hour time, email formats)

## Examples of Well-Defined Issues

### Activity Management Example
```yaml
Action: Add a new activity
Activity Name: Chess Club
Description: Learn chess strategies, participate in tournaments
Schedule: Tuesdays, Thursdays
Start Time: 15:30
End Time: 17:00
Max Participants: 20
Category: Academic
Reason: Student requests and teacher availability
```

### UI Enhancement Example
```yaml
Area: Overall color scheme/theme
Current: Blue color scheme
Desired: School colors (white #FFFFFF and lime green #32CD32)
Acceptance Criteria:
- [ ] Header background changed to lime green
- [ ] Buttons use school colors
- [ ] Good contrast maintained
- [ ] Mobile view works properly
```

### Bug Report Example
```yaml
Description: Registration fails for Soccer Team
Area: Student Registration
Steps:
1. Click on Soccer Team
2. Enter john@mergington.edu
3. Click Register
4. Error appears
Expected: Student successfully registered
Actual: Error "Failed to register student"
Severity: High
```

## Impact

This implementation addresses the issue requirements:

1. ✅ **Clear problem description**: Required fields with examples
2. ✅ **Clear acceptance criteria**: Checkbox lists in each template
3. ✅ **Hints, tips, and suggested solutions**: Placeholders and implementation notes
4. ✅ **Limitations and context**: Additional context fields throughout

Teachers can now submit change requests without needing to understand the codebase, and GitHub Copilot can easily process and implement these requests with minimal further explanation.
