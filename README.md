# Polyquantum
_Collaborative research in quantum science powered by Git.
## About
Polyquantum is a platform, structured as a GitHub repository, for open collaborative research in the field of quantum science.

In Polyquantum, users can openly share a new research idea or collaborate to research projects proposed by other users.

A unique feature of Polyquantum is the transparent tracking of scientific contributions. This is achieved through the distributed version control system [Git](https://en.wikipedia.org/wiki/Git), ensuring that authorship is properly recognized by permanently recording each step of the research process in the Git history. 

More details about Polyquantum can be found on the [ABOUT.md](ABOUT.md) page.

## How to explore and contribute to existing ideas
1. Go to the _Issues_ section and explore the list of all existing projects.
1. Discuss and interact directly by commenting on a specific issue.
2. Each time the discussion produces original material that is worth preserving (ideas, solutions, calculations, etc..), create or edit a Markdown document in the issue subfolder (e.g., `/documents/42/1-solution.md`, `/documents/42/2-alternative-solution.md`, _etc._).
3. Open a Pull Request to merge your file.

## How to create a new research project
1. Open a new **issue** to share a new research idea or a new problem.
2. Once refined, create a subfolder in `/documents/` folder.  
   - Name the subfolder after the issue number (e.g., `/documents/42/`).
   - Create or edit a Markdown document explaining your idea (e.g., `/documents/42/0-main.md`).
   - Include metadata at the top: author, date, source issue.  
3. Open a Pull Request to merge the new subfolder and its internal file.  

## Issues vs. Markdown files
- **Issues** are for open brainstorming, discussions, and comments.  
- **Markdown files** are for finalized ideas and serve as a permanent record.

## Attribution
4. After merging a `.md` document, your contribution and your authorship will be permanently preserved in Git history. This avoids plagiarism.
