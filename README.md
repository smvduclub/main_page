  
 # The CodeClub-SMVDU (Shri Mata Vaishno Devi University, Katra)

Official website of The CodeClub, SMVDU Katra.

## About

> _This is a platform for newbies. You will find basic information regarding all clubs of smvdu, like code club, AI Circle and pretty much thing which will help you to develop yourself._

 > _A student organisation formed to impart knowledge, experience and ideas to others._

 > _We at CodeClub try our best to impart knowledge related to Computer Science, our and our contacts experiences in that field. Also we discuss ideas to dig deeper to learn._

Contributions, such as typo corrections or bug reports, are very welcome! Feel free to [open or report an issue](\https://github.com/smvduclub/main_page) .

  
## Contributing and developing a feature

1. Make sure you are in the develop branch `git checkout develop`.<br />

2. Sync your copy `git pull --rebase upstream develop`.<br />

3. Create a new branch with a meaningful name `git checkout -b branch_name`.<br />

4. Develop your feature on Xcode IDE  and run it using the simulator or connecting your own iphone.<br />

5. Add the files you changed `git add file_name` (avoid using `git add .`).<br />

6. Commit your changes `git commit -m "Message briefly explaining the feature"`.<br />

7. Keep one commit per feature. If you forgot to add changes, you can edit the previous commit `git commit --amend`.<br />

8. Push to your repo `git push origin branch-name`.<br />

9. Go into [the Github repo](https://github.com/smvduclub/main_page/) and create a pull request explaining your changes.<br />

10. If you are requested to make changes, edit your commit using `git commit --amend`, push again and the pull request will edit automatically.<br />

11. If you have more than one commit try squashing them into single commit by following command:<br />

`git rebase -i origin/master~n master`(having n number of commits).<br />

12. Once you've run a git rebase -i command, text editor will open with a file that lists all the commits in current branch, and in front of each commit is the word "pick". For every line except the first, replace the word "pick" with the word "squash".<br />

13. Save and close the file, and a moment later a new file should pop up in  editor, combining all the commit messages of all the commits. Reword this commit message into meaningful one briefly explaining all the features, and then save and close that file as well. This commit message will be the commit message for the one, big commit that you are squashing all of your larger commits into. Once you've saved and closed that file, your commits of current branch have been squashed together.<br />

14. Force push to update your pull request with command `git push origin branchname --force`.<br/>

15. To update your local copy with remote changes, run the following:<br />

`git fetch upstream develop`<br />

`git rebase  upstream/develop`<br />

This will give you an exact copy of the current remote, make sure you don't have any local changes.<br />

  

  

## Communication

- Use slack for communication 'thecodeclubsmvdu.slack.com'

-  Use Facebook for communication - https://www.facebook.com/codeclubsmvdu/
