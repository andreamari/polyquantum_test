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
3. To contribute original material (ideas, solutions, calculations, etc.) that is worth preserving in a (Git-tracked) document:  
   - 👉 Follow [this guide](docs/README.md) to create or edit a Markdown file in the subfolder `/docs/[NUM_ISSUE]/`.  E.g (for issue #1) :
     ```
     /docs/1/3-alternative-solution.md
     ```
   - In every document, include author(s) and affiliation(s).
4. If accepted, the new (or modified) document will be published in `/docs/[NUM_ISSUE]/` and permanently tracked by the Git system.
5. The document can be referenced as _Authors_, _Polyquantum 1.3 (2025)_ corresponding, in this example, to project #1, document #3, created in 2025.  



## 💡 How to share a new research idea/project/problem
1. Open a [new issue](https://github.com/andreamari/polyquantum_test/issues/new/choose) describing your idea/project/problem.
2. A new subfolder `/docs/[NUM_ISSUE]/` containing a `README.md` file (referencing your new issue) will be automatically created. 
3. To preserve your idea/project/problem in a (Git-tracked) document:  
   - 👉 Follow [this guide](docs/README.md) to create a new Markdown file in the subfolder `/docs/[NUM_ISSUE]/`.  E.g (for issue #1) :
     ```
     /docs/1/1-is-quantum-theory-complete.md
     ```
   - In the document, include author(s) and affiliation(s).
4. If accepted, the new document will be published in `/docs/[NUM_ISSUE]/` and permanently tracked by the Git system.
5. The new research project can be referenced as:
    - _Polyquantum 1_ (short notation);
    - _Authors_, _Polyquantum 1 (2025)_ corresponding, in this example, to the whole project #1, created in 2025;
    - _Authors_, _Polyquantum 1.1 (2025)_ corresponding, in this example, to project #1, specific document #1, created in 2025.

## Usage of Issues vs. Markdown files
- **Issues** are optimal for brainstorming, discussions, and quick comments. Authorship of contributions is not tracked by Git (it's similar to posting in a blog or social media).
- **Markdown files** are for more refined ideas/solutions/calculations that are worth preserving as a permanent record in the Git history. Such files are referenced, tracked, and version-controlled. Authorship of contributions is permanently preserved by the Git system (it's similar to posting in the [arXiv](https://en.wikipedia.org/wiki/ArXiv) repository).

## License
👉 Your contribution and the structure of this repository are licensed according to the [LICENSE.md](LICENSE.md) document.

