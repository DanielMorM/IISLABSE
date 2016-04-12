<<<<<<< HEAD
NOWAK195930 4CS2
=======
gitlab
============

Repository contains the description of laboratory concerning basic usage of revision control system Git, realised during 'Software engineering' course conducted by Institute of Applied Computer Science for students of International Faculty of Engineering.

Files:
----------------
Description of laboratory tasks is in file [git_lab_desc.pdf](https://github.com/tkowals/gitlab/blob/master/git_lab_desc.pdf?raw=true).
Changes that will be introduced in particular tasks are located separate folders inside folder [context]
(https://github.com/tkowals/gitlab/tree/master/context). 
Currently the folder contains one exemplary project.

Concept
-----------------
The structure of laboratory separates the problem of revision control system (which is the main topic) from a project being controlled (which is only an example - context). Changes, which are to be introduced within the example project, are described independently in individual files. The separation enables switching the exemplary context of revision control. By the default it is a webpage, but other types of context are possible, i.e. connected with programming (e.g. Java project) or with software development (e.g. preparation of Law document). The structure of laboratory defines a scenario of introducing changes.
Such generality enforces an adequate description of the laboratory, e.g. instead of the term "Open this page in a browser to check the correctness of the structure after the changes" is a message: "Test the correctness of the changes.". The effect of this operation is a situation in which the student himself must determine how to control the correctness, depending on the type of example.

Scenarios 
----------------
1. Individual work

  1. Initialization and interconnecting local and remote repository.
  2. Initial version of the project.
  3. Creation of branches for seperate features (feature branches).
  4. Partial feature development.
  5. Introducing change in master branch (bugFix) and merging it with feature branches.
  6. Finalizing feature implementation.
  7. Merging features with master branch.
  8. Sending results to remote repository and creation of project release.

2. Teamwork

  1. Remote "cloning" of colleague project on GitHub platform and establishment of local repository on its bases. 
  2. Development of feature 3.
  3. Sending changes to remote repository.
  4. Sending information about changes (pull request) to project owner.
  5. Introduction of changes made ​​by a colleague to your remote repository and create the next release of the project.
>>>>>>> 830ff25b86b36931bb3930d20aa62cfdd67c01d8
