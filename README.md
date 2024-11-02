# Commit Standards

According to the **[Conventional Commits](https://www.conventionalcommits.org/en)** documentation, semantic commits offer a simple convention for commit messages. This convention defines a set of rules to create an explicit commit history, making it easier to build automated tools.

These commits enable you and your team to quickly understand which changes were made to a code segment.

Each commit is identified by a keyword, which indicate whether it’s a code change, package update, documentation adjustment, visual change, or test update.

## Types and Descriptions

Semantic commits include the following structural elements (types), indicating the purpose of each commit:

- **`feat`** - Indicates a **new feature** in the code (relates to the MINOR in semantic versioning).

- **`fix`** - Indicates that the code **fixes a bug** (relates to the PATCH in semantic versioning).

- **`docs`** - Marks **documentation changes**, such as updates in the README. (No code changes included).

- **`test`** - Used for **test modifications** like creating, updating, or deleting unit tests. (No code changes included).

- **`build`** - Used for modifications in **build files and dependencies**.

- **`perf`** - Identifies **performance-related code changes**.

- **`style`** - Indicates **formatting adjustments** (e.g., semicolons, trailing spaces, linting) that don’t affect code functionality.

- **`refactor`** - Refers to **refactoring** without changing functionality, such as code restructuring or performance enhancements from code reviews.

- **`chore`** - Indicates updates in **build tasks, admin configurations, or packages**, like adding files to `.gitignore`. (No code changes included).

- **`ci`** - Refers to changes related to **continuous integration**.

- **`raw`** - Used for changes in **configuration files, data, features, or parameters**.

- **`cleanup`** - Removes commented code, unnecessary sections, or other cleanup actions for better **code readability and maintainability**.

- **`remove`** - Indicates **deletion of obsolete or unused files, directories, or functionalities**, maintaining project organization.

## Recommendations

- Add a type that is **consistent with the commit title**.
- Keep the **first line limited to 4 words maximum**.
- Use the **commit description** for detailed information.
- Start each message with an **emoji** representing the commit type.
- Use **authentic links** without shorteners or affiliates.

## Commit Additions

- **Footer:** Includes the reviewer’s name and task number in Trello or Jira, e.g., `Reviewed-by: Elisandro Mello Refs #133`.
- **Body:** Provides precise descriptions, showing impacts and reasons for the changes and instructions for future interventions, e.g., `see the issue for details on typos fixed`.
- **Description:** A brief summary of the change, e.g., `correct minor typos in code`.

## Examples

<table>
  <thead>
    <tr>
      <th>Git Command</th>
      <th>Result on GitHub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>git commit -m "Initial commit"</code>
      </td>
      <td>Initial commit</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: Update README"</code>
      </td>
      <td>docs: Update README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "fix: Infinite loop at line 50"</code>
      </td>
      <td>fix: Infinite loop at line 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: Login page"</code>
      </td>
      <td>feat: Login page</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "ci: Update Dockerfile"</code>
      </td>
      <td>ci: Update Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "refactor: Convert to arrow functions"</code>
      </td>
      <td>refactor: Convert to arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "perf: Improve response time"</code>
      </td>
      <td>perf: Improve response time</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "fix: Revert inefficient changes"</code>
      </td>
      <td>fix: Revert inefficient changes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "feat: CSS styling for form"</code>
      </td>
      <td>feat: CSS styling for form</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "test: Add new test"</code>
      </td>
      <td>test: Add new test</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "docs: Comments for LoremIpsum() function"</code>
      </td>
      <td>docs: Comments for LoremIpsum() function</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "raw: RAW Data for year YYYY"</code>
      </td>
      <td>raw: RAW Data for year YYYY</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "cleanup: Remove commented code and unused variables in form validation function"</code>
      </td>
      <td>cleanup: Remove commented code and unused variables in form validation function</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m "remove: Delete unused project files to maintain organization"</code>
      </td>
      <td>remove: Delete unused project files to maintain organization</td>
    </tr>
  </tbody>
</table>

## About the Author

This repository was created and is maintained by **Ciro Cesar Maciel**. I am a Software Engineer passionate about creating efficient and well-documented solutions. I am always looking for new tools and practices that can simplify and improve the development workflow.

In addition to this project, I have been working on other interesting projects related to automation, Artificial Intelligence (AI), browser extensions, and more. I am also beginning to teach what is necessary to learn Artificial Intelligence (AI), helping others to get started on their AI journey.

If you are interested in Software Development, Data Science, AI, or other tech topics, feel free to explore my GitHub profile and connect with me.

### How to Find Me:

- GitHub: [ciro-maciel](https://github.com/ciro-maciel)
- LinkedIn: [Ciro Cesar Maciel](https://www.linkedin.com/in/ciro-maciel/)
- Website: [ciro-maciel](https://www.ciro-maciel.click)

I am always open to new collaborations and projects. If you have an interesting idea or just want to exchange thoughts about development, don't hesitate to reach out!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
