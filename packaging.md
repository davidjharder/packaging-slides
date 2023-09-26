---
marp: true

theme: default
---

# Solus Packaging - Setup

* Solus Help Docs: `help.getsol.us`
* GitHub Account
  * Creating an SSH key
  * Authorizing `github-cli`
* Clone & fork the Solus monorepo: `github.com/getsolus/packages`
  * Quick repository tour
* Task running tool: `go-task` AKA `task`
* Bump and build a test package

---

# Solus Packaging - Building a New Package & Updating an Existing Package

* Building a new package
  * Using the `go-task new -- packagename URL`
  * Filling basic `package.yml` fields
  * Creating a branch and committing changes with `git`
  * Creating a Pull Request
* Updating an Existing Package
  * Using `go-task -- update version URL`

---

# Solus Packaging - Macros

- What are macros & what does Solus provide
- Identifying build systems
  - `make`, `cmake`, `meson`, others
  - Examples
- Solus 