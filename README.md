# Polyquantum
_Open, collaborative, version-controlled research in quantum science_

## About
_Polyquantum_ is an open platform for collaborative research in quantum science, structured as a GitHub repository.  
It allows researchers to:

- 💡 Share new research ideas openly  
- 🛠️ Collaborate on ongoing projects proposed by others  
- 📝 Preserve and track research contributions transparently  

A key feature of Polyquantum is the transparent tracking of authorship.  
By using [Git](https://it.wikipedia.org/wiki/Git_(software))’s distributed version control, every research step is permanently recorded in Markdown documents, ensuring proper recognition of contributors.  

👉 More details about Polyquantum can be found in [ABOUT.md](ABOUT.md).

## 🛠️ How to contribute to existing ideas
1. Browse the [**Issues** section](https://github.com/andreamari/polyquantum_test/issues) to see existing research projects.  
2. Interact and discuss by commenting on specific issues.  
3. When discussions produce original material (ideas, solutions, calculations, etc.) that is worth preserving in a (Git-tracked) document:  
   - Create or edit a Markdown file in the subfolder `docs/[NUM_ISSUE]/`.  E.g (for issue #1) :
     ```
     /docs/1/3-alternative-solution.md
     ```
   - Use a progressive number prefix (`1-`, `2-`, `3-` …) in file names for ordering:  
     ```
     1-idea.md
     2-solution.md
     3-alternative-solution.md
     ```
   - In every document, include author(s) and affiliation(s). 
   - The new document can be referenced as: _Polyquantum 1.3 (2025)_, corresponding in this example to Issue #1, document #3.  
4. Open a _pull request_ to merge your contribution. Once reviewed, if accepted, your file will appear in `docs/[NUM_ISSUE]/`.


## 💡 How to share a new research idea
1. Open a [new issue](https://github.com/andreamari/polyquantum_test/issues/new/choose) describing your idea/project/problem.
2. Formalize your idea in a (Git-tracked) Markdown file and place it in the subfolder `docs/[NUM_ISSUE]/`. E.g (for issue #1) :
```
/docs/1/1-idea.md
```
   - Start the file name with `1-` (first document).  
   - Include author(s) and affiliation(s).
   - The new idea can be referenced as:  
      - Whole research project: `Polyquantum 1 (2025)`.
      - Specific first document: `Polyquantum 1.1 (2025)`. 
3. Open a _pull request_ to merge your contribution. Once reviewed, if accepted, your file will appear in `docs/[NUM_ISSUE]/`.


## Usage of Issues vs. Markdown files
- **Issues** are optimal for brainstorming, discussions, and quick comments. Authorship of contributions is (weakly) tracked by the web interface, not by Git.
- **Markdown files** are for more refined ideas/solutions/calculations that are worth preserving as a permanent record in the Git history. Such files are referenced, tracked, and version-controlled. Authorship of contributions is strongly preserved by the Git system.

## License
👉See [LICENSE.md](LICENSE.md) page.

