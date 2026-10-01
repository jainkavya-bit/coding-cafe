1. We use the word --global so that the Git configuration applies to alll the repositories on the computer. Otherwise, it would only apply to the current Git repository.
2. .git appeared in ls-a but not in ls. It is a hidden directory. It contains files and information that Git needs to track the repository. 
3. It is offering to track 3 files/folders: README.md, lab4/, and week02/. They are the files and folders currently in the coding-cafe directory. Nothing is anything that I didn't write. 
4. Nothing disappeared from the output. I didn't have the .venv/ folder in the git status output earlier. 
5. .gitignore should be committed. This is because it has code that tells Git which files/folders to leave out of the repository.
6. README.md moved from 'Untracked files' to 'changes to be committed'. In the three-places-model, this means the file was moved from the working directory to the staging area. 
7. Git printed that the commit was created and showed how many files were changed. It said 5 files were changed.
8. The first seven characters of the commit is 2706477. They are the short form of the commiit hash, which identifies the commit. 
9. The four stepps of the lopp are: edit, stage, commit and repeat. 
10. This file name is a standard file that manny software projects use to introduce and explain a repository. It is displayed on the repositoory's main page, so visitors can quickly understand what the project is about. 
11. gh auth login authenticates  your GitHub account in the terminal. It stores the credentials, so GitHub can recognize when you push, instead of having to re-login every time. 
12. The README.md file is showing on the front page of the repository. This is because GitHub automatically uses it as the repository's introoduction.
13. No, ppushing did not change the local history. It just put the existing commits onto GitHub. 
14. A private repository exists on GitHub, but only the people who have been given access or under the collaboorators can see or work with it. A repository that is not on GitHub and is only on my computer cannot be accessed on GitHub at all. 