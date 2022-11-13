## Git branching:
<pre>
	-Create new branch && switch to it:
		git checkout -b [new_branch-name]
	-Create sub branch:
		git checkout -b [new_subbranch-name] [current-branch]
	-Delete branch:
		git branch -d [branch-name]
	-Switch to another branch:
		git checkout [existing-branch]
	-Current branch
		git branch
</pre>

## Git status

Checks the status of all repos within a folder

<pre>
FOR /D %%G in ("*") DO (
    cd %%~nxG
    git status
    cd ..
)
</pre>

## Git pull

Tries to fetch up-to-date information of all repos within a folder

<pre>
FOR /D %%G in ("*") DO (
    cd %%~nxG
    git pull
    cd ..
)
</pre>