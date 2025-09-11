# Polyquantum
_Collaborative research in quantum science, version-controlled._

## About
Polyquantum is a platform, structured as a GitHub repository, for open collaborative research in the field of quantum science.

In Polyquantum, users can openly share a new research idea or collaborate on research projects proposed by other users.
A unique feature of Polyquantum is the transparent tracking of scientific contributions. This is achieved through the distributed version control system [Git](https://en.wikipedia.org/wiki/Git), ensuring that authorship is properly recognized by permanently recording research documents in the Git history. 

More details about Polyquantum can be found on the [ABOUT.md](ABOUT.md) page.

## How to explore and contribute to existing ideas
1. Go to the [_Issues_ section](https://github.com/andreamari/polyquantum_test/issues) and explore the list of all existing projects.
1. Discuss and interact directly by commenting on a specific issue.
2. Each time the discussion produces original material that is worth preserving (ideas, solutions, calculations, etc..), create or edit a Markdown document in the issue subfolder (e.g., `/documents/42/1-solution.md`, `/documents/42/2-alternative-solution.md`, _etc._).
   - Name the file starting with a progressive number `#-` (e.g., `2-solution.md`, `3-alternative-solution`). This is to preserve a chronological ordering and to allow a compact reference convention _Polyquantum 42.3 (2025)_ to be used in other issues or in scientific papers.
4. Open a Pull Request to merge your file.

## How to share a new research idea
1. Open a [new *issue*](https://github.com/andreamari/polyquantum_test/issues/new/choose) to share a new research idea/problem/project.
2. Create a Markdown document explaining your idea (e.g., `/documents/42/1-idea.md`).
   - Name the subfolder after the issue number (e.g., `/documents/42/`).
   - Name the file starting with `1-` (e.g., `/documents/42/1-idea.md`) to indicate that this is the first document.
   - Include metadata at the top: author, date, source issue.  
3. Open a Pull Request to merge the new subfolder and its internal file.  

## Issues vs. Markdown files
- **Issues** are optimal for brainstorming, discussions, and quick comments. Autorship of contributions is weakly tracked by the web interface, not by Git.
- **Markdown files** are for more refined ideas/solutions/calculations that are worth preserving as a permanent record in the Git history. Such files can be easily referenced, tracked, and version-controlled. Autorship of contributions is strongly preserved.
