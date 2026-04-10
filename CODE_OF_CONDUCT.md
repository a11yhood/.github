
## Community Norms

The [A11yhood](https://github.com/a11yhood) community prioritizes accessibility and inclusion. Contributors, and contributions, should uphold those values. 

- **Be respectful.** Critique ideas, not people. Assume good intent and ask questions before drawing conclusions.
- **Center the mission.** A11yhood exists to connect accessibility resources to people. When making decisions about features, language, or design, consider how choices affect the people this platform is built for.
- **Use inclusive language.** Prefer person-first and identity-first language as appropriate. Avoid ableist, racist, or otherwise exclusionary language in code, comments, documentation, and discussions.
- **Respect lived experience.** Contributions from people with disabilities and other marginalized identities are especially valuable. Make space for those perspectives.
- **Keep things accessible.** Accessibility is a core value of this project, not an afterthought. When contributing UI changes:
  - Use semantic HTML. Prefer native HTML elements (`<button>`, `<nav>`, `<main>`, `<section>`, `<header>`) over generic `<div>` or `<span>` elements where meaning matters.
  - When using MUI components, use the `component` prop to preserve semantic HTML (e.g. `<Container component="section">`).
  - Ensure interactive elements are keyboard accessible and have visible focus states.
  - Do not rely on color alone to convey meaning.
  - Use ARIA attributes only when native HTML semantics are insufficient — prefer correct HTML over ARIA patches.
  - Test with a screen reader if you are making significant UI changes.
- **No spam or self-promotion.** Issues and pull requests should be relevant to the project.

Contributors who do not follow these ground rules may be asked to revise their contributions or removed from the project.

