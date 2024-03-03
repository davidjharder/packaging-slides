---
marp: true
theme: default
size: 4:3

---

# Solus packaging: **Setup**
![bg right 50%](Solus.svg)

---

# Solus packaging: **Setup**

* Solus Help Docs: `help.getsol.us`
* Switching repositories
* Packager file
* Installing extra packages and setup
* GitHub: Clone & fork the Solus monorepo: `github.com/getsolus/packages`
  * Quick repository tour
* Task running tool: `go-task` AKA `task`
* Help functions
* Bump and build a test package

---

# Solus packaging: **Building a new package & updating an existing package**
![bg right 50%](Solus.svg)

---

# Solus packaging: **Building a new package & updating an existing package**

* Building a new package
  * Using the `go-task new -- packagename URL`
  * Filling basic `package.yml` fields
  * Creating a branch and committing changes with `git`
  * Creating a Pull Request
* Updating an Existing Package
  * Using `go-task -- update version URL`

---

# Solus packaging: **Macros**
![bg right 50%](Solus.svg)

---

# Solus packaging: Macros

- What are macros & what does Solus provide
- Identifying build systems
  - `make`, `cmake`, `meson`, others
  - Examples
- Solus 