# learn_git

#Open Questions
1. is git branch -M <name> the same as git checkout -b <name> (respectivley git branch ... & git switch <name>)
2. is git switch <name> <==> git checkout <name>
3. how to write a fancy README
	Answer : you dont
4. why does it say my local main branch is ahead of upstream when "git switch main" but says nothing at all when switching to b_one
	Answer : Because there was no upstream for the other branches (exept main)
		 I did set it with git push --set-upstream origin branch tho
5. Is it bad practice to merge branches localy and then just push. When shuld you use PR and when just merge 'quietly'
