# Code Reviews

## Introduction

Code reviews are a key part of building high-quality software. They help us catch bugs early, improve code readability, and share knowledge across the team. When done well, they reduce the number of defects in production, foster collaboration, and support learning.

At our company, we use code reviews to ensure our codebase remains clean, secure, and maintainable — and to help everyone on the team grow as developers.

---

## Best Practices (Do’s)

### For Code Authors:
- Keep pull requests small and focused (ideally under 400 lines)
- Include a clear PR title and description explaining the **what** and **why**
- Test your code before submitting it for review
- Tag the appropriate reviewers who know the context
- Respond to feedback with openness and a learning mindset

### For Reviewers:
- Review pull requests promptly — don’t let them pile up
- Ask questions rather than give commands ("Could this be simplified?")
- Focus on logic, design, and clarity more than formatting
- Check for test coverage and edge cases
- Be kind, respectful, and helpful in all comments

---

## Bad Practices (Don'ts)

- Submitting huge PRs that are difficult to review
- Ignoring the PR description or context
- Approving PRs without fully reviewing the code
- Leaving vague or unhelpful comments like “fix this” without explaining why
- Being overly critical or focusing only on small nitpicks

---

## Common Pitfalls

- **Lack of Context:** Not providing sufficient background information in the PR can lead to misunderstandings.
- **Delayed Reviews:** Waiting too long to review PRs can slow down the development process.
- **Fragmented Feedback:** Giving scattered or conflicting feedback without clear action items.
- **Over-Reliance on Automated Tools:** Depending solely on linters or automated checks without human insight.
- **Inconsistent Standards:** Not having a shared understanding of what constitutes quality code or acceptable practices.

---

## Example Workflows

- **Standard PR Workflow:**
  - Developer creates a small, focused PR with a clear description.
  - PR is assigned to one or more reviewers.
  - Reviewers check the code for logic, design, and potential edge cases.
  - Feedback is provided; developer addresses comments.
  - Once all feedback is resolved, the PR is approved and merged.

- **Collaborative Review Session:**
  - A scheduled meeting where developers and reviewers discuss the PR together.
  - The team reviews the code in real-time, clarifying doubts and agreeing on changes collectively.
  - This workflow is especially useful for complex changes or learning opportunities.

- **Asynchronous Review Workflow:**
  - Developers submit PRs and reviewers provide feedback at their own pace.
  - Communication happens via inline comments and follow-up discussions on the PR.
  - This workflow is flexible and accommodates distributed teams across different time zones.
