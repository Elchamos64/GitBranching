# Team 3.14159
- [Main Branch](#main)
- [Developer Branch](#dev)
- [Individual Branch](#ind)
- [Features Branches](#feature)
- [How to Merge a Branch](#merge)

## Main Branch <a id="main"></a>
### About the Branch:
The main branch is the main branch of the project. It is the branch that contains the latest stable version of the project. This branch should not be updated until it has gone through QA and tested all the features properly
## Developer Branch <a id="dev"></a>
The name of the branch is `developer_branch` you can access this branch either thorugh vs code by switching the branch you are working on the bottom left corner of your screen, or through the command line with the following command `git checkout nameOfBranch`. 

If you need to make a copy of this branch because you need to work on a feature you can use the following command `git checkout -b oscars-feature developer_branch` this will create a branch called `oscars-feature` with a copy of the all the information that is in the `developer_branch`. 
## Individual Branches <a id="ind"></a>
Branches are meant to be used for 1 feature only. So If you need to work on many features make sure you create equal amount of branches. For example, if I were working on 3 features I will create 3 branches like so:
- `feature1_branch`
- `feature2_branch`
- `feature3_branch`

## Features Branches <a id="features"></a>

## How To Merge a Branch <a id="features"></a>
When merging a branch make sure you run the following commands:
- `git add .`
- `git commit -m "your message goes here"`

Once you have added the commit message you are ready to go ahead and merge the changes to the developer_branch. To do this, you are going to switch to the developer_brach (which is the branch you are merging the changes into) and use the following command `git merge feature_branch` this will merge the changes from the branch you are working on to the developer branch.

Hopefully, this will go smooth and you won't have any merge comflicts. If you do, go to the [Merge Conflicts](#conflict) section.
