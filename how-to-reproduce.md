# How I reproduced the bug

1.	Created this repo
2.	Created readme in master
3.	Fork master to branch-test
4.	Create testfile1.md in branch-test
5.	Open PR branch-test to master
6.	Create testfile2.md in master
7.	Open PR master to branch-test
8.	Edit readme in master
9.	Edit readme in branch-test
10.	Used Github GUI to resolve conlflict - hit merge commit
11.	****(PR tab shows it going from 2 to 1 open PRs****
12.	Ergo: I never merged PR 1 but it merged itself based on the no. 10 merge commit action
13.	I can then merge PR2 (which is what I've done in the past, then realized that the other PR somehow got merged)
