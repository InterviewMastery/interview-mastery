# Interview Mastery
Interview Mastery is a web application that allows users to connect with others and participate in mock interviews to improve their interviewing skills. With Interview Mastery, users can enter a 1:1 video chat with friends or random people and take turns conducting mock interviews. This platform is perfect for anyone who wants to practice their interviewing skills, whether they are preparing for a job interview, seeking career advice, or simply looking to improve their communication skills.

## Features
1:1 video chat with a friend or a random user
Ability to switch between interviewer and interviewee roles
Option to choose interview questions from a pre-made list or create custom questions
Timer to keep track of interview duration
Feedback section where the interviewer can provide feedback to the interviewee
Analytics dashboard to track user's progress and identify areas for improvement

# Git Repo Setup (InterviewMastery)

### Repo Basics
Each member will fork the main repo and then clone their forked repo. Members then sets the Project Repo as the ```upstream```. Changes are done on each member's fork on a new branch. When a member is ready to commit new code, they add and commit the changes to their forked repo, checkout ```main``` , pull latest upstream changes, and then merge their feature branch. Then members will create a pull request to the main repo. This is done, so members can fix merge issues before issuing a new PR.

__Instructions__:

```bash
git remote add upstream https://github.com/InterviewMastery/interview-mastery
```

**Verify upstream was added:**

```bash
git remote -v

origin  https://github.com/<github_handle>/interview-mastery.git (fetch)
origin  https://github.com/<github_handle>/interview-mastery.git (push)
upstream        https://github.com/InterviewMastery/interview-mastery.git (fetch)
upstream        https://github.com/InterviewMastery/interview-mastery.git (push)
```

**Install the dependencies:**

```bash
npm install
```

#### Pull Request Procedures

```bash
git checkout -b <branch-name>       # work on a new branch on your fork.
git add <files>                     # add changed files.
git commit -m 'descriptive message' # write a descriptive commit message.
git checkout main                   # switch to main branch
git pull upstream main              # pull latest changes from upstream before committing.
git merge <branch-name>             # merge new branch to main, make sure to resolve any merge conflicts before pushing.
git push                            # push to your fork
Go to your fork on Github and initiate a pull request.
```


### License
This project is licensed under the MIT License - see the LICENSE file for details.



