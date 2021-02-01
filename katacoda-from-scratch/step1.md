## Preparing a Git repository

Katacoda scenarios are generally stored in Git repositories like GitHub. 

In this case we'll assume that GitHub will be used. However, BitBucket, GitLab and other should work in a similar way. Assuming that you already have a GitHub and Katacoda account, go to github.com and create a new repository for your Katacoda courses. Afterwards, copy the repository URL, for example `https://github.com/YOUR_USERNAME/YOUR_KATACODA_REPO_NAME` in your Katacoda profile settings page at `Git Scenario Repository`.

Going back to your GitHub repository, click on `Settings`, then the `Webhooks` tab and configure a new Webook with the following payload URL: `https://editor.katacoda.com/scenarios/updated`. The secret can be found on your Katacoda profile settings page as well. As soon as your webhook is configured correctly you can save it.

The GitHub repository you just finished configuring will be the repository on which your Katacoda tutorials will be stored in.