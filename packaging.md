---
marp: true
theme: default
size: 4:3
---

# Solus Packaging - Setup

* Solus Help Docs: `help.getsol.us`
* Switching repositories
* Packager file
* Installing pre-requisites
* GitHub Account & authorizing `github-cli`
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