# github-action-qa-reviews

# QA Reviews Teams Notification

This Github Action sends a notification to Teams saying if a Pull Request Comment contains 'QA_TEST', then it will send a notification to a Teams channel named something like "`TEAM_NAME_HERE` QA Reviews". 

The notification would tell the user the following:
- `Commit message here` is Ready for Testing
- Who opened the Pull Request
- What Repository the Pull Request
- What Branch the pull request came from
- A link to the Pull Request

