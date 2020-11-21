# kottans-frontend
An Education From Kottans

- [x] 0 - <b>Git and GitHub</b> - [Done](#git-entry)
- [x] 1 - <b>Linux, Command Line, HTTP Tools</b> - [Done](#linux)
- [x] 2 - <b>Git for Team Collaboration</b> - [Done](#git-collaboration)


## <a name="git-entry">Git Recap</a>
I actively use git for not a long time and course from Udacity helped me a lot to figure out the things which were not very clear to me. For example, I've had troubles with merging and resolving conflicts. Also it was not clear for me, how git can manage different branches and commits. 
![Screenshot github](./git_and_github/git_udacity.png "UdacityGit")
The main new points that I learned from this course.
 - Flags for `git log`:
 ```
    $ git log --oneline
    $ git log --stat
 ```
 - Command for working with branches `git branch` + commands to create, delete or switch the branch.
 - Command for merging and ways for resolving conflicts.
 - I didn't know that after reset the data is stored in 30 days.


 ## <a name="linux">Linux CLI, and HTTP</a>
 I am not an active Linux user, but have a little experience with it. This course got me better understanding of Linux file system and commands.
 ![Screenshot linux](./task_linux_cli/ls_quiz1.png)
 ![Screenshot linux](./task_linux_cli/ls_quiz2.png)
 ![Screenshot linux](./task_linux_cli/ls_quiz3.png)
 ![Screenshot linux](./task_linux_cli/ls_quiz4.png)
 ![Screenshot linux](./task_linux_cli/ls_conclusion.png)
 In this section I've opened for myself a new Linux commands:
 - `lpr`, `lpq` and `lprm`: send document (or set of documents) for print.
 - flag `-r` to `cp` and `rmdir` for copy or remove directory with files and directories in.
 - `chmod` for add or remove permissions for user or group to read, write file or execute.
 - `ps aux` for watching current processes in the system, this is very usefull when you need to terminate some program and use command `kill`, for which you need to know the ID of the prosess (`ps aux` allows to find it).  
 - also I learned how to make a pipe output.

 From the articles about HTTP I've got:
 - what is HTTP and URL.
 - verbs (what exactly are GET, POST, PU, DELETE and OPTIONS, HEAD, TRACE).
 - the status-codes.
 - formats and information of requests and response messages.
 - which kind of connections may be between servers and clients.
 - importance of identification and authorization of users.
 - cashing abd it's settings.


## <a name="git-collaboration">Git Collaboration</a>
![Screenshot git-collaboration](./task_git_collaboration/git_collaboration_udacity.png)
![Screenshot git-collaboration](./task_git_collaboration/git_course.png)

 I've never worked with remote repos in collaboration, so with these courses I've finally understood:
 - why do we need forks and how they work.
 - `git pull` and `git push` commands.
 - I've understood pull requests and how they work.
 - for me command `git rebase` was new.


