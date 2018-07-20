+ SCM / VCS / RCS
+ Implementations - git, svn
+ Role of git/svn? 
+ Version navigation - branches, tags
+ Collaboration/sharing - team work
+ Distributed model -- every team members has their own copy of code (repository), remote repo for sharing
+ Commits - tracking of all operations (Changelog)
+ Url:- [https://github.com/rajeshsola/ci-demo](ci-demo)
[https://github.com/rajeshsola/jenkins-examples](ci-demo)
+ Git steps:-
+ Created and switched to clean dir
+ Place some files in this, say test.c
##Commands
		
		mkdir hello
		
		cd hello
		
		git init
		
		git add test.c
		
		git commit -m "My first commit"
		
		#create a remote repository on github (any other provider)
		
		git remote add https://github.com/xxxx/hello-world
		
		git push -u origin master
		
##Adding further files

		git add hello.c
		
		git commit  "adding hello.c"
		
		git push origin master
		
## Activity Time:- 

+ Signup for github 
+ Create a first repo,say hello-world
+ Install any git software,e.g.      gitforwindows.org

