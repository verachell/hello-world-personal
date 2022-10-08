# hello-world-personal
Nothing to see here. My test repository for using GitHub, plus other bits and pieces that don't fit in anywhere else.

More info: I'll add more info here as needed.

## Reminder to self when creating new releases
First, create new branch if have not done so already (typically the dev branch, which I always prefer to delete after merging).

It helps to have drafted release notes somewhere to copy and paste in when prompted - these will wind up going in several places in the next steps

Next, in that dev branch, go to upload new files - these files should have the same name as the old files. This is better than deleting and then uploading, because a straight upload allows diff to be able to compare them. Upload the changed files into that new branch AND make sure that there is a short but meaningful description of changes for each file in the GitHub field.

Then once all files are uploaded, create a pull request to merge dev to master. Then do pull request, it will prompt for deletion of dev after, accept that.

After the merge, go to releases and draft a new release. Add tag w release number, title the release the same as the tag (e.g. 1.2.0). No need to add files etc it will take them automatically from master.
