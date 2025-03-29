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
 

---

---

## 🔗 References and Further Reading

1. **[The Unseen Ripple Effect of Code Reviews on Developer Experience – Hatica](https://www.hatica.io/blog/how-code-reviews-impact-developer-experience/)**  
   Discusses how code reviews affect developer morale, growth, and team collaboration, based on real team experiences.

2. **[Code Reviews: The Good, The Bad & The Ugh – LinkedIn Blog by Nic Pegg](https://www.linkedin.com/pulse/code-reviews-good-bad-ugh-nic-pegg-74q3c)**  
   A personal and humorous take on the ups and downs of code reviews in modern software teams.

3. **[How to Review Code Effectively: A GitHub Staff Engineer's Philosophy](https://github.blog/developer-skills/github/how-to-review-code-effectively-a-github-staff-engineers-philosophy/)**  
   Practical advice from a GitHub engineer, with a focus on constructive feedback and avoiding common review pitfalls.

4. **[How I Review Code as a Senior Developer – Medium by Vinh Nguyen](https://medium.com/@vndpal/how-i-review-code-as-a-senior-developer-for-better-results-47e979393483)**  
   Personal techniques used by a senior dev to give meaningful feedback and support junior developers.

5. **[Code Review Best Practices – Palantir Blog](https://blog.palantir.com/code-review-best-practices-19e02780015f)**  
   Best practices rooted in real engineering culture at Palantir, including how to balance feedback and mentorship.
