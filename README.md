## Git Merge Practice

This is a practice repo set up for the 01092023 Data Science cohort to practice branches, Git merges, and merge conflicts.

This is at least partly a lesson in best practices, partly about what NOT to do, with a side note of resolving issues that do arise.

#### Instructions

1. Step one, clone this repo! Don't fork it, just clone it.

    >git clone https://github.com/JulianWard147/010923-Git-Merge-Conflict-and-gitignore

2. Step two, make a new branch named after yourself. 

    >git branch *your-name-here*

3. **Checkout that new branch**

    >git checkout *your-name-here*

4. **Double check that you really did checkout that new branch**

5. Open jupyter notebook, and add something, delete something, or in some way change the main-notebook provided.

6. Make a new notebook called 'your-name-notebook', replacing your-name with your name, of course.

7. Make a new .txt file, with a unique name, put your deepest darkest secret inside of it. Then add that file to the .gitignore. 

* Actual depth and darkness of the secret should depend on your confidence in your ability to set the .gitignore correctly.

8. Stage all your changes using git add, and then commit using git commit.

    >git add -A
    
    Note: Usually it's bad practice to use -a when doing git add. We're doing this to demonstrate the .gitignore functionality
    
    >git commit -m "Your message here"

9. Push YOUR BRANCH to the origin.

    Do:
    
    >git push origin *your-branch* 
    
    Don't:

    >git push origin main

10. Open this link in your internet browser: https://github.com/JulianWard147/010923-Git-Merge-Conflict-and-gitignore. (Or, if you're reading these instructions off the README on github.com already, stay put!)

11. Navigate over to the branches tab. 

12. Try to merge your branch into the main branch.

13. (Eventuually!) Use the GitHub interface to resolve the merge conflict created in the main-notebook. *We will review this step together.*

14. Check your work:
- Your branch should appear as 'merged' in the Github interface.
- The notebook you created should appear along with any other individual notebooks.
- The .gitignore should have the file name of your secret .txt file.
- But! Your secret .txt file should not be in the GitHub repo.
