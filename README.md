# Hello-World
Getting Started with Github

GitHub Scenarios:
1.	Master is the main branch where all the code lies, what if there are many developers and all create a new branch from Master, and before you merge your changes to Master branch some other developer has merged his changes. – We need to first run the command 
	Git pull (this will bring all the changes made by other developers to your local code base and then you can merge your branch with your changes.
2.	The actual workflow to work in a project with multiple developers & automation testers with Git.
a.	Create a branch from Master (on doing this all master branch code will come to your branch & now we can do any edits we want in the code to achieve the feature we want to add in the code base)
b.	Once all the changes in ‘feature’ branch is done, commit your changes to the branch.
c.	But suppose meanwhile, some other developer has merged his branch to master so we need to ‘git pull’ to have his changes on our local.
d.	Then create a pull request and select the reviewer as well, and submit the pull request.
e.	Once pull request has submitted, the reviewer will check and review the changes and then approve the pull request.
f.	Now, we can merge our branch to master.

