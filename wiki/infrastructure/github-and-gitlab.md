# GitHub and GitLab

## GitHub

We use GitHub for version control of most of our projects, both internal and with non-profit organizations. You can find our organization [here](https://www.github.com/CorrelAid).

There are different levels of permissions:

1. Members of the CorrelAid Core Team are **members** of the GitHub organization. Through the GitHub Team _coreteam_ , they have access to a lot of repositories (except of project repositories).
2. Some of the members of the organization are also **owners** of the GitHub organization. That means that they can delete and manage repositories, invite new members etc. (see [GitHub help](https://help.github.com/en/articles/repository-permission-levels-for-an-organization))
3. Everyone else - project team members, "temporary" core team members, external collaborators are added as **collaborators** with read/write access to the relevant repositories they need access to. They are **not** added to the GitHub organization. From the GitHub help:

> Outside collaborators: Repository collaborators can include organization members or outside collaborators. An outside collaborator is a person who has access to one or more organization repositories but is not explicitly a member of the organization, such as a consultant or temporary employee. ([https://help.github.com/en/articles/repository-permission-levels-for-an-organization](https://help.github.com/en/articles/repository-permission-levels-for-an-organization))



### GitHub Actions

CI/CD (Continuous Integration / Continuous Delivery) is an important cornerstone of today's software development best practices. This is why, in general, we encourage CorrelAid teams to use GitHub Actions, e.g. for testing pipelines etc.&#x20;

#### Public Repositories

GitHub Actions is free for public repositories. :tada:

We need to add your repositories to the list of repos for which GitHub Actions is available. To request this, please contact Frie (@frie) on Slack.&#x20;

#### Private Repositories

In principle, CorrelAid supports best practices such as CI/CD and automated testing using GitHub Actions. However, [pricing](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions) can be tricky with cloud resources like GitHub Actions. As a NPO, we have limited financial resources, so we encourage you to think about the following points.

* make **repositories public** whenever possible: GitHub Actions is **free for public repositories** because GitHub is committed to supporting open source. Hence, the easiest solution is to make your repo open-source whenever it's possible. There is no shame in developing code in public, your code doesn't need to be perfect during development! Examples:
  * API wrapper packages (e.g. [pocketapi](https://github.com/correlaid/pocketapi))
  * internal tooling without sensitive data (e.g. [correltools](https://github.com/correlaid/correltools))
* do you really need GitHub Actions or is it a nice add-on? Maybe your repo is more of a fun analysis than something that needs to be stable for the long-term. In this case, maybe you don't really _need_ automated testing?!
* if your repository needs to stay private and you really do need GitHub Actions, consider:
  * because MacOS and Windows are much [more expensive than Ubuntu](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions#minute-multipliers), please avoid running pipelines on those platforms, especially on MacOS (1 min MacOS = 10 minutes on Ubuntu)
  * how often do you need to run the GitHub Action? Does it have to be run on open PRs with every commit triggering a new run? Suggestion:
    * have a `main` branch where you run on every commit. you never commit on `main` directly, except for hot fixes
    * have a `dev` branch. this is the branch you open your PR against. You run your tests on every commit on the `dev` branch.&#x20;
    * you work on feature branches that branch off `dev`. You **don't run** GitHub Actions on the Pull Requests. Instead, you test locally and merge to `dev` to see whether the tests pass for all platforms.
    * You could also investigate running your feature branch / PR tests on Ubuntu only, with MacOS and Windows only run on `dev.`&#x20;

Once you have considered and thought through all those points, please write a message to Frie (@frie) on Slack, explaining the reasoning for a) why your repo needs to be private, b) why you need GitHub Actions and c) your branch and usage concept. If you're unsure about any of the points, Frie can discuss them with you.

Once we have come to an agreement, Frie can add your repo to the list of repositories for which GitHub Actions is available and you can start using it.&#x20;

## GitLab

We also have a GitLab organization: [https://gitlab.com/correlaid](https://gitlab.com/correlaid).

However, we currently do not use it for much. If you want to work with GitLab in your project for any reason, we can also host the project repository there. No problem. :slight\_smile:

## FAQ

See our general FAQ for answers.
