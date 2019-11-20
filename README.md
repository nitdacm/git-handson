# Git Handson by ACM NITD Kickstart 19

Starter Repository for students to learn Git and Github.

# Instructions

1. :inbox_tray: Clone this repo

	git clone https://github.com/nitdacm/git-handson

2. :cd: Change directory into `git-handson`

	cd git-handson

3. You will find this `README.md` with instructions.

	cat README.md

4. :cd: Change directory into `hello-world`

	cd hello-world

5. :hammer: Your task is to make a `C` program that prints your github username and url. Here is an example.

```c
#include<stdio.h>
int main(void) {
	printf("Hi, I'm Boot-Error and my github profile is https://github.com/Boot-Error");
	return 0;
}
```

6. :boom: After writing your code, save it with your name. Run it for sanity check

	gcc Boot-Error.c && ./a.out

7. If no errors, you can proceed to the `git` part. Comeback to the project directory.

	cd ..

8. First add the file into `staging` or `index`

	git add hello-world/Boot-Error.c

9. Now commit the changes to local repository

	git commit

Write your commit message, like `added hello world code` and then save.

10. :mega: Push the changes to your remote repository, the github.

	git push origin master

11. :tada: Congrats, you have successfully push to remote repository but its not over yet. Await for instructions! 
