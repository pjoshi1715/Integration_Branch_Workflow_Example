# Integration_Branch_Workflow_Example
Team Names:  Sujal, Arav, Siri, Parth

Name of Workflow:  Integration Branch Workflow

Description of Basic Git workflow:
Basic git workflow revolves around master branch and developer branch
Master branch is the main working branch, automatically created by Git
Developer branch is merged into master after the desired features are incorporated 


Description of Integration Branch Workflow: (as summarized by your group)
The Integration Branch is a testing branch which contains many versions of features. After testing and adding code to the integration branches, they can be pushed to the master branch. This ensures that it will be easier to detect errors as the code is split up into multiple integration branches, instead of in one master branch. Basically, the integration branch workflow will make sure that one error will not interfere with the ‘correct’ code. 
Integration branch where all of the code is initially pushed to
Code is tested, fixed, and integrated together in the integration branch
This ensures that code works well together and also isn’t affecting the master branch
Once all of the code in the integration branch is working, the code is pushed to the master branch and the out to production
After the integration branch is merged with the master branch, the integration branch is deleted and the project is complete


Key Differences from basic workflow, and key use cases
Whereas a basic workflow is based on one branch, the integration workflow is based on two branches: the master branch and the integration branch. All decisions in the basic workflow are made within that branch. All changes are made in the integration branch and, once finalized, are pushed onto the main branch. This is ideal for very large projects (mainly software based) with time stamps and many small tweaks. This type of integration can prevent bugs from occurring in main software as each tweak is worked on individually and then merged.

Basic Workflow:
One branch
All decisions and changes made in the same branch
Ideal for small/simple projects

Integration Workflow:
Two branches:
Master
Integration
Decisions and tweaks made in integration branch
Pushed to main branch when complete
Ideal for large (mostly software based) projects
Used by companies that constantly update their OS (i.e. Apple)

Documentation of git commands used, and annotated sample sequence of commands used in creating your repository: 
-included on shared documentation

Link to your Git example repository: https://github.com/pjoshi1715/Integration_Branch_Workflow_Example

Diagram or Diagrams of workflow: https://www.toptal.com/git/git-workflows-for-pros-a-good-git-guide
