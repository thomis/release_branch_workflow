# Process Steps

0 Create repo with license

1 Create feature-0 branch fom main

2 Add changelog.md

3 Add reademe.md

4 feature-0 PR > main (squash merge), delete feature-0

----

5 Create release-1 branch from main

----

6 Create hotfix-1 branch from release-1 branch

7 Add hotfix-1.1

8 Add hotfix-1.2

9 Add hotfix-1.3

----

10 Create hotfix-0 branch from release-1

11 Add hotfix-0

----

12 Create feature-1 branch from main

13 Add feature-1

14 feature-1 PR > main (squash merge), delete feature-1

----

15 hotfix-0 PR > release-1 (squash merge), delete hotfix-0

16 release-1 PR > main (rebase and merge)

----

17 hotfix-1 PR > release-1 (squash merge), delete hotfix-1

18 release-1 PR > main (rebase and merge)
