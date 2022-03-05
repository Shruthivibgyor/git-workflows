Git clone:-
The git clone command is used to create a copy of a specific repository or branch within a repository.
What Does git clone Do??
By cloning with Git, we get the entire repository - all files, all branches, and all commits.
Cloning a repository is typically only done once, at the beginning of the interaction with a project. 
Once a repository already exists on a remote, like on GitHub, then we would clone that repository so we could interact with it locally. 
Once we have cloned a repository, we won't need to clone it again to do regular development.
How to Use git clone:-
git clone [url]: Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits.
git clone --mirror: Clone a repository but without the ability to edit any of the files. This includes the refs, or branches.
git clone --single-branch: Clone only a single branch.
git clone --sparse: Instead of populating the working directory with all of the files in the current commit recursively, only populate the files present in the root directory. 
Related Terms:-
git branch: This shows the existing branches in our local repository. 
 can also use git branch [banch-name] to create a branch from our current location, or 
 git branch --all to see all branches, both the local ones on our machine, and the remote tracking branches stored from the last git pull or git fetch from the remote.