# Polyquantum
_Open, collaborative, version-controlled research in quantum science_

---

## About

**Polyquantum** is an open platform for collaborative research in **quantum science**, structured as a GitHub repository.  
It allows researchers to:

- 💡 Share new research ideas openly  
- 🤝 Collaborate on ongoing projects proposed by others  
- 📝 Preserve and track research contributions transparently  

A key feature of Polyquantum is the **transparent tracking of authorship**.  
By using Git’s distributed version control, every contribution is permanently recorded, ensuring proper recognition of contributors.  

👉 More details can be found in the [ABOUT.md](ABOUT.md) page.

---

## 🤝 How to Explore & Contribute to Existing Ideas

1. Browse the [**Issues** section](https://github.com/andreamari/polyquantum_test/issues) to see existing research projects.  
2. Interact and discuss by commenting on specific issues.  
3. When discussions produce original material (ideas, solutions, calculations, etc.):  
   - Create or edit a Markdown file in the corresponding issue subfolder:  
     ```
     /documents/42/2-solution.md
     /documents/42/3-alternative-solution.md
     ```
   - Use a progressive number prefix (`1-`, `2-`, `3-` …) for ordering:  
     ```
     2-solution.md
     3-alternative-solution.md
     ```
   - In every document always include **author(s)** and **affiliation(s)**. 
   - Suggested citation format: _Polyquantum 42.2 (2025)_, correspnding in this example to Issue #42, document #2.  
4. Open a **Pull Request** to merge your contribution.

---

## 💡 How to Share a New Research Idea

1. Open a [new issue](https://github.com/andreamari/polyquantum_test/issues/new/choose) describing your idea/project/problem.  
2. Create a Markdown file in a new subfolder (named after the issue number):
```
/documents/42/1-idea.md
```
- Always start with `1-` for the seed document.  
- Include **Author(s)** and **Affiliation(s)**.  
- Suggested citation formats:  
  - Whole research project: `Polyquantum 42 (2025)`  
  - Specific seed document: `Polyquantum 42.1 (2025)`  
3. Open a **Pull Request** to merge your new project folder and seed document.

---

## Issues vs. Markdown files
- **Issues** are optimal for brainstorming, discussions, and quick comments. Autorship of contributions is (weakly) tracked by the web interface, not by Git.
- **Markdown files** are for more refined ideas/solutions/calculations that are worth preserving as a permanent record in the Git history. Such files are referenced, tracked, and version-controlled. Autorship of contributions is strongly preserved by the GIT system.

---

## 📜 License

👉See [LICENSE.md](LICENSE.md) page.

