I am using this repository for Git practise.
I commit 3 files in master branch, then I created a new branch named as testbranch and committed 3 different files in it.
Then, I checkout the master branch and merge the testbranch with master branch. After that I pushed the files to the remote repository.
Then I tried to delete the files of testbranch, it could be done by revert the changes of previous merge. We simply have to use this following command "git revert <commit id>". Again, I pushed the new changes to master branch on remote repository.
We have to write the commit id of master branch as we merged the testbranch into the master branch.
After the revert operation, I pushed the new changes back to the remote repository.
Then, I checkout to the testbranch and added some new files in the folder, and set the remote branch as testbranch, so that I can push the files to the testbracnch in remote repository.
Atlast I pushed the files to the testbranch on remote repository.
