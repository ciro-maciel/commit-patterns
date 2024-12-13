# Commit Standards

According to the **[Conventional Commits](https://www.conventionalcommits.org/en)** documentation, semantic commits offer a simple convention for commit messages. This convention defines a set of rules to create an explicit commit history, making it easier to build automated tools.

These commits enable you and your team to quickly understand which changes were made to a code segment.

Each commit is identified by a keyword, which indicates whether it’s a code change, package update, documentation adjustment, visual change, or test update.

## Table of Contents

1. [Types and Descriptions](#types-and-descriptions)
2. [Recommendations](#recommendations)
3. [Commit Additions](#commit-additions)
4. [Examples](#examples)
5. [About the Author](#about-the-author)
6. [License](#license)

## Types and Descriptions

Semantic commits include the following structural elements (types), indicating the purpose of each commit:

| **Type**      | **Description**                                                                                             |
|---------------|-------------------------------------------------------------------------------------------------------------|
| `feat`        | Indicates a **new feature** in the code (relates to the MINOR in semantic versioning).                      |
| `fix`         | Indicates that the code **fixes a bug** (relates to the PATCH in semantic versioning).                      |
| `docs`        | Marks **documentation changes**, such as updates in the README. (No code changes included).                |
| `test`        | Used for **test modifications** like creating, updating, or deleting unit tests. (No code changes included).|
| `build`       | Used for modifications in **build files and dependencies**.                                                |
| `perf`        | Identifies **performance-related code changes**.                                                           |
| `style`       | Indicates **formatting adjustments** (e.g., semicolons, trailing spaces, linting) that don’t affect code functionality.|
| `refactor`    | Refers to **refactoring** without changing functionality, such as code restructuring or performance enhancements from code reviews.|
| `chore`       | Indicates updates in **build tasks, admin configurations, or packages**, like adding files to `.gitignore`. (No code changes included).|
| `ci`          | Refers to changes related to **continuous integration**.                                                   |
| `raw`         | Used for changes in **configuration files, data, features, or parameters**.                                |
| `cleanup`     | Removes commented code, unnecessary sections, or other cleanup actions for better **code readability and maintainability**.|
| `remove`      | Indicates **deletion of obsolete or unused files, directories, or functionalities**, maintaining project organization.|

## Recommendations

- Add a type that is **consistent with the commit title**.
- Keep the **first line limited to 4 words maximum**.
- Use the **commit description** for detailed information.
- Start each message with an **emoji** representing the commit type.
- Use **authentic links** without shorteners or affiliates.

## Commit Additions

- **Footer:** Includes the reviewer’s name and task number in Trello or Jira, e.g., `Reviewed-by: Edgar de Oliveira Refs #133`.
- **Body:** Provides precise descriptions, showing impacts and reasons for the changes and instructions for future interventions, e.g., `see the issue for details on typos fixed`.
- **Description:** A brief summary of the change, e.g., `correct minor typos in code`.

## Examples

| Git Command                                                                       | Result on GitHub                                                              |
|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| `git commit -m "Initial commit"`                                               | Initial commit                                                                |
| `git commit -m "docs: Update README"`                                          | docs: Update README                                                           |
| `git commit -m "fix: Infinite loop at line 50"`                                | fix: Infinite loop at line 50                                                 |
| `git commit -m "feat: Login page"`                                             | feat: Login page                                                              |
| `git commit -m "ci: Update Dockerfile"`                                        | ci: Update Dockerfile                                                         |
| `git commit -m "refactor: Convert to arrow functions"`                         | refactor: Convert to arrow functions                                          |
| `git commit -m "perf: Improve response time"`                                  | perf: Improve response time                                                   |
| `git commit -m "fix: Revert inefficient changes"`                              | fix: Revert inefficient changes                                               |
| `git commit -m "feat: CSS styling for form"`                                   | feat: CSS styling for form                                                    |
| `git commit -m "test: Add new test"`                                           | test: Add new test                                                            |
| `git commit -m "docs: Comments for LoremIpsum() function"`                    | docs: Comments for LoremIpsum() function                                      |
| `git commit -m "raw: RAW Data for year YYYY"`                                  | raw: RAW Data for year YYYY                                                   |
| `git commit -m "cleanup: Remove commented code and unused variables in form validation function"` | cleanup: Remove commented code and unused variables in form validation function |
| `git commit -m "remove: Delete unused project files to maintain organization"` | remove: Delete unused project files to maintain organization                  |

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
