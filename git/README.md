[go back](../README.md)


   #### Create a free tier GitHub account 
   
   https://github.com/join?plan=free&source=pricing-card-free

   #### Create a free tier Azure DevOps account 
    
   https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/

   #### Check out https://github.com/sjultra/inspec-gcp-cis-benchmark

   #### Make a commit to a test log file.  Record your name and date.

#### Markdown 

  https://guides.github.com/features/mastering-markdown/#intro

#### Git commands for updating the local repo

    1. Open Terminal.
    
    2. Change the current working directory to your local project.
    
    3. Fetch the branches and their respective commits from the upstream repository. Commits to master will be stored in a local branch, upstream/master.

      $ git fetch upstream
       > remote: Counting objects: 75, done.
      > remote: Compressing objects: 100% (53/53), done.
       > remote: Total 62 (delta 27), reused 44 (delta 9)
      > Unpacking objects: 100% (62/62), done.
      > From https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY
      >  * [new branch]      master     -> upstream/master

    4. Check out your fork's local master branch.

      $ git checkout master
      > Switched to branch 'master'

    5. Merge the changes from upstream/master into your local master branch. This brings your fork's master branch into sync with the upstream repository, without losing your local changes.

      $ git merge upstream/master
      > Updating a422352..5fdff0f
      > Fast-forward
      >  README                    |    9 -------
      >  README.md                 |    7 ++++++
      >  2 files changed, 7 insertions(+), 9 deletions(-)
      >  delete mode 100644 README
      >  create mode 100644 README.md

    If your local branch didn't have any unique commits, Git will instead perform a "fast-forward":

      $ git merge upstream/master
      > Updating 34e91da..16c56ad
      > Fast-forward
      >  README.md                 |    5 +++--
      >  1 file changed, 3 insertions(+), 2 deletions(-)

