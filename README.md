Test Task report

The task was:
- To walk through 8base Quick User Guide
- To make several environment (braches) in workspace
- To make changes in 'Master' using migrating generation and commiting

1. Quick User Guide was quite easy to walk through. It has understandable structure and useful examples. 
Issues I had while walking through:
- Executing the command '8base init . --functions=resolver:myCustomResolver' from paragraph 3.2 "Deploy a Serverless Function (OPTIONAL)" - the error 'Name cannot start with a period.' is shown. Everything goes smooth when executing the command '8base init 'project' --functions=resolver:myCustomResolver' with no period symbol in the name.
- Cloning the repo with starting app - it is said in paragraph 3.3 "Choose a Starter App / Framework for the Frontend" that we shoud go to 'client' directory, then clone repo, and, finally, install dependencies (using npm install). If we do it this way the app will be cloned in /client/{app_name} directory, and npm install won't work until we go to client/{app_name} directory
- The screenshot doesn't match description: in paragraph 2.1. "Building a Data Model" there is a description of the field 'User' we need to create. It is said that option 'Allow multiple Notes per User'=True and option 'Allow multiple Users per Note'=False. But it's vice versa on the screenshot below: 'Allow multiple Notes per User'=False and option 'Allow multiple Users per Note'=True.
- API Explorer link (https://app.8base.com/api-explorer) in paragraph 2.1. "Building a Data Model"  isn't working - it redirects to main dashboard with workspaces. Actual link is: https://app.8base.com/workspace/{your_workspace_id}/api-explorer

2. Branches 'new_env' & 'another_branch' were made

3. Trigger 'myCustomTrigger' was made in 'new_env' branch. Then migration to 'Master' was generated and committed. 
