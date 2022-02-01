# Setting up the project's Github Repo

## Steps or Details
- Engramar to create Github repository and add the relevant contributors
- Main branch should be protected, requiring pull requests before merging by going to the repo > Settings > Branches > Branch protection rules
  - This will ensure we don't run into unnecessary merge conflicts, and will also simulate how code is managed in a team setting 
- Setup Github Issues & Github Project Board for project management
  - See the [Project Eisteddfod repo](https://github.com/codesydney/eisteddfod) for an example of effective usage of Issues and Projects
  - Project board should be a Kanban board containing the following headers
    - Product Backlog / Ideas - Ideas that are not fully fleshed out yet or are not urgent
    - Issues - Issues that we want to actively work on ASAP but have not started work on
    - UX / UI Design - Issues that will need additional design / specifications before being ready for development
    - Ready for Development - Issues that are now ready to start development
    - In Development - Issues that are currently in progress 
    - Code Review - Issues which have a pull request already submitted 
    - UAT - Features that are being tested after being merged into `main`
    - Done - Once it has passed UAT, move to Done
- Setup Project Readme
  - Readme should contain information about what the project is, link to the deployed app, and other relevant links
  - Not sure how to start? Check this out: https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/
- Add the Github repo to the #github_notifications Slack channel by typing `/github subscribe codesydney/<repoName>`
- Add the Github repo to the project Slack channel's bookmarks 

## FAQs
- Can we use our own project management tools like JIRA or Trello?
  - Ideally we can keep everything in the Code.Sydney Github repo, but you may choose to use your own project management tool as long as the group are all agreed, and you link the tool from within the 

## Other relevant resources
