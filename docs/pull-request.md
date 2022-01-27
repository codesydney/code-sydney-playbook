# Managing version control / branches / pull requests

We use Github to manage our code as a team. Using Github's pull request functionality will ensure that we keep our codebase free of conflicts, while also maintaining a clean history of changes. 

## Steps
- For a video overview, click [here](https://www.youtube.com/watch?v=xbD5lDCzvP8)
- Whenever you work on a new feature, do not develop on the `main` branch. We will put some control to prevent this from happening.
- Make sure your repo is up to date with the Github repo, with a `git pull`
- Create your own feature branch by navigating to the root of the directory and typing `git checkout -b "name-of-feature"`
  - Ideally you will just create one branch per feature or issue, to allow for easy merging and code review later on
  - If you are working on a branch that is tied to a Github Issue, then it's best to name the branch after the issue
- Work on your feature branch as normal and make sure to save all your files
- Once you are ready to push your code do `git add .` to stage your files for commit
- Commit your changes with a message of what you changed with `git commit -m "message you want to add"`
- Push your changes with `git push origin "name-of-branch"`. The terminal should return a Github link.
  - Click through to the Github link and you should now be on a Pull Request page.
- Edit the details of your pull request and add your teammates as reviewers
- Once the PR has been reviewed, you can merge into the `main` branch and safely delete the branch from within Github
- Remember to `git pull` into your `main` branch locally to keep everything up to date before working on your next feature

## FAQs

## Other relevant resources
