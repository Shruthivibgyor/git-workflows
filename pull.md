Git Pull:-
git pull updates your current local working branch, and all of the remote tracking branches. 
What Does git pull Do??
git pull is one of the most used Git commands.
Without running git pull, local repository will never be updated with changes from the remote.
How to Use git pull:-
git pull: Update our local working branch with commits from the remote, and update all remote tracking branches.
git pull --rebase: Update our local working branch with commits from the remote, but rewrite history so any local commits occur after all new commits coming from the remote, avoiding a merge commit.
git pull --force: This option allows you to force a fetch of a specific remote tracking branch when using the <refspec> option that would otherwise not be fetched due to conflicts. 
git pull --all: Fetch all remotes - this is handy if we are working on a fork or in another use case with multiple remotes.