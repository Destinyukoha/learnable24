# learnable24
what is version control? 
    This is the system that helps tracks change to files over time,allowing multiple people people to callaborate on project and keeping a record of modifications.                               
Explain the difference between git and github?
    Git and Github are related but serve different purposes in the world of version control and software development 
    KEY DIFFERENCE ARE:
    GIT: allows you to manage code history and collaboration on a local machine.
    WHERE AS GITHUB:IS a platform that enables remote collaboration, sharing , and hosting of git repositories with additional features for community engagement and team collaboration online.
EXPLAIN THE DIFFERENCE BETWEEN GIT FETCH AND GIT PULL?
    GIT FETCH: downloads changes from the remote repository,but DOES NOT MERGE them into your current branch. Allows you to inspect the change befpore deciding to merge.
    WHEREAS GIT PULL:Downloads change and immediately merge them into your current branch, updating your working directory.
EXPLAIN THE SIMPLE TERMS, GIT REBASE AND COMMAND FOR IT?
    IN SIMPLE TERMS,Git rebase is a command in git used to intrgrate change from one branch another.it allows you to apply commit from one branch onto another, typically to keep a linear project history.
    COMMAND FOR IT(COMMON USEAGE):
    Git rebase<branch>
    Git checkout feature-branch
    Git rebase main
    HANDLING CONFLICTS:
    Git rebase --continue
    TO CANCEL THE REBASE:
    git rebase --absort.
Explain in simple terms git cherry-pick and the command for it?
    In simple terms, git cherry-pick is a command used to apply a specific commit (or changes from a commit) from one branch to another. This is useful when you want to bring in a single change from another branch without merging the entire branch.
    COMMAND:
    git cherry-pick <commit-hash>
    EXAMPLE:
    First, find the commit hash you want to cherry-pick (you can use git log to see the commit history).
    SECONDLY,Switch to your target branch (e.g., branch A)
     git checkout branchA
    thirdly,Run the cherry-pick command:
     git cherry-pick abc1234
    This applies the changes from commit abc1234 to branch A.


