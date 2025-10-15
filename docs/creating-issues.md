# Creating Issues - Guide for Teachers

This guide explains how to create well-structured issues that can be easily handled by GitHub Copilot or other developers.

## Available Issue Templates

We've created several issue templates to help you request changes without needing to understand the technical details of the codebase. Each template guides you through providing all the necessary information.

### 1. Bug Report
**Use when:** Something is broken or not working as expected

**What it includes:**
- Description of the bug
- Steps to reproduce the problem
- Expected vs. actual behavior
- Severity level
- Additional context like error messages

**Example:** "When I try to register a student for Soccer Team, I get an error message."

### 2. Feature Request
**Use when:** You want to add new functionality to the system

**What it includes:**
- Problem or need being addressed
- Proposed solution
- Acceptance criteria (specific requirements)
- Priority level
- Benefits and alternative approaches

**Example:** "Add a calendar view to see activities organized by day and time."

### 3. Activity Management
**Use when:** You need to add, modify, or remove an extracurricular activity

**What it includes:**
- Type of change (add/modify/remove)
- Activity details (name, description, schedule)
- Maximum participants
- Activity category
- Reason for the change

**Example:** "Add Chess Club that meets Tuesdays and Thursdays, 3:30-5:00 PM, max 15 students."

### 4. UI/Design Enhancement
**Use when:** You want to change how the website looks or improve the user experience

**What it includes:**
- Which part of UI needs improvement
- Current state vs. desired state
- Design specifications (colors, layout, etc.)
- User benefit
- Accessibility considerations

**Example:** "Change the website colors from blue to our school colors: white and lime green."

### 5. API/Backend Enhancement
**Use when:** You need new backend functionality or API endpoints

**What it includes:**
- Type of backend change needed
- API endpoint details
- Request and response formats
- Authentication requirements
- Validation rules

**Example:** "Add endpoint to register multiple students at once instead of one at a time."

### 6. Documentation Update
**Use when:** Documentation is incorrect, missing, or needs improvement

**What it includes:**
- Type of documentation change
- Location of documentation
- Current vs. proposed content
- Reason for change

**Example:** "Add missing documentation for the unregister endpoint in the API reference."

## How to Create an Issue

1. Go to the [Issues page](../../issues) of the repository
2. Click the **"New Issue"** button
3. Select the appropriate template from the list
4. Fill out all required fields (marked with red asterisks)
5. Provide as much detail as possible in optional fields
6. Click **"Submit new issue"**

## Tips for Writing Good Issues

### Be Specific
❌ Bad: "Fix the website"
✅ Good: "When clicking 'Register' for Soccer Team, error appears: 'Failed to register student'"

### Provide Context
Include information about:
- What you were trying to do
- What you expected to happen
- What actually happened
- Any error messages you saw

### Define Success
Use acceptance criteria to clearly state what "done" looks like:
- [ ] Student registration works without errors
- [ ] Success message appears after registration
- [ ] Student appears in the participants list

### Include Examples
Show examples of what you want:
- "Similar to Google Calendar's week view"
- "Like the color scheme on our school's main website"
- Email formats: "john@mergington.edu"

## What Happens After You Submit

1. **Automatic Labels**: The issue will be automatically tagged based on the template you used
2. **Review**: Someone will review your issue to ensure all necessary information is provided
3. **Assignment**: The issue may be assigned to GitHub Copilot or a developer
4. **Implementation**: Work will begin on addressing your request
5. **Updates**: You'll receive notifications about progress on your issue
6. **Closure**: Once complete, the issue will be closed with a summary of changes

## Benefits of Using Templates

✅ **Faster Resolution**: Issues with complete information can be addressed more quickly

✅ **Better Results**: Clear requirements lead to solutions that better meet your needs

✅ **Copilot-Friendly**: Well-structured issues can often be automatically handled by GitHub Copilot

✅ **Less Back-and-Forth**: Providing all details upfront reduces the need for follow-up questions

✅ **Consistency**: Everyone uses the same format, making issues easier to understand and track

## Common Scenarios

### Scenario 1: Activity Schedule Change
**Template to use:** Activity Management

**Fill in:**
- Action: "Change activity schedule"
- Activity name: "Drama Club"
- New schedule details
- Reason: "Teacher availability changed"

### Scenario 2: Website Color Update
**Template to use:** UI/Design Enhancement

**Fill in:**
- UI area: "Overall color scheme/theme"
- Current: "Blue color scheme"
- Desired: "School colors: white and lime green"
- Specific color codes if available

### Scenario 3: Registration Error
**Template to use:** Bug Report

**Fill in:**
- Description of the error
- Exact steps that cause the error
- What you expected to happen
- Error message you see
- How often it occurs

## Need Help?

If you're not sure which template to use or need assistance:
- Check the [Documentation](./how-to-develop.md)
- Open a blank issue and describe what you need
- Someone will help you reformulate it using the appropriate template

## Questions?

For general questions or discussions, use the [Discussions](../../discussions) section instead of creating an issue.
