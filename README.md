# vhol-demo

This is a demo repo to show how easy it is to get setup with dbt continuous integration and deployment using GitHub Actions.
You should be able to run this self-contained example, use the `yml` workflow files as template, make some minor changes and have your own dbt project up and running with CI/CD in no time.

![](img/Datafold_in_dbt_CI.png)

**Tech Stack:**

- dbt Core
- Snowflake
- GitHub Actions
- Datafold Cloud
- AWS S3

If you have questions unique to your tech stack, schedule a call with us at: [Datafold](https://www.datafold.com/)

## What does success look like?

- Slim CI pipeline that runs and tests only the models that have changed and their downstream models in your pull requests
- Automated Datafold data diffs in your pull requests if you have a Datafold account
- Automated deployment of changed dbt models to production and their downstream models when pull requests merge into the main production branch
- Automated staging schema cleanup after a pull request is closed so you don't have schema clutter

## How to set up S3 for Slim CI

TODO
